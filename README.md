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

	
	
	//circle
#include <iostream>
#include <string>
using namespace std;
int main()
{
	double r, a, c;
	cout << "Enter the radius to calculate the area and circumference of the circle \n";
	cin >> r;
	a = 3.14 * r * r;
	c = 2 * 3.14 * r;
	cout << "The area of the circle is: " << a << endl;
	cout << "The circumference of the circle is:" << c << endl;
	return 0;
}

	
	
	//Rectangle Triangle Square
#include <iostream>
#include <string>
using namespace std;
int main()
{
	double length, width, rect, tri, sq;
	cout << "\n Calculating the area of Rectangle, Triangle and Square shapes\n";
	cout << "Enter the length:\n";
	cin >> length;
	cout << "\nEnter the width : \n";
	cin >> width;
	rect = length * width;
	tri = (length * width) * 0.5;
	sq = length * length;
	cout << "\nThe area of rectangle : \n" << rect << endl;
	cout << "\nThe area of triangle: \n" << tri << endl;
	cout << "\nThe area of square: \n" << sq << endl;
	return 0;
}
