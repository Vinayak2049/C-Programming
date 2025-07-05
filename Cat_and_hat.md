# Cat and Hat

## You are given a string str, you need to return True if  the words "cat" and "hat" appear same number of times in str, otherwise return False.
   Note: str contains only lowercase English alphabets.

### Code
#include<stdio.h>
#include<string.h>
int main(){
    char str[100];
    int cat = 0;
    int hat = 0;
    printf("Enter a string: ");
    scanf("%s",str);
    char *ptr = str;
    while((ptr=strstr(ptr,"cat"))!= NULL){
        cat++;
        ptr=ptr+1
    }
    ptr = str;
    while((ptr=strstr(ptr,"hat"))!= NULL){
        hat++;
        ptr=ptr+1
    }
    if(cat==hat)
    printf("True");
    else
    printf("False");
    return 0;
}
