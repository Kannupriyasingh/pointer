# pointer
#include <iostream>

using namespace std;

class x
{
public:
    int m1,m2;
    void f(int k1 ,int k2)
    {
        m1=k1;
        this ->m2=k2;
        cout <<"Id ="<<this <<endl;
    }
};

int main()
{
    x a;
    a.f(2,3);
    cout<<"addr ="<< &a<< endl;
    cout<<"a.m1="<<a.m1<<"  "<<"a.m2="<<a.m2<<endl;
    return 0;
}

