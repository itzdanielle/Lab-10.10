# Lab-10.10
#include <iostream>
using namespace std;

int main() {

	char grade;

	cout << "What grade did you earn in Programming I ?" << endl;
	cin >> grade;

	switch( grade )  // This is where the switch statement begins
  {
  	case 'A':  cout << "an A - excellent work !" << endl;
  		       
  	case 'B':  cout << "you got a B - good job" << endl;
  		       
  	case 'C':  cout << "earning a C is satisfactory" << endl;
  		       
  	case 'D':  cout << "while  D is passing, there is a problem" << endl;
  	   	       
    case 'F':  cout << "you failed - better luck next time" << endl;
  		       
    default:   cout << "You did not enter an A, B, C, D, or F" << endl;
	}
 // When you remove the break from each statement, no matter what you enter it will fall to the next statement and in this case since we removed all the breaks, they are all together 


}
