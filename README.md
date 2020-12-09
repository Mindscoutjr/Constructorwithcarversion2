#include <iostream>

using namespace std;
class Car 
{
    string m,b;
    public:
        Car(string,string);
        void display(void)
        {
           cout<<"Model ="<<"\n";
           cout<<"Brand ="<<"\n";
           
        }
        
};
Car :: Car (string x,string y)
{
   m=x;
   b=y; 
}
int main()
{
    Car string1("Ford");
    Car string2("x50");
    
    cout<<"\nModel = "<<"\n";
    string1.display();
    
    cout<<"\nBrand = "<<"\n";
    string2.display();
    return 0;
}
