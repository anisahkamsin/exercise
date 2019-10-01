# exercise
//

#include "stdafx.h"
#include <iostream>
using namespace std;
float price = 9.90;
int quantity = 0;
const int DISC = 10;
float totalprice = 0;

void star()
{
	cout << "This is Lab4" << endl;
	cout << "Anisah Binti Kamsin, Do Exersice" << endl;

}

int calc()
{
	cout << "enter quantity";
	cin >> quantity;
	totalprice = (price*quantity) * (100 - DISC) / 100.00;

	return 0;
}
int main()
{

	star();
	calc();
	cout << "total price =" << totalprice << "\n";


    return 0;
}

