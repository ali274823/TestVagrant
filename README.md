#include <iostream>

using namespace std;

int main()
{
    int leather=1100,umbrella=900,cigarette=200,honey=100;
    int x;
    int sum=0;
    int total;
    cout<<"Press the item you want to buy 1. leather wallet 2. umbrella 3. cigarette 4. honey";
    cin>>x;
    if(x=1)
    {
       sum= leather*(18/100);
       total=sum+leather;
    }
   else if(x=2)
    {
        sum=2*umbrella*(12/100);
        total=sum+umbrella;
    }
      else  if(x=3)
    {
        sum=3*cigarette*(28/100);
        total=sum+cigarette;
    }
       else if(x=4)
    {
        sum=4*honey;
        total=sum;
    }
    cout<<total;

    return 0;
}
