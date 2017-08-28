#include <iostream>
using namespace std;
template<class T>
T sum(T x,T y)
{
    T s;
    s=x+y;
    return(s);

}
int main()
{
    int i,j;
    float f,g;
    cout<<"enter the two int values";
    cin>>i>>j;
    cout<<sum(i,j);
    cout<<"enter the float values";
    cin>>f>>g;
    cout<<sum(f,g);
}
