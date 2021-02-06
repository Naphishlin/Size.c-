#include<iostream>
using namespace std;
int main()
{
	cout<<"size of char:"<< sizeof(char)<<"byte"<<endl;
	cout<<"size of int:"<< sizeof(int)<<"bytes"<<endl;
	cout<<"size of float:"<< sizeof(float)<<"bytes"<<endl;
	cout<<"size of double:"<< sizeof(double)<<"bytes"<<endl;
	return 0;
}
	
#include<iostream>
using namespace std;
int main()
{
  double firstNumber,secondNumber,productOfTwoNumbers;
	cout<<"Enter two numbers";
	//stores two floating point numbers in variable firstNumber and secondNumber respectively
	cin>>firstNumber>>secondNumber;
	//performs multiplication and stores the result in variable productOfTwoNumbers
	productOfTwoNumbers=firstNumber*secondNumber;
	cout<<"product="<< productOfTwoNumbers;
	return 0;
}
