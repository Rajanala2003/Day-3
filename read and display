#include<iostream>
using namespace std;
class student
{
	char name[50];
	int rollno;
	int total;
	public:
		void readdetails(void);
		void gradecal(void);
		void printdetails(void);
;}
void student::readdetails(void)
{
	cout<<" enter the name :";
	cin>>name;
	cout<< " enter the roll number :";
	cin>> rollno;
	cout<< " enter the total marks :";
	cin>>total;
}
void student::gradecal
{
	float per;
	per=total/500*100;
	if(per>=75)
	  cout<<" A grade";
	else if(per>=60 && per<75)
	  cout<<"B grade ";
	else if(per>=50 && per<60)
	  cout<<" C grade";
	else
	   cout<< " D grade ";
}
void student::printdetails(void)
{
	cout<<" name"<<name;
	cout<<" roll number "<<rollno;
	cout<<" total marks"<<total;
}
int main()
{
	int i,n;
	student std[10];
	cout<<" enter total number of students :";
	cin>>n;
	for(i=0;i<n;i++)
	{
		cout<<" \n enter student details "<<i+1;
		std[i].readdetails();
	}
	for(i=0;i<n;i++)
	{
		cout<<" \n enter student details "<<i+1;
		std[i].printdetails();
		std[i].gradecal();
	}
	return 0;
}
