#include<iostream>
#include<cmath>
using namespace std;
int main()
{
	int x;
	cout << "please enter the year" << endl;
	cin >> x;
	if (x % 4 == 0 && x % 100 != 0 || x % 400 == 0)
	{
		cout << x << "is a leap year" << endl;
	}
	else
	{
		cout << "<<x<<is not a leap year" << endl;
	}
}
