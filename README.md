# pointers-using-to-add-numer-and-find-the-address-of-varaibles-in-memory
#include <iostream>
using namespace std;

int main() {
    int a=7;
    int b=8;
    int *c=&a;
    int *d=&b;
    int sum=*c+*d;
    cout<<"the sum of pointers="<<sum<<endl;
    cout<<"the address of a="<<&a<<endl;
    cout<<"the value at a="<<*c<<endl;
    cout<<"the address of b="<<&b<<endl;
    cout<<"the value of b ="<<*d<<endl;

    return 0;
}
