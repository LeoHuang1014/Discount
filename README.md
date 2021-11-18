# Discount
Discount 20% if guests are over 20 people. 


#include <iostream>
  
 using namespace std;
  
 int main()
 
 {
 	int people, money;
  
 	cout<<"please input how many people:\n";
 	cin>>people;
 	money=people*399;
 	if(people>20)
 	  money=money*8/10;
  
 	cout<<"Total amount:\n"<<money<<endl;
 	
 	return 0;
 }
