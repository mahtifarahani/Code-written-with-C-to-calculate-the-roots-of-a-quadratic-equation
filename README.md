# Code-written-with-C-to-calculate-the-roots-of-a-quadratic-equation
حسابگر ریشه های معادله درجه دوم\نوشته شده به عنوان پروژه دانشگاهی با زبان سی پلاس پلاس
#include <iostream>
#include <conio.h>
#include <math.h>
#include <stdlib.h>
using namespace std;
int main()
{ system("cls");

            int a,b,c;

            int d;

            double r1,r2;

            cout << " please enter a :" ;

            cin >> a ;

            cout << " please enter b :" ;

            cin >> b ;

            cout << " please enter c :" ;

            cin >> c ;

            d= (b*b) - (4*a*c);

            if (d>0){

                        r1=((-b)-sqrt(d))/(2*a);

                        r2= ((-b)+sqrt(d))/(2*a);

                        cout << "r1 : " << r1 <<'\t'<< "r2 : " << r2;

            }

            else if (d==0){

                        r1 = (-b)/(2*a);

                        cout << " r1,r2 : " << r1;

            }

            else if (d<0)

                        cout << " rishe nadarim " ;


   getch() ; return 0 ; }
