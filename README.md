# Lecture-15

cbrt and sqrt

    #include <iostream>
    #include <math.h>
    using namespace std;
    int main() 
    {
      cout << "The cube of 8 is: " << pow(8, 3) << endl;
      cout << "The square-root of 8 is: " << sqrt(8) << endl;
      cout << "The square-root of 8 is: " << pow(8, 1 / 2) << endl;
      cout << "The cube-root of 8 is: " << cbrt(8) << endl;
      cout << "The cube-root of 8 is: " << pow(8, 1 / 3) << endl;
    }



user with input to know sqrt and cbrt

    #include <iostream>
    #include <math.h>
    using namespace std;
    int main() 
    {
      int input{};
      cout << "Input a number to know the square root and cube root: ";
      cin >> input;
      cout << "The square root of " << input << " is: " << sqrt(input) << endl;
      cout << "The cube root of " << input << " is: " << cbrt(input) << endl;
    }

Function

    #include <iostream>
    #include <math.h>
    using namespace std;
    void Welcome();
    int main() 
    {
        Welcome();
        cout << "End of program" << endl;
        return 0;
    }
    void Welcome() {
        cout << "Welcome to my program!" << endl;
    }
