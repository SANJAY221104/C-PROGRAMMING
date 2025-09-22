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
