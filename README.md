# averageOf5Numbers
#include<iostream>
using namespace std;

int main()
{
  int sum,num1,num2,num3,num4,num5;
  double answer;
  cout << "Enter 5 numbers with spaces in-between them: " << endl;
  cin >> num1 >> num2 >> num3 >> num4 >> num5 >>endl;
  sum = num1+num2+num3+num4+num5;
  answer = sum / 5.0 ;
  cout << "The answer is: << answer <<endl;
  system("pause");
}
