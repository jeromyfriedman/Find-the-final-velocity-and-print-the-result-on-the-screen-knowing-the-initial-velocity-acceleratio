# Find-the-final-velocity-and-print-the-result-on-the-screen-knowing-the-initial-velocity-acceleratio
Find the final velocity and print the result on the screen knowing the initial velocity, acceleration and time
#include <iostream>
#include <conio.h>
using namespace std;
int main()
{

int v,u,a,t;
cout << "Tap toc v0, gain a, time t: " << endl;
cin>>u>>a>>t;
v=u+a*t;
cout << "The final valve is " << v << "." << endl;
return 0;
}
