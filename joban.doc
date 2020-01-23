//reverse of linear array in data structures
#include<iostream>
using namespace std;
int main()
{
    int arr[20],i,n,temp;
    cout<<"Enter size of array:"<<endl;
    cin>>n;
    cout<<"Enter array elements:"<<endl;
    for(i=1;i<=n;i++)
        cin>>arr[i];
    cout<<"Array elements are:"<<endl;
    for(i=1;i<=n;i++)
        cout<<arr[i]<<" ";
    int j=n;
    for(i=1;i<=(j/2);i++)
    {
        temp=arr[j];
        arr[j]=arr[i];
        arr[i]=temp;
        j--;
    }
    cout<<endl<<"Reverse\n";
    for(i=1;i<=n;i++)
    {
        cout<<arr[i];
    }
}
