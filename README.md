include <stdio.h>

int main()
{
int l,b,a,p;
printf("enter the value");
scanf("%d%d",&l,&b);
a=l*b;
p= 2*(l+b);

if(a<p){
    printf("greater");}
    else{
        printf("less");}
    return 0;
}
