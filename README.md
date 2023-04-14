
#include <iostream>
using namespace std;


int main() {
    float a=0;
    float b=0;
    float x=0;
    float y=0;
    float z=0;
    cin >> a >> b >> x >> y;
    if(x<0 and y>0){
       z =((a*x)-(b*y));
    } else if (x>=0 and y<=0){
        z =((a*x*x)-(b*y));
    }else {
       z =((a*x)+(b*y*y));
    }
    cout<<z;




    return 0;
}
