# Lecture-5-Exercises-and-Solutions

Lecture 5 Exercises

SLIDE 2, Biography

    #include <iostream>
    using namespace std;

    int main(){
        //cout means character output
        cout << "Name: Jamela Rose E. Alcantara" << endl;
        cout << "Hometown: Laguna, Philippines" << endl;
        cout << "Age: 18 years old" << endl;

        return 0;
    }
    
SLIDE 4, Temperature (Fahrenheit to Celsius)

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
        double f; //fahrenheit
        double c; //celsius

        cout << "Enter the temperature in Fahrenheit to be converted into celsius\n";
        cin >> f;

        c = (f - 32) * 0.5556; //formula of celsius from fahrenheit

        cout << "The temperature in Celsius is: " << c << endl;

        return 0;
    }

SLIDE 5, Temperature (Celsius to Fahrenheit)

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
        double f; //fahrenheit
        double c; //celsius

        cout << "Enter the temperature in Celsius to be converted into Fahrenheit\n";
        cin >> c;

        f = (f * 1.8) + 32; //formula of fahrenheit to celsius

        cout << "The temperature in Fahrenheit is: " << f << endl;

        return 0;
    }
    
SLIDE 5, Circles

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
        double r, area, circum; //variables, double defines and holds any numerically valued data type especially any decimal oriented value
            cout << "The radius to find the area and circumference of the circle: \n"; //character output
        cin >> r; //character input for the radius
        area = (22 / 7) * r * r; //formula for area of the circle
        circum = 2 * (22 / 7) * r; //formula for circumference of the circle

        cout << "\n The area of the circle is: " << area;
        cout << "\n The circumference of the circle is: " << circum;
        
        return 0;
    }
    
SLIDE 6, Rectangle Triangle Square

    #include <iostream>
    using namespace std;

    int main()
    {
      double width, length, area, S, A, B, C, side; //variables, double defines and holds any numerically valued data type especially any decimal oriented value

      //area of rectangle
      cout << "Find the Area of a Rectangle\n";
      cout << "Enter the Length of the rectangle: ";
      cin >> length;
      cout << "Enter the Width of the rectangle: ";
      cin >> width;
      area = (length * width); //formula for the area of rectangle
      cout << "The area of the rectangle is: " << area << endl;

      //area of triangle
      cout << "\nFind the Area of a Triangle\n";
      cout << "Enter three sides of the triangle:\n";
      cin >> A >> B >> C;
      S = (A + B + C) / 2; //formula for the area of triangle (Heron's Law)
      area = sqrt(S * (S - A) * (S - B) * (S - C)); //formula for the area of triangle (Heron's Law)
      cout << "The area of the triangle is: " << area << endl;

      //area of square
      cout << "\nFind the Area of a Square\n";
      cout << "Enter the side of the square: ";
      cin >> side;
      area = side * side; //formula for the area of square
      cout << "The area of the square is: " << area << endl;

      return 0;
    }

