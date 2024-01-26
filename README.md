//GCD-of-two-numbers//
//GCD of two number with c language//

#include<stdio.h>
void main(){
    int n1,n2;
    printf("enter numbers");
    scanf("%d%d",&n1,&n2);
    while(n1!=n2){
        if (n1>n2)
        n1=n1-n2;
        else
        n2=n2-n1;
    }
    printf("is :%d",n2);
}
