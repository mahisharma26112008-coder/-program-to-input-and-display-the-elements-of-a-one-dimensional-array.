# -program-to-input-and-display-the-elements-of-a-one-dimensional-array.

#include<iostream>
  using namespace std;
    int main(){
        int n;
        cout<<"enter the size of array : "<<"\n";
        cin>>n;
        
        int arr[n];
        for(int i=0; i<n;i++){
            cout<<"enter the elements of array  "<<i+1<<"\n";
            cin>>arr[i];
        }
        
        
        cout<<"elements are : "<<"\n";
         for(int i=0;i<n;i++){
             cout<<arr[i]<<" ";
         }
        return 0;
    }
