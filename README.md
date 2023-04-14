[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/MhO6lfiK)
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
