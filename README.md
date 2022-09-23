# Fibonocci-series-till-N
#include <iostream>
using namespace std;
int main (){
    int n,c;
    cout<<"Enter the number ";
    cin>>n;
    int a=0,b=1;
    while(a<n){
        cout<<a;
        c=a+b;
        a=b;
        b=c;
    }
    return 0;
}
