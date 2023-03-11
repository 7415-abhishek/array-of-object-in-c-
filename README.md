# array-of-object-in-c-
//program to make a array of object
#include<iostream>
using namespace std;

class employee
{
    int id; 
    int salary;

    public:
    void setid()
    {
cout<<"enter the number of employee id";
cin>>id;


    }
    void getid()
    {
        salary=10000000;

        cout<<"the id of employee is::"<<id<<endl;
        cin>>id;


    }
};
int main()
{
  //  employee abhishek,sumit,vivek,sharma,rohit;
  //  employee i;
   // i.setid();
   /// i.getid();

   employee sh[4];
   for (int i = 0; i < 4; i++)
   {
    sh[i].setid();
   sh[i].getid();

   }
   

}
