# Avninder-1915305
![](Gndec.jpg)

# My Details
### Name :- Avninder Preet Singh
### Branch :- CSE C1
### Roll number :- 1915305
## My Codes
## 1. To Print your name using puts

```C
#include<stdio.h>
int main(){
    puts("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n");
    puts("My Name is Avninder Preet Singh\n");
    puts("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\n");
    return 0;
}
```
![](/images/1.jpg)
---
## 2. To print college address

```C
#include<stdio.h>
int main(){
    printf("Guru Nanak Dev Engineering College,\n");
    printf("Gill Road,\n");
    printf("Ludhiana, Punjab\n");
    return 0;
}
```
![](/images/2.jpg)
---
## 3. Addition of two numbers input by user

```C
#include<stdio.h>
int main(){
    int n1,n2,sum;
    printf("Enter 1st number :- ");
    scanf("%d",&n1);
    printf("Enter 2nd number :- ");
    scanf("%d",&n2);
    sum=n1+n2;
    printf("Their Sum is %d\n",sum);
    return 0;
}
```
![](/images/3.jpg)
---
## 4. Program to compute quotient and remainder

```C
#include<stdio.h>
int main(){
    int d1,d2,q1,r1;
    printf("enter dividend :- ");
    scanf("%d",&d1);
    printf("enter divisor :- ");
    scanf("%d",&d2);
    r1=d1%d2;
    q1=d1/d2;
    printf("Quotient is %d\n",q1);
    printf("Remainder is %d",r1);
    return 0;
}
```
![](/images/4.jpg)
---
## 5. Program to swap two numbers without third variable

```C
#include<stdio.h>
int main(){
    int a,b;
    printf("Enter 1st number ('a') :- ");
    scanf("%d",&a);
    printf("Enter 2nd number ('b') :- ");
    scanf("%d",&b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("a = %d,b = %d",a,b);
    return 0;
}
```
![](/images/5.jpg)
---
## 6. Program to check number is even or odd

```C
#include<stdio.h>
int main(){
    int n1;
    printf("Enter number :- ");
    scanf("%d",&n1);
    if(n1%2==0){
        printf("Number is even");
    }
    else{
        printf("Number is odd");
    }
    return 0;
}
```
![](/images/6.jpg)
---
## 7. Finding greatest of two numbers

```C
#include<stdio.h>
int main(){
    int a,b;
    printf("Enter 1st number ('a') :- ");
    scanf("%d",&a);
    printf("Enter 2nd number ('b') :- ");
    scanf("%d",&b);
    if(a>b){
        printf("A is greater");
    }
    else if(b>a){
        printf("B is greater");
    }
    else{
        printf("A and B are equal");
    }
    return 0;
}
```
![](/images/7.jpg)
---
## 8. To find greatest of three entered numbers

```C
#include<stdio.h>
int main(){
    int a,b,c;
    printf("Enter 1st number ('a') :- ");
    scanf("%d",&a);
    printf("Enter 2nd number ('b') :- ");
    scanf("%d",&b);
    printf("Enter 3rd number ('c') :- ");
    scanf("%d",&c);
    if(a>b && a>c){
        printf("A is greatest");
    }
    else if(b>c){
        printf("B is greatest");
    }
    else{
        printf("C is greatest");
    }
    return 0;
}
```
![](/images/8.jpg)
---
## 9. To print grade of a student by entering marks

```C
#include<stdio.h>
int main(){
    int marks;
    printf("Enter Marks of Student out of 100 :- ");
    scanf("%d",&marks);
    if(marks>=95){
        printf("O grade");
    }
    else if(marks<95 && marks>=90){
        printf("A Grade");
    }
    else if(marks<90 && marks>=80){
        printf("B Grade");
    }
    else if(marks<80 && marks>=70){
        printf("C Grade");
    }
    else if(marks<70 && marks>=60){
        printf("D Grade");
    }
    else if(marks<60 && marks>=50){
        printf("E Grade");
    }
    else if(marks<50 && marks>=40){
        printf("E- Grade");
    }
    else{
        printf("F Grade");
    }
    return 0;
}
```
![](/images/9.jpg)
---
## 10. To find roots of entered quadratic equation
```C
#include<stdio.h>
#include<math.h>
int main(){
    int a,b,c,d,z;
    float r1,r2;
    printf("Quadratic equation is in the form of [ ax^2 + bx + c ]\n");
    printf("Enter value of a :- ");
    scanf("%d",&a);
    printf("Enter value of b :- ");
    scanf("%d",&b);
    printf("Enter value of c :- ");
    scanf("%d",&c);
    d = (b * b) - 4*a*c;
    z = pow(d,0.5);
    if(a==0){
        printf("equation is not quadratic equation");
    }
    else if(d>=0){
        r1 = (-b+z)/2*a;
        r2 = (-b-z)/2*a;
        printf("Value of roots are %f and %f",r1,r2);
    }
    else{
        printf("roots are imaginary");
    }
    return 0;
}
```
![](/images/10.jpg)
---
## 11. To check whether entered year is leap year or not
```C
#include<stdio.h>
int main(){
    int year;
    printf("Enter Year :- ");
    scanf("%d",&year);
    if(year%4==0){
        printf("Entered Year is a leap year");
    }
    else{
        printf("Entered year is not a leap year");
    }
    return 0;
}
```
![](/images/11.jpg)
---
## 12. To generate table of 5
```C
#include<stdio.h>
int main(){
    int x;
    for(x=0;x<=10;x++){
        printf("5 X %d = %d \n",x,5*x);
    }
    return 0;
}
```
![](/images/12.jpg)
---
## 13.
```C
#include <stdio.h>
 
int main() {
	char Operator;
	float num1, num2, result;	
	printf("\n Please Enter the Values for two Operands: num1 and num2  :  ");
	scanf("%f", &num1);	
	printf("Please Enter an Operator :- ");
	scanf("%c", &Operator);
	printf("\n Please Enter the Values for two Operands: num1 and num2  :  ");
	scanf("%f", &num2);
	switch(Operator)
			{
  			case '+':
  				result = num1 + num2;
  				break;
  			case '-':
  				result = num1 - num2;
  				break;  			
  			case '*':
  				result = num1 * num2;
  				break;
  			case '/':
  				result = num1 / num2;
  				break;
			default:
				printf("You have entered an Invalid Operator ");				    			
			}

printf("The result of %.1f %c %.1f  = %.2f", num1, Operator, num2, result);

return 0;
}
```
---
## 14. To calculate reverse of a number
```C
#include <stdio.h>
int main(){
    int n, rn, rem,n1;
    rn=0;
    printf("Enter a number:- ");
    scanf("%d", &n);
    n1=n;
    while(n != 0){
        rem = n%10;
        rn = rn*10 + rem;
        n /= 10;
    }
    printf("Reversed Number = %d",rn);
    return 0;
}
```
![](/images/14.jpg)
---
## 15. To check whether a number is palindrome or not
```C
#include <stdio.h>
int main(){
    int n, rn, rem,n1;
    rn = 0;
    printf("Enter a number :- ");
    scanf("%d", &n);
    n1 = n;
    while(n != 0){
        rem = n%10;
        rn = rn*10 + rem;
        n /= 10;
    }
    if(rn == n1){
        printf("Number is Palindromic");
    }
    else{
        printf("Number is not Palindromic");
    }
    return 0;
}
```
![](/images/15.jpg)
---
## 16. To check whether a number is prime or not
```C
#include<stdio.h>
int main(){
    int a,i,x;
    printf("Enter number :- ");
    scanf("%d",&x);
    a=0;
    for(i=1;i<=x;i++){
        if (x%i==0){
            a=a+1;
        }            
    }
    if(a==2){
        printf("%d is a prime number",x);
    }
    else{
        printf("%d is not a prime number",x);
    }
    return 0;
}
```
![](/images/16(i).jpg)
![](/images/16(ii).jpg)
---
## 17. To print all prime numbers between 1 to 100
```C
#include<stdio.h>
int main(){
    int a,x,i;
    for(x=1;x<=100;x++){  
        a=0;
        for(i=1;i<=x;i++){
            if (x%i==0){
                a=a+1;
            }
        }
        if(a==2){
            printf("%d\n",x);
        }
    }
    return 0;
}
```
![](/images/17.jpg)
---
## 18. To check whether a number is armstrong or not
```C
#include<stdio.h>
int main(){
    int n,i,a,num=0;
    printf("Enter Number :-\n");
    scanf("%d",&n);
    a=n;
    while(n!=0){
        i=n%10;
        num=num+(i*i*i);
        n/=10;
    }
    if(a==num){
        printf("Entered number is an armstrong number");
    }
    else{
        printf("Entered number is not an armstrong number");
    }
    return 0;
}
```
![](/images/18.jpg)
---
## 19. A program to generate given patterns
```C
#include<stdio.h>
int main(){
    // ALL 3 PATTERNS ARE IN THIS FILE

/**********************************************************
**********************************************************/ 
    printf("\n");
    printf("FIRST\n");
    printf("\n");

    int i,j;
    for(i=1;i<=4;i++){
        for(j=1;j<=4;j++){
            if(j==1){
                printf("1 ");
            }
            else if(j==2 && (i==2 || i==3 || i==4)){
                printf("2 ");
            }
            else if(j==3 && (i==3 || i==4)){
                printf("3 ");
            }
            else if(j==4 && i==4){
                printf("4 ");
            }
        }
        printf("\n");
    }
/**********************************************************
**********************************************************/
    printf("\n");
    printf("SECOND\n");
    printf("\n");

    int a,b;
    for(a=1;a<=4;a++){
        for(b=1;b<=4;b++){
            if(a==1 && b==1){
                printf("1 ");
            }
            else if(a==2){
                if(b==1){
                    printf("2 ");
                }
                else if(b==2){
                    printf("3 ");
                }
            }
            else if(a==3){
                if(b==1){
                    printf("4 ");
                }
                else if(b==2){
                    printf("5 ");
                }
                else if(b==3){
                    printf("6 ");
                }
            }
            else if(a==4){
                if(b==1){
                    printf("7 ");
                }
                else if(b==2){
                    printf("8 ");
                }
                else if(b==3){
                    printf("9 ");
                }
                else if(b==4){
                    printf("10 ");
                }
            }
        }
        printf("\n");
    }

/************************************************************
************************************************************/
    printf("\n");
    printf("THIRD\n");
    printf("\n");

    int x,y;
    for(x=1;x<=4;x++){
        for(y=1;y<=7;y++){
            if(x==1){
                if(y==4){
                    printf("1 ");
                }
                else{
                    printf("  ");
                }
            }
            else if(x==2){
                if(y==3 || y==4 || y==5){
                    if(y==3 || y==5){
                        printf("1 ");
                    }
                    else if(y==4){
                        printf("2 ");
                    }
                }
                else if(y==1 || y==2 || y==6 || y==7){
                    printf("  ");
                }
            }
            else if(x==3){
                if(y==4){
                    printf("3 ");
                }
                else if(y==3 || y==5){
                    printf("2 ");
                }
                else if(y==2 || y==6){
                    printf("1 ");
                }
                else if(y==1 || y==7){
                    printf("  ");
                }
            }
            else if(x==4){
                if(y==4){
                    printf("4 ");
                }
                else if(y==3 || y==5){
                    printf("3 ");
                }
                else if(y==2 || y==6){
                    printf("2 ");
                }
                else if(y==1 || y==7){
                    printf("1 ");
                }
            }
        }
        printf("\n");
    }
    return 0;
}
```
![](/images/19.jpg)
---
## 20. To find largest number in 1 dimentional array
```C
#include<stdio.h>
int main(){
    int x,n,a;
    int arr1[10];
    for(x=0;x<10;x++){
        printf("Enter number for %d place in array :- ",x+1);
        scanf("%d",&n);
        arr1[x] = n;
    }
    for(int i=0;i<10;i++){
        a=0;
        for(int j=0;j<10;j++){
            if(arr1[i]>=arr1[j]){
                a=a+1;
            }
        }
        if(a==10){
            printf("%d is largest number in array",arr1[i]);
        }
    }
    return 0;
}
```
![](/images/20.jpg)
---
## 27. To calculate factorial of entered number
```C
#include<stdio.h>
int main(){
    int n1,n0,sum;
    sum=1;
    printf("Enter Number :- ");
    scanf("%d",&n1);
    for(int x=n1;x>1;x--){
        sum=sum*x;
        printf("%d * ",x);
        n1=n1-1;
    }
    printf("1");
    printf("\n");
    printf("%d",sum);
    return 0;
}
```
![](/images/27.jpg)
---
## 28. Program to print febonacci series
```C
#include<stdio.h>
int main(){
    int y,n1,n2,fn;
    printf("Enter length of fibonacci series :- ");
    scanf("%d",&y);
    n1=0;
    n2=1;
    printf("0, 1, ");
    for(int x=0;x<=y;x++){
        fn=n1+n2;
        printf("%d, ",fn);
        n1=n2;
        n2=fn;
    }
    return 0;
}
```
![](/images/28.jpg)
## 34. 
```C
#include <stdio.h>
int main() {
  int variable;
  int *pointer;
  variable = 99;
  pointer = &variable;
  printf("Address of variable = %p", &pointer);
  return 0;
}
```
![](/images/34.jpg)
