//# calculate-the-diffirent-variables
//it is the code about to calculte the value of foure variables and display on consoule

#include<iostream>
using namespace std;
int main()
{
	int a=1,b=5,c=6,d=7;
	
	c*=--c+--b%++a*b--/++a;
	cout<<"a="<<a<<",b="<<b<<",c="<<c<<",d="<<d<<endl;
	return 0;
	
}
