#include <iostream>

using namespace std;

int main()
{
    int x,i,count=0;
    cout<< " Masukkan sebuah angka  :";
    cin>>x;
    for (i=2;i<=x/2;i++)
    {
        if (x%i==0)
            count++;
    }
    if (count>0||x<2)
        cout<<x<< "bukan bilangan pima\n";
    else
        cout<<x<< "\n bilangan prima\n";
}
