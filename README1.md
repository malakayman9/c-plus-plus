#include<iostream>
using namespace std;
void main() {
 

	int x;
	int i;

	for (x=0 ;x<=5;x++)
	{
		for(i=5 ;i>x;i--)
		cout << "*";
		cout << endl;
	}
}
