# Even and Odd

## Given a positive integer x. Your task is to check, if it is even or odd

### Code
#include<stdio.h>

int Even_Odd(int x){
    if (x%2==0){
        printf("Even");
    }
    else{
        printf("odd");
    }
}

int main(){
    int x;
    printf("Enter a number: ");
    scanf("%d",&x);
    Even_Odd(x);
}
