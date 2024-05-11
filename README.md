# Basic_To_Advance_Programs
C++ Programs for Beginners 

// #1 Hello World Program
// This is a simple C++ program that
/*#include <iostream>
using namespace std;
 int main (){
    cout<<"Hare Krishna World !"<<endl;
    return 0;
}*/

// #2   Printing own Name Program
/*#include <iostream>
using namespace std;
main () {
string name ;
cout<<"Enter your Name : ";
cin>>name;
cout<< " Hare Krishna " << name <<  " How are you dear " <<name << " ? "<<endl ;
cout<<"Reply Dear "<<name <<" : "; cin>>name;
 cout << " I am also Fine and say Hare Krishna ";

return 0;
}*/
//#3  Get input  from user Program
/* #include <iostream>
using namespace std;
int main () {
 string n ;
 int a ;
 long d ;
   cout << " Enter Your prosanal Deatails : "<<endl;

   cout << " Name : ";
   cin >>n ;
   cout << " Age : ";
   cin >>a;
   cout << " Date of Birth : ";
   cin>>d;
   cout << "-----------Your Details--------------"<<endl;
   cout<< " Name : "<<n<<endl<<" Age : "<<a<<endl<<" Date of birth : "<<d;
  return 0;
}*/

 //#4 Arithmetic Operators  call Function Program
/*
#include <iostream>
using namespace std;

int addTwoNumber(int a, int b)
{
   return a+b  ;
}

int main (){
int a,b ;
a = 12 ; b= 16;
cout<<" Sum of : "<<addTwoNumber(a,b);

return 0;

}
*/

//#5 swaping  two Variable  values  program
/*
#include <iostream>
using namespace std;
int main() {
int a= 6 , b =9 ;
cout <<" before swapping a = " <<a<< " b = "<<b    <<endl;
// built-in sweap  function
swap(a,b);

cout <<" after swapping a =  " <<a<< " b = "<<b          <<endl;

return 0;
} */

//#5.1 swaping  two Variable  values  program
/*
#include <iostream>
using namespace std;
int main() {
int a= 6 , b =9 ;
cout <<" before swapping a = " <<a<< " b = "<<b    <<endl;
// sweap with 3 variable
int temp;
temp=a;
a=b;
b=temp;
cout <<" after swapping a =  " <<a<< " b = "<<b          <<endl;

return 0;
} */


//#5.2
// C++ program to swap two
// numbers without using 3rd
// variable
/*
 #include <bits/stdc++.h>
   using namespace std;

// Driver code
int main()
{
    int a = 2, b = 3;

    cout << "Before swapping a = " << a << " , b = " << b
         << endl;

    // applying algorithm
    b = a + b;
    a = b - a;
    b = b - a;

    cout << "After swapping a = " << a << " , b = " << b
         << endl;
    return 0;
}
*/


//6
// Find the size of variables int float double and char
/* #include <iostream>
using namespace std;
int main () {
    int intType ;
    float floatType ;
    double doubleType ;
    char charType ;
    cout<<"Size of int : "<< sizeof(intType)<<"\n";
    cout<<"Size of float : "<< sizeof(floatType)<<"\n";
    cout<<"Size of double : "<< sizeof (doubleType)<<"\n";
    cout << "size of char : "<<sizeof (charType) ;
return 0;


} */

//#7
/* Multply two floating point Number with creating a
user define function */
/*  #include <iostream>
using namespace std;
// creating a user define Function
float mul_float_num(float a, float b)
{return a*b ; }

int main () {
float a = 1.2, b = 3.0 , product;
//Calling the user difine function
product = mul_float_num(a,b);
// print output
cout<<product;
return 0;

}
*/
// #8
// Print ASCII Value of a Character
/*
#include <iostream>
using namespace std;
int main() {
char c = 'k' ;
// %d  display the integer value of character
// %c display the actual Character
cout<<("American Standard Code Information Interchange (ASCII) ")<<endl;
printf("The ASCII value of %c is %d ", c,c);
return 0;

}
*/

// #9
// program to convert fahrenheit to celsius
/*
# include <iostream>
using namespace std ;
// creating a user define Function
// Formula is : T(C) = (T(F)-32)* 5/9
float Conversion(float n)
{
    return (n-32.0)* 5.0 / 9.0 ;
}
// Driver Code
int main () {

 float n = 40 ;
 cout<< Conversion(n);
 return 0;

}
*/

// #10
// find the sample interest program
/*
#include <iostream>
using namespace std ;

int main () {
    float p=1, r=1,t=1 ;
    // culculate simple interest
    // formula : simple_interest = (p*t*r)/100

    float SI = (p*t*r)/100;
    // print the resultant value of SI ;
    cout << "sample Interest = "<<SI ;
    return 0;
}

*/

// #11
// C++ program to find compound interest
// for given values.
/*
#include <bits/stdc++.h>
using namespace std;
// Driver
int main()
{
  double principal = 10000, rate =250 , time = 2;
  // Calculate compound interest
  double A = principal * ((pow((1 + rate / 100), time)));
  double CI = A - principal;
  cout << "Compound interest is " << CI;
  return 0;

   // pow = 6.125

}

*/
//#12

// C++ program to find area
// and perimeter of rectangle
/*
#include <iostream>
using namespace std;
//Utility Function
  int areaRectangle(int a, int b) 
    {
     int area = a*b;
     return area;
    }  
                       
  int areaPermeter (int a, int b) 
  
    { 
       int perimeter = 2*(a+b) ;
       return perimeter ; 
    } 
   //Driver Code 
   int main () {
  int a = 5 , b = 6 ; 
  cout << "Aera : "<<areaRectangle(a,b)<<endl;
  cout<< "Perimeter : " <<areaPermeter(a, b);
  return 0;   } 
  
*/

 // Basic programing is done 👍


