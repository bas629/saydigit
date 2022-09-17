# saydigit
#include<iostream>
using namespace std;
void  saydigit(int n)
{ if(n==0)
{
    return ;
}
int r;
r=n%10;
n=n/10;

 saydigit(n);
cout<<r;

}

int main()
{ int n;
cin>>n;
saydigit(n);






}





