#include <iostream>
#include <cmath>   // For math functions
using namespace std;

void program1();
void program2();
void program3();
void program4();
void program5();
void program6();
void program7();
void program8();
void program9();
void program10();
void program11();
void program12();
void program13();
void program14();
void program15();
void program16();
void program17();
void program18();
void program19();
void program20();
void program21();
void program22();
void program23();
void program24();
void program25();
void program26();
void program27();
void program28();
void program29();
void program30();

void showMenu() {
    cout << "\n========= 30 BASIC C++ PROGRAMS =========\n";
    cout << "1.  Assign and print three variable values.\n";
    cout << "2.  Print message: 'C++ is powerful.'\n";
    cout << "3.  Interchange values of two variables.\n";
    cout << "4.  Convert years to months.\n";
    cout << "5.  Sum and product of two numbers.\n";
    cout << "6.  Convert age in years to months.\n";
    cout << "7.  Calculate total and average of marks.\n";
    cout << "8.  Convert Fahrenheit to Celsius.\n";
    cout << "9.  Find maximum number from four.\n";
    cout << "10. Convert miles to kilometers.\n";
    cout << "11. Average of two integers.\n";
    cout << "12. Volume of a cylinder using const.\n";
    cout << "13. Area of circle using #define.\n";
    cout << "14. Convert millimeters to inches.\n";
    cout << "15. Interchange two variable values.\n";
    cout << "16. Product of three variables (3 each).\n";
    cout << "17. Separate integral and fractional parts.\n";
    cout << "18. Calculate s = vi*t + 0.5*a*t*t.\n";
    cout << "19. Age in months and days.\n";
    cout << "20. Print path using escape sequences.\n";
    cout << "21. Print pattern with \\n.\n";
    cout << "22. Input and print student info.\n";
    cout << "23. Circle area and circumference.\n";
    cout << "24. Total and average of 5 subjects.\n";
    cout << "25. Area of triangle (Heron’s formula).\n";
    cout << "26. Convert rupees to dollars.\n";
    cout << "27. Convert time to seconds.\n";
    cout << "28. Compute discriminant (b*b - 4ac).\n";
    cout << "29. Print message if n > 100.\n";
    cout << "30. Check odd or even number.\n";
    cout << "------------------------------------------\n";
    cout << "Enter program number (1-30) to view, or -1 to exit.\n";
    cout << "==========================================\n";
}

int main() {
    int choice;

    do {
        showMenu();

        cout << "\nEnter your choice: ";
        cin >> choice;
        cout << "\n";

        switch (choice) {
            case 1: program1(); break;
            case 2: program2(); break;
            case 3: program3(); break;
            case 4: program4(); break;
            case 5: program5(); break;
            case 6: program6(); break;
            case 7: program7(); break;
            case 8: program8(); break;
            case 9: program9(); break;
            case 10: program10(); break;
            case 11: program11(); break;
            case 12: program12(); break;
            case 13: program13(); break;
            case 14: program14(); break;
            case 15: program15(); break;
            case 16: program16(); break;
            case 17: program17(); break;
            case 18: program18(); break;
            case 19: program19(); break;
            case 20: program20(); break;
            case 21: program21(); break;
            case 22: program22(); break;
            case 23: program23(); break;
            case 24: program24(); break;
            case 25: program25(); break;
            case 26: program26(); break;
            case 27: program27(); break;
            case 28: program28(); break;
            case 29: program29(); break;
            case 30: program30(); break;

            case -1:
                cout << "Program terminated.\n";
                break;

            default:
                cout << "Invalid choice! Try again.\n";
        }

        cout << "\n------------------------------------------\n";

    } while (choice != -1);

    return 0;
}

// PROGRAMS BELOW

void program1() {
    int a=10, b=20, c=30;
    cout << "Value of a = " << a << "\nValue of b = " << b << "\nValue of c = " << c << endl;
}

void program2() {
    cout << "C++ language is a powerful programming language.\n";
}

void program3() {
    int a=5, b=10, temp;
    cout << "Before interchange:\na = " << a << ", b = " << b << endl;

    temp = a;
    a = b;
    b = temp;

    cout << "After interchange:\na = " << a << ", b = " << b << endl;
}

void program4() {
    int year = 2;
    cout << "Years in months are: " << year * 12 << endl;
}

void program5() {
    int a=6, b=4;
    cout << "Sum = " << a+b << "\nProduct = " << a*b << endl;
}

void program6() {
    int years = 20;
    cout << "Months in " << years << " years: " << years*12 << endl;
}

void program7() {
    int roll, m1, m2, m3;

    cout << "Enter Roll Number: ";
    cin >> roll;

    cout << "Enter PF marks: ";
    cin >> m1;

    cout << "Enter FE marks: ";
    cin >> m2;

    cout << "Enter ICP marks: ";
    cin >> m3;

    int total = m1 + m2 + m3;
    double avg = total / 3.0;

    cout << "Total = " << total << "\nAverage = " << avg << endl;
}

void program8() {
    double f;
    cout << "Enter temperature in Fahrenheit: ";
    cin >> f;

    double c = (5.0/9.0) * (f - 32);

    cout << "Temperature in Celsius: " << c << endl;
}

void program9() {
    int a,b,c,d,maxi;
    cout << "Enter four numbers: ";
    cin >> a >> b >> c >> d;

    maxi = a;
    if(b > maxi) maxi = b;
    if(c > maxi) maxi = c;
    if(d > maxi) maxi = d;

    cout << "Maximum number is: " << maxi << endl;
}

void program10() {
    double miles = 2.5;
    cout << miles << " miles in kilometers: " << miles * 1.609 << endl;
}

void program11() {
    int x=7, y=13;
    cout << "Average = " << (x+y)/2.0 << endl;
}

void program12() {
    const double pi=3.14159;
    cout << "Volume = " << pi * 2 * 2 * 5 << endl;
}

void program13() {
    #define PI 3.14159
    float r = 3.0;
    cout << "Area = " << PI * r * r << endl;
}

void program14() {
    double mm=50.8;
    cout << "Inches = " << mm / 25.4 << endl;
}

void program15() {
    int a=9, b=4, temp;
    cout << "Before: a=" << a << ", b=" << b << endl;

    temp = a;
    a = b;
    b = temp;

    cout << "After: a=" << a << ", b=" << b << endl;
}

void program16() {
    cout << "Product = " << 3*3*3 << endl;
}

void program17() {
    double x=15.58971;
    int i = (int)x;
    double fraction = x - i;

    cout << "Integral = " << i << "\nFractional = " << fraction << endl;
}

void program18() {
    float vi = 10.2, t = 2.8, a = 9.8;
    double distance = (vi*t) + 0.5*a*(t*t);
    cout << "Distance = " << distance << endl;
}

void program19() {
    int years = 21;
    cout << "Months = " << years*12 << "\nDays = " << years*365 << endl;
}

void program20() {
    cout << "C:\\Windows>\n'P'\t'A'\t'K'\n\"Pakistan\"\n";
}

void program21() {
    cout << "XXXXX\nXXXX\nXXX\nXX\nX\n";
}

void program22() {
    string name;
    int age;
    float height;
    char gender;

    cout << "Enter Name: ";
    cin >> name;

    cout << "Enter Age: ";
    cin >> age;

    cout << "Enter Height: ";
    cin >> height;

    cout << "Enter Gender (M/F): ";
    cin >> gender;

    cout << "Name: " << name << "\nAge: " << age << "\nHeight: " << height << endl;

    if(gender=='M' || gender=='F')
        cout << "Gender: " << gender << endl;
    else
        cout << "Invalid Gender\n";
}

void program23() {
    const double pi = 3.14159;
    float r;
    cout << "Enter radius: ";
    cin >> r;

    cout << "Area = " << pi * r * r 
         << "\nCircumference = " << 2 * pi * r << endl;
}

void program24() {
    int marks[5], total=0;
    float average;

    cout << "Enter 5 marks:\n";

    for(int i=0; i<5; i++) {
        cin >> marks[i];
        total += marks[i];
    }

    average = total / 5.0;

    cout << "Total = " << total << "\nAverage = " << average << endl;
}

void program25() {
    double a,b,c;
    cout << "Enter sides: ";
    cin >> a >> b >> c;

    double s = (a+b+c)/2.0;
    double area = sqrt(s*(s-a)*(s-b)*(s-c));

    cout << "Area = " << area << endl;
}

void program26() {
    double PKR = 12000;
    cout << "Dollars = " << PKR / 60.0 << endl;
}

void program27() {
    int h,m,s;
    cout << "Enter hours: ";
    cin >> h;
    cout << "Enter minutes: ";
    cin >> m;
    cout << "Enter seconds: ";
    cin >> s;

    int total = (h*3600) + (m*60) + s;

    cout << "Total Seconds = " << total << endl;
}

void program28() {
    int a,b,c;
    cout << "Enter a, b, c: ";
    cin >> a >> b >> c;

    cout << "Discriminant = " << (b*b) - 4*a*c << endl;
}

void program29() {
    int n;
    cout << "Enter number: ";
    cin >> n;

    if(n > 100)
        cout << "n is greater than 100.\n";
}

void program30() {
    int n;
    cout << "Enter number: ";
    cin >> n;

    cout << ((n % 2 == 0) ? "Even\n" : "Odd\n");
}
