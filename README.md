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
Name = Jony

Roll no=100012

Age = 25

Phone no.= 9922115566

The name is Jony
Your roll no is 100012
My phone number is 9922115566
 My age is 25
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzNDc0NzM2MSwxOTI2MTAxMTY4LDk4NT
MxNjQ5MywxMjQ3NzI3MzYxLC0xMjgzOTkzMzcsMTA3NTkzNTU1
Nl19
-->