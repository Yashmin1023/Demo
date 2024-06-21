# Demo
#include<stdio.h>
typedef int* pointer;

int main(){
    int a =5,b = 7;
    //int* x,y; //int* x & int y without typedef
    pointer x = &a, y = &b; //int* x & int* y
    printf("%p\n",x);
    printf("%p\n",y);

    return 0;
}
