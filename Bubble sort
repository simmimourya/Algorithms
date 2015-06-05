#include <iostream>

using namespace std;

void main()
{
	int optimus[6];
	int i, j, m,a;

	cout << "enter 6 elements" << endl;
	
	for ( a = 0; a < 6;a++)
	{
		cin >> optimus[a];

	}

	for (j = 0; j < 6; j++)
	{
		for (i = 0; i < 5; i++)
		{
			if (optimus[i] > optimus[i + 1])
			{
				int temp = 0;
				temp = optimus[i];
				optimus[i] = optimus[i + 1];
				optimus[i + 1] = temp;

			}


		}
	}
	cout << "the array is ";
		for (int m = 0; m < 6; m++)
		{
			cout << optimus[m] << endl;
		}

}
