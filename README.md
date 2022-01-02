# Lecture-5
//-Biography
#include <iostream> 
using namespace std;
int main()
{
	string name;
	int age;
	string hometown;

	cout << "enter your name :" << endl;
	cin >> name;
	cout << "enter your age:" << endl;
	cin >> age;
	cout << "enter your hometown :" << endl;
	cin >> hometown;
	return 0;

}
  

	
//Temperature F To C
#include <iostream>
using namespace std;
int main()
{
	double f;
	double c;
	cout << "enter the temperature in farenhite :" << endl;
	cin >> f;
	c = (f - 32) * 0.556;
	cout << "the temperature in Celsius is :" << c << endl;
	return 0;


}




//Temperature C To F
#include <iostream>
using namespace std;
int main()
{
	double f;
	double c;
	cout << "enter the temperature in Celsius :" << endl;
	cin >> c;
	f = (c * 1.8) + 32;
	cout << "the temperature in Farenhite is :" << f << endl;
	return 0;


}
