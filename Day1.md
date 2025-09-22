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
