# The-pointless-box
[ While loop program ]
#include<iostream>
using namespace std;
int main()
{
	string choice;
	cout << "Enter a number: " << endl;
	cin >> choice;
	while (true)
	{
		if (choice == "1")
		{
			cout << "You entered number 1 " << endl;
			break;
		}
		else if (choice == "2")
		{
			cout << "You entered number 2 " << endl;
			break;
		}
		else {
			cout << "Please enter either number 1 or number 2. " << endl;
			cin >> choice;
		}
		
	}
	cin.get();
	return 0;
}
