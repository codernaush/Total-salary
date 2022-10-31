//# Total-salary
///hra   = 20% of basic da    = 50% of basic allow = 1700 if grade = ‘A’ allow = 1500 if grade = ‘B’ allow = 1300 if grade = ‘C' or any other character pf    = 11% of //basic.
#include<math.h>
#include<iostream>
using namespace std;

int main() {
	// Write your code here
	
int basic,allow;

    char grade;

    cin>>basic;

    cin>>grade;

    double hra,da,pf;

    hra=.2*basic;

    da=.5*basic;

    pf=.11*basic;

    if(grade=='A'){

        allow=1700;

    }else if(grade=='B'){

        allow=1500;

    }else allow=1300;

            int total=round((basic+hra+da+allow)-pf);

            cout<<total<<endl;

    return 0;

}
	

	

	

	

	

	

	

	

	

	

	

	

	

	

	

	

