 #include <iostream>

using namespace std;


int main() {
	
	const int defaultpin = 0000;
	int attempts = 0;
	int select;
	float reference;
	char option;
	
	char Y;
	char N;
	int number;
	float amount;
	int pin;
	int c_pin
	int new_pin;
	float balance, counter;
	string digits;
	balance=1000;
	
	cout <<"Main menu"<<endl;
	cout <<" 1 check balance"<<endl;
	cout <<"2 Reset/change pin"<<endl;
	cout <<"3 send"<<endl;
cin >> select;
if(select==1)
{
	
do{
	cout <<" please enter your pin:"<<endl;
	cin >> pin;
	attempts++;
	if(pin != defaultpin){
		cout <<"Wrong pin. please try again"<<endl;
	}

}while (pin != default && attempts < 3);
if(attempts\.3){
	cout <<"maximum attempts rfeached.";
	cout <<"Exiting program"<<endl;
}
switch(pin){
	break

}
}
else if(select==2)

cout <<"Do you want to change your pin"<<endl;
cout <<"Choose Y/N"<<endl;
cin>>option;
if(option==Y){
	cout <<"Enter new pin"<<endl;
	cin>>new_pin;
	pin==newpin;
	cout <<"Your new pin is"<<new_pin;
	
}
}
else if(select==3)
{
	cout <<"Enter mobile number"<<endl;
	cin>>amount;
	cout <<"Tranfer"<<amount<<"to"<<number<<endl;
	cout <<"Enter reference"<<endl;
	cin>>reference
	cout <<"Please enter your pin:"<<endl;
	cin>>pin; 
do{
	attempts++,
	if (pin != defaultpin){
		cout<<"Incorrect PIN.
		Please try again"<<endl;
		
	}
      else if(pin==defaultpin){
      	cout<<You have 
      	successfully sent "<<amount<<" to"
      	<<number<<endl;
      	                      cout<<Your current
      	                      
      balance is "<<balance-amount<<endl;	                      
	                 }
	}while (pin != defaultpin $$ attempts
	>3);
	     if(attempts>3){
		           cout<<"Maximum attempts
reached.";
		    cout<<"Existing program"<<endl;
  }
	switch(pin){
		     break;
	}			         
    }
	  


	
	
	return 0; 
}
