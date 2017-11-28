// ConsoleApplication8.cpp: ���������� ����� ����� ��� ����������� ����������.
//

#include "stdafx.h"
#include <windows.h>
#include <iostream>
#include <math.h>
using namespace std;
int main()
{
	int a, b;
	double x, y, h;
	cout <<( "Enter a =" );
	cin >> a;
	cout << (" Enter b = ");
	cin >> b; 
	cout<<(" Enter h = ");
	cin >> h;
	x = a;
	while (x <= b)
	{
		y = pow(x, 5) + 2 * (x*x) - 3;
		x += h;
		cout << " x =" << x; cout << "   y = " << y << endl;
	}
	system(" pause");
	return 0;
}
