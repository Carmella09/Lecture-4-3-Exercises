# Lec-4-3-Codes

LECTURE 3 EXERCISE

Create a Program that prints following details to the console 
Name :
Age :
Current Address :  
Permanent Address:

    #include <iostream>  
    using namespace std;

    int main() 
    { 
      cout << "Name: Finn the Human " << endl; 
      cout << "Age: 12 years old " << endl;
      cout << "Current Address: Land of Ooo" << endl;
      cout << "Permanent Address: Land of Ooo " << endl;

      return 0; 
    }

LECTURE 4 EXERCISES
  
  Possible Data Types!
  
    #include <iostream>  
    #include <string>
    using namespace std;

    int main() 
    {
      int firstNumber = 1;  
      bool iCanCode = true;  
      char hopefulGrade = 'a';  
      double myDecimal = 1.0;  
      string minimalSentance = "y";  
      int keyMash = 13213123;
      float mysteryDataType = 5.6f; 

      cin.get();  
      return 0;
    }

  Division Fix!
  
      #include <iostream> 
    using namespace std;
    int main()
    {
      double numberOne = 50;
      double numberTwo = 7;
      cout << numberOne / numberTwo << endl;

      cin.get(); 

        return 0;
    }
  
  Untidy Code
  
    #include <iostream> 
    #include <string> 
    using namespace std;

    int main() 
    {
      cout << "This is untidy code." << endl;
      cout << "I'm surprised it works." << endl;

      int number = 6;

      cout << "It has " << number << " lines of code - " << endl;
      cout << "each more hideous than the last. " << endl;
      cout << "You probably should add some line breaks in the text too" << endl;

        cin.get(); 
        return 0;
    }
  
  USB Shopper 
  
      #include <iostream>
    using namespace std;
    int main()
    {
        int numberOne = 50;
        int numberTwo = 6;
        cout << "You can buy " << numberOne / numberTwo << " USB" << endl;

        int numberThree = 50;
        int numberFour = 48;
        cout << numberThree - numberFour << " AED is your change" << endl;

        cin.get(); 
        return 0;
    }
    
    
  Declaration and Initialisation
  
      #include <iostream>
    using namespace std;
    int main()
    {
        int numberEight = 8;
        int numberTen = 10;

        cout << numberEight + numberTen << endl;

        cin.get(); 
        return 0;
    }
