# C++-code-for-shivling-

#include<iostream>
using namespace std;
int main() 
{int i,j; 
for(j=26;j>=-52;j--){ 
for(i=-39;i<=39;i++){ 
if((abs(i)<22&&(abs(j-4)<2||abs(j+2)<2||abs(j+8)<2)||(abs(i)==22&&(j==4||j==-2||j==-8)))||(!((676*i*i+1521*j*j<=822557)||(abs(i)<35&&j<0)))) 
cout<<" "; 
else 
cout<<"*";} 
cout<<std::endl;} 
return 0;}
