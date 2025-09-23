
#for loop
```
#include<stdio.h>
int main()
{
    int a=10;
    for(int i=1;i<=a;i++){
        printf("%d\n",i);
    }
}
```
#while loop
```
#include<stdio.h>
int main()
{
    int a=1;
    while(a<=10){
        printf("%d\n",a);
        a++;
    }
}
```
#Do-while loop
```
#include<stdio.h>
int main()
{
    int a=1;
    do{
        printf("%d\n",a);
        a++;
    }
    while(a=10);

}
```
#print 1-100 even Numbers
```
#include<stdio.h>
int main()
{
    int a=1;
    while(a<=100){
        if(a%2==0){
            printf("%d ",a);
        }
        a++;
    }

}
```

Multiplication Table Using Loops
```
#include<stdio.h>
int main()
{
    int a=1;
    for(int i = 1;i<=10;i++){
        for(int j=1;j<=10;j++){
           printf("%d x %d = %d\n",i,j,i*j); 
           

        }
                       printf("\n");


    }
}
```
