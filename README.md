# basic-coding-demo
THIS my first Git Repository.
<br>
Author-Om Dwivedi
#include<iostream>
using namespace std;
int main(){
    int l;
    int k;
    int x=INT_MIN;
    int y=INT_MAX;
    int array[]={23,-54,-14,25};
    int size=sizeof(array)/sizeof(int);
    for(int i=0;i<size;i++){
      if(array[i]>x){
        x=array[i];
        k=i;}
        }
    for(int j=0;j<size;j++){
      if(array[j]<y){
        y=array[j];
        l=j;}
       }
    cout <<array[k]<< endl;
    cout <<array[l]<< endl;
    return 0;
}