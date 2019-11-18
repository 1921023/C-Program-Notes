# _PPS Assignment_

## [](https://github.com/Krishan00007/C-program-notes/blob/master/c%20program.c.md#submitted-by-)_**Submitted By :**_

##### [](https://github.com/Krishan00007/C-program-notes/blob/master/c%20program.c.md#name--krishan)_**Name : Deepak Kumar**_

##### [](https://github.com/Krishan00007/C-program-notes/blob/master/c%20program.c.md#roll-no--1921057)_**Roll No. : 1921023**_

##### [](https://github.com/Krishan00007/C-program-notes/blob/master/c%20program.c.md#branch--information-tecnologyit)_**Branch : Information Tecnology(I.T)**_

##### [](https://github.com/Krishan00007/C-program-notes/blob/master/c%20program.c.md#section---it-a2)_**Section : I.T. A1**_

# [](https://github.com/Krishan00007/C-program-notes/blob/master/c%20program.c.md#my-c-programes-assignment)**My C programes assignment**

## 1:To print hello world
```
//To print  hello world
#include<stdio.h>
int main()
{                     
 printf("\nHello world\n");
}
```

OUTPUT:
```

 Hello world
 ```

## 2:To fill your information
```

  // To fill your information
#include<stdio.h>

  void info();
  int main()
  {
     info();
  }

   void info()
  {  char a[20];
     int roll,age;
     long int ph;
   printf("\nEnter your information:\n");
   printf("Name = ");
    scanf("%s",a);
  printf("\nRoll no=");
scanf("%d",&roll);
printf("\nAge = ");
 scanf("%d",&age);
 printf("\nPhone no.= ");
 scanf("%ld",&ph);

printf("\nThe name is %s\nYour roll no is %d\nMy phone number is %ld\n My age is %d\n",a,roll,ph,age);

}
```
**OUTPUT:**
```
Enter your information:
Name = Devil

Roll no=1921023

Age = 18

Phone no.= 8847547031

The name is Devil
Your roll no is 1921023
My phone number is 8847547031
 My age is 18
 ```
 
## 3:Sum and average of numbers
```
 // sum and average of number
#include<stdio.h>
  int main()
 {                                 
     int a,b,c,d,e,sum,avg;
                                                               
   printf("Enter five numbers:");
   scanf("%d %d %d %d %d",&a,&b,&c,&d,&e);
    sum = a+b+c+d+e;
   printf("The sum is:%d\n",sum);
   avg = sum/5;
   printf("The average is:%d\n",avg);
  }
```
**OUTPUT**:
```
Enter five numbers:1 2 3 4 5 
The sum is:15
The average is:3
```
## 4:To find sum of two numbers
```
     // to find sum of two numbers
     #include<stdio.h>
int main()
{                                                                                      
 int a;
 int b;
 int c ;
 printf("Enter two numbers to get sum:");
 scanf("%d  %d",&a,&b);
 printf(" \nThe result is :%d + %d= %d\n",a,b,c=a+b);
    return 0;
 }
```
**OUTPUT**:
```
Enter two numbers to get sum:50 50
 
The result is :50 + 50= 100
```

## 5:To show area,perimeter,volume of square

   ```
 //Area,premiter,volume of square
  #include<stdio.h>
void square();
int main()
{     
 square();
 return 0;
}                                    
void square()
{
 int side;
 printf("Enter the side of square:");
 scanf("%d",&side);

 printf("\nPerimeter of square:%d",4*side);
 printf("\nArea of square:%d",side*side);
 printf("\nVolume of square:%d\n",side*side*side);
}
```
**OUTPUT**:
```
Enter the side of square:4

Perimeter of square:16
Area of square:16
Volume of square:64
```

## 6:To find number is even or odd
```
     #include<stdio.h>
int main()
{                                
  int a;   
 printf("Enter a number:");
 scanf("%d",&a);
if(a%2==0)
printf("The  number is even\n");
else
 printf("The number is odd\n");
}
```
**OUTPUT**:
```
Enter a number:4
The  number is even
```
_**OR**_
```
Enter a number:7
The number is odd
```
## 7:To show the size of int,float,char,double,long,short
```
 // size of int, float, char, double, long, short
#include<stdio.h>
int main()
{                                   
 printf("Integer:%d\n",sizeof(int));
 printf("float:%d\n",sizeof(float));
 printf("character:%d\n",sizeof(char));
 printf("double:%d\n",sizeof(double));
 printf("short:%d\n",sizeof(short));
 printf("long:%d\n",sizeof(long));
 }
```
**OUTPUT**:
```
Integer:4
float:4
character:1
double:8
short:2
long:8
```
## 8:To show area,diameter,circumference of circle
```
   #include<stdio.h>
 int main()
  {
    float a;   
float  const pi=3.14;
   printf("Enter radius of circle:");
    scanf("%f\n",&a);
  printf("diameter of circle is:%f\n",2*a);
  printf("circumference of circle:%f\n",2*pi*a);
  printf("Area of circle:%f\n",pi*a*a);
return 0;
 } 
```
**OUTPUT**:
```
Enter radius of circle:6
diameter of circle is:12.000000
circumference of circle:37.680000
Area of circle:113.040001
```
## 9:To show puts value upto n number using loop
```
// to show punishment using loop
 #include<stdio.h>
 int main()
 {
 int i,a;
 printf("Enter the number upto punishment is shown:");
 scanf("%d",&a);
  for(i=1;i<=a;i++)
puts("WORK HARD AND ACHIEVE SUCCESS ");
return 0;
}
```
**OUTPUT**:
```
Enter the number upto punishment is shown:10
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxMzczMTI5MDEsMTc4NzE2NDkyOSwxOT
I2MTAxMTY4LDk4NTMxNjQ5MywxMjQ3NzI3MzYxLC0xMjgzOTkz
MzcsMTA3NTkzNTU1Nl19
-->