#DataTypes

```
#include<stdio.h>
#include<string.h>
int main(){
    int a;
    float b;
    char c[20];
    double d;
    
    scanf("%d %f %[^\n] %lf",&a,&b,c,&d);
    printf("%d\n",a);
    printf("%.2f\n",b);
    printf("%s\n",c);
    printf("%.3lf",d);
}
```
#define & const assign
```
#include<stdio.h>
#define hundo 100
int main(){
    const int a = 50;
    
    printf("%d\n",a);
    printf("%d",hundo);
}
```
#with and without temp variable swap numbers
```
#include<stdio.h>
int main(){
   int a=2;
   int b=3;
   int c;
    c=a;
    a=b;
    b=c;
    printf("with third variable\n");
     printf("%d\n%d\n",a,b);
     
    a=a+b;
    b=a-b;
    a=a-b;
    printf("without third variable\n");
    printf("%d\n%d",a,b);
}
```
# implicit and explicit and finding avr with and without casting
```
#include <stdio.h>
int main() {
    int a = 10;  
    float b = a;
    printf("implicit:-\n");
    printf("%d\n%.2f\n\n",a,b); //implicit
    
    float c=5.32;
    int z = (int)c;
    printf("explicit:-\n");
    printf("%.2f\n%d\n",c,z);//explicit
    
    int f = 5;
    int m = 5;
    float avg1 = (a+b)/2;
    float avg2 = (float)(a+b)/2;
    printf("\navg with and without casting\n");
    printf("%.2f\n%.2f",avg1,avg2);
}

```
