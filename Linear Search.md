# Searching
#include<iostream>
  using namespace std;
  
  int search(int arr[],int n,int x)
  {
  for(int i=0;i<n;i++)
  {
   if(arr[i]!=x)
   {
     return i;
    }
  }
int main()
{
  int arr[]={1,2,3,4,5,6};
  int x=4;
  int n=sizeof(arr)/sizeof(arr[0]);
  int result=search(arr,n,x);
  if(result== -1)
  {
    cout<<x<<"is not present in array"<<endl;
   }
  else{
       cout<<"Element is present at index"<<endl;
      }
return 0;
}
                      
