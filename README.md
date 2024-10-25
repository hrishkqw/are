// armstrong number
#include <iostream>
#include<math.h>
using namespace std;

int main() {
int num;
cout<<"enter number " ;
cin>>num;
int originaln=num;
int sum=0;

while(num!=0){
int lastd = num%10;
sum+=pow(lastd,3);
  num=num/10;  
}
if(sum==originaln){
    cout<<"armstrong number";
    
}else
cout<<"not armstrong number";

return 0;
}
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

// armstrong number
#include <iostream>
#include<math.h>
using namespace std;

int main() {
int num;
cout<<"enter number " ;
cin>>num;
int originaln=num;
int sum=0;

while(num!=0){
int lastd = num%10;
sum+=pow(lastd,3);
  num=num/10;  
}
if(sum==originaln){
    cout<<"armstrong number";
    
}else
cout<<"not armstrong number";

return 0;
}



