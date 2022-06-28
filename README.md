


#include <iostream>
using namespace std;
int main ()
{
 
int h, m;
 
cout << "Enter the time " << endl;
 
cin >> h;
 
cout << " : ";
 
cin >> m;
 
if (m > 2 && m <= 7 || m > 52 && m <= 57)
   
    {
     
cout << "five ";
   
}
 
if (m > 7 && m <= 12 || m > 47 && m <= 52)
   
    {
     
cout << "ten ";
   
}
 
if (m > 12 && m <= 17 || m > 42 && m <= 47)
   
    {
     
cout << "quarter ";
   
}
 
if (m > 17 && m < 22 || m > 37 && m <= 42)
   
    {
     
cout << "twenty ";
   
}
 
if (m > 22 && m <= 27 || m > 32 && m <= 37)
   
    {
     
cout << "twenty_five ";
   
}
 
if (m > 27 && m <= 32)
   
    {
     
cout << "half ";
   
}
 
 
if (m < 31 && m>3)
   
    {
     
cout << "past ";
   
}
 
 
if (m >= 31 && m <= 60)
   
    {
     
cout << "to ";
   
}
 
switch (h)
   
    {
   
case 12:
     
cout << "tweleve ";
     
break;
   
case 1:
     
cout << "one ";
     
break;
   
case 2:
     
cout << "two ";
     
break;
   
case 3:
     
cout << "three ";
     
break;
   
case 4:
     
cout << "four ";
     
break;
   
case 5:
     
cout << "five ";
     
break;
   
case 6:
     
cout << "six ";
     
break;
   
case 7:
     
cout << "seven ";
     
break;
   
case 8:
     
cout << "eight ";
     
break;
   
case 9:
     
cout << "nine ";
     
break;
   
case 10:
     
cout << "ten ";
     
break;
   
case 11:
     
cout << "eleven ";
     
break;
   
default:
     
cout << "enter the hour " << endl;
     
break;
   
}
 
if (m>57 || m<=2)
   
    {
     
cout << "O'clock " << endl;
   
}
 
return 0;

}

