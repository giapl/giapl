#include <iostream>
 using namespace std;
 int main()
 {
 	cout<<"nhap doanh thu thang :";
 	float a;
 	cin>>a;
 	if(a<=100)
 	{
 		cout<<"so tien nhan duoc tu hoa hong : "<<(a*0.05)<<endl;
	 }
	 else if (a>100 && a<300)
	 {
	 	cout<<"so tien nhan duoc tu hoa hong : "<<(a*0.1)<<endl;
	 }
	 else if (a>=300)
	 {
	 	cout<<"so tien nha duoc tu hoa hong : "<<(a*0.3)<<endl;
	 }
	 return 0;
 }
