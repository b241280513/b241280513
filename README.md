#iclude<stdio.h>
int main(void){
int a,b,c,sum=0;
puts("二つの整数を入力せよ:");
printf("整数A:"); scanf("%d",&a);
printf("整数B:"); scanf("%d",&b);
if(b<a){
c=a;
a=b;
b=c;
}
c=a;
do{
sum=sum+a;
a++;
}while(a<=b);
printf("%d以上%d以下の全整数の和は%dです¥n",c,b,sum);
return 0;
}




