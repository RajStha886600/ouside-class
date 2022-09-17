# ouside-class
#include <iostream>
using namespace std;
class Add
{
    private :
    int a, b, sum;
    public:
    void getdata();
    void calculate();
    void display();
};
void Add:: getdata()
{
    cout<<"enter tha value of a and b";
    cin>>a>>b;
    
}
void Add:: calculate ()
{
    sum= a+b;
}
void Add:: display ()
{
    cout<<"sum is : "<<sum;
}
int main()
{
    Add A;
    A.getdata();
    A.calculate();
        A.display();
return 0;
}
