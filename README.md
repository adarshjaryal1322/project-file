# PROGRAMMING FOR PROBLEM SOLVING 

### NAME - ADARSH JARYAL

### ROLL NO - 1914002

### BRANCH - CIVIL 

### SECTION - CE (A1)


# PROGRAM NO 1 : PROGRAM TO PRINT WELCOME MESSAGE 

 ` #include <stdio.h>`  
   `void main ()`  
  ` {`  
     `puts ("Welcome Budding Engineers");`  
   `}`  
   
   ## OUTPUT
   
   `Welcome Budding Engineers `
   
   
   
   # PROGRAM NO : 2 PROGRAM TO PRINT THE ADDRESS
   
  ` include <stdio.h>`  
`void main ()`  
`{`  
`puts ("House Number : 111");`  
`puts ("Street Number : 2");`  
`puts ("XYZ Nagar ");`  
`puts ("Patiala");`  
`}`  

## OUTPUT

`House Number : 111`  
`Street Number : 2`  
`XYZ Nagar`   
`Patiala`  

# PROGRAM NO 3 : PROGRAM TO FIND THE SUM OF TWO NUMBERS 

`#include <stdio.h>`  
`int main ()`  
`{`  
`int a,b,c;`  
`printf ("Enter first variable : ");`  
`scanf ("%d",&a);`  
`printf("Enter second variable : ");`  
`scanf ("%d",&b);`  
`c = a+b; `                                                
`printf("Sum of two variables is : %d\n",c);`  
`return 0;`                                                      
`}`  

## OUTPUT 

`Enter first variable : 10`  
`Enter second variable : 20`  
`Sum of two variables is : 30`  

# PROGRAM NO 4 : PROGRAM TO CONVERT TEMPERATURE FROM CELCIUS TO FAHRENHEIT

`#include <stdio.h>`  
`void main ()`                                                   
`{`  
`float num1,num2;`  
`printf ("\nEnter value in centigrade:\n");`  
`scanf ("%f",&num1);`  
`num2 = (num1*9/5)+32;`  
`printf ("\nValue in farenheit is :%.2f\n",num2 );`  
`}`  

## OUTPUT

`Enter value in centigrade:`  
`100`  

`Value in farenheit is :212.00`  

# PROGRAM NO 5 : PROGRAM TO FIND AREA AND PERIMETER OF A CIRCLE

`#include <stdio.h>`  
`int main ()`  
`{`  
`float radius,area, peri,pi=3.14 ;`  
`printf("Enter radius of circle :");`  
`scanf ("%f",&radius);`  
`area=pi*radius*radius;`  
`peri=2*pi*radius;`  
`printf("Area of circle : %f,",area);`  
`printf("Perimeter of circle : %f",peri);`  
`return 0;`  
`}`  

## OUTPUT 

`Enter radius of circle :5`  
`Area of circle : 78.500000,Perimeter of circle : 31.400002`  

# PROGRAM NO 6 : PROGRAM TO SWAP TWO NUMBERS WITHOUT USING THIRD VARIABLE 

`#include <stdio.h>`  
`int main ()`  
`{ `                                                                  
`int a,b;`  
`printf ("\nEnter the  value of a :");`  
`scanf ("%d",&a);`  
`printf ("\nEnter the value of b :");`  
`scanf ("%d",&b);`  
`a=a+b;`   
`b=a-b;`  
`a=a-b;`  
`printf ("\nThe swaped values of a : %d\n",a);`  
`printf ("\nThe swaped value of b : %d \n",b);`  
`return 0;`  
`}`  

## OUTPUT 
`Enter the  value of a :10`  

`Enter the value of b :20`  

`The swaped values of a : 20`  

`The swaped value of b : 10 `    

# PROGRAM NO 7 : PROGRAM TO CHECK WHETHER THE NUMBER IS EVEN OR ODD

`#include <stdio.h>`  
`int oddeven(int num1);`  
`int main ()`  
`{`  
`int s ;`  
`printf ("Enter the integer:");`  
`scanf ("%d",&s);`  
`oddeven (s);`  
`return 0;`  
`}`  
`int oddeven(int num1)`  
`{`  
`if (num1%2==0)`  
`printf ("The number is even");`  
`else`  
`printf ("The number is odd:");`  
`return 0;`  
`}`  

## OUTPUT 

`Enter the integer:177`  
`The number is odd` 

# PROGRAM NO 8 : PROGRAM TO PRINT FIZZBUZZ

`#include <stdio.h>`  
`void main()`  
`{`  
`int a,i;`  
`printf("enter the number ");`  
`scanf("%d",&a);`  
`for(i=1;i<=a;i++)`  
`{ if (i%15==0)`  
`printf("fizzbuzz\n");`  
`else if(i%5==0)`  
`printf("buzz\n");`  
`else if(i%3==0)`  
`printf("fizz\n");`  
`else`  
`printf("%d\n",i);`  
`}`  
`return 0;`  
`}`  

## OUTPUT 

`enter number 30`  
`1`  
`2`  
`fizz`  
`4`  
`buzz`  
`fizz`  
`7`  
`8`  
`fizz`  
`buzz`  
`11`  
`fizz`  
`13`   
`14`  
`fizzbuzz`  
`16`  
`17`  
`fizz`  
`19`  
`buzz`  
`fizz`  
`22`  
`23`  
`fizz`  
`buzz`  
`26`  
`fizz`  
`28`  
`29`  
`fizzbuzz`  

# PROGRAM NO 9 : PROGRAM TO PRINT DAYS OF A WEEK 

`#include <stdio.h>`  
`int main ()`  
`{`  
`int day;`  
`printf ("Enter the number of day (Consider Monday = 1 and Sunday = 7) : ");`  
`scanf ("%d",&day);`  
`switch (day)`  
`{`  
`case 1:`  
`printf ("\nToday is Monday\n ");`  
`break;`  
`case 2:`  
`printf  ("\nToday is Tuesday\n");`  
`break;`  
`case 3:`  
`printf ("\nToday is Wednesday\n");`  
`break;`              
`case 4:`  
`printf("\nToday is Thursday\n");`   
`break;`  
`case 5:`  
`printf ("\nToday is Friday\n");`  
`break ;`  
`case 6:`  
`printf ("\nToday is Saturday\n");`  
`break;`  
`case 7:`  
`printf("\nToday is Sunday\n");`  
`break;`  
`default :`  
`printf ("Please Enter a valid number ");`  
`}`  
`return 0;`  
`}`  

## OUTPUT 

`Enter the number of day (Consider Monday = 1 and Sunday = 7) : 3`  

`Today is Wednesday`

# PROGRAM NO 10 : PROGRAM TO FIND FACTORIAL OF A NUMBER 

`#include <stdio.h>`  
`void main()`  
`{`  
`int a,n=1,i;`  
`printf("enter i : ");`  
`scanf("%d",&i);`  
`for(a=1;a<=i;a++)`  
`n=n*a;`  
`printf("factorial of i is %d \n",n);`  
`}`  

## OUTPUT 

`enter i : 5`  
`factorial of i is 120`  

# PROGRAM NO 11 : PROGRAM TO CHECK WHETHER A NUMBER IS PRIME OR NOT 

`#include <stdio.h>`  
`int main ()` 
`{`  
`int n,i,flag=0;`  
`printf ("Enter the number : ");`  
`scanf ("%d",&n);`  
`for (i=2 ; i<=n/2 ; i++)`   
`{`              
`if (n%i == 0)`  
  `{`  
   ` flag = 1;`  
        `break;`    
   ` }`           
`}`              
`if (n==1)`         
`{`  
  `printf ("1 is neither a prime nor a composite number ");`  
`}`  
`else `  
`{`  
  `if (flag ==0)` 
`printf ("%d is a prime number.",n);`  
  `else`   
`printf ("%d is not a prime number.",n);`  
`}`  
`return 0;`  
`}`  

## OUTPUT 

`Enter the number : 235`  
`235 is not a prime number`  


# PROGRAM NO 12 : PROGRAM TO DISPLAY SERIES AND FIND SUM OF 1+1/2+1/3+.....+1/n
`#include<stdio.h>`  
`int main()`  
`{`  
`int num,i,sum=0;`  
`printf("Input any number: ");`  
`scanf("%d",&num);` 
`printf("1 + ");`  
`for(i=2;i<=num-1;i++)`  
`printf(" 1/%d +",i);`  
`for(i=1;i<=num;i++)`  
`sum = sum + i;`  
`printf(" 1/%d",num);`  
`printf("\nSum = 1/%d",sum+1/num);`  
`return 0;`  
`}`  

##  OUTPUT
   `Enter any no: 7`  
   `01 + 1/2 + 1/3 + 1/4 + 1/5 + 1/6 + 1/7`  


# PROGRAM NO 13 : PROGRAM TO DISPLAY SERIES AND FIND SUM OF 1+3+5+....+n
`#include<stdio.h>`   
 
`void main()`  
`{`  

`int n, i, sum = 0;`  
`printf(" Enter any number: " );`  
`scanf(" %d ", &n);`  

`for(i = 1; i<n; i = i + 2 )`  
`{`  
`printf(" %d + ", i);`  
`sum = sum + i;`  
`}`  
`printf(" %d ", n);`  
`printf(" \nSum = %d ", sum + n );`  
`getch();`    
 
  ##  OUTPUT
  `Enter any no:7`  
  `1+3+5+7`  
  `Sum=16`
  
  
  # PROGRAM NO 14 : PROGRAM TO SHOW SUM OF 10 ELEMENTS OF ARRAY AND SHOW THE AVERAGE
  
  `#include <stdio.h>`  

`int main()`  
`{`  
    `int Arr[10], n, i, sum = 0;`  

    `printf("Enter the number of elements you want to insert : ");`  
    `scanf("%d", &n);`    

    `for (i = 0; i < n; i++)`  
    `{`  
       `printf("Enter element %d : ", i + 1);`
        `scanf("%d", &Arr[i]);`  
        `sum += Arr[i];`  
    `}`  

    `printf("\nThe sum of the array is : %d", sum);`  
    `printf("\nThe average of the array is : %0.2f", (float)sum / n);`  

    `return 0;`  
`}`  


  ##  OUTPUT
  `Enter elements of an array:4`  
  `5`  
  `6`  
  `1`  
  `2`  
  `3`  
  `5`  
  `5`  
  `4`  
  `7`  
  `Sum=42`  
  `Average=4.22`  
  
  
  # PROGRAM NO 15 : PROGRAM TO FIND THE MAXIMUM NUMBER IN AN ARRAY
  `#include <stdio.h>`  
`int main()`  
`{`  
        `int array[50], size, i, largest;`  
        `printf("\n Enter the size of the array: ");`  
	      `scanf("%d", &size);`  
        `printf("\n Enter %d elements of  the array: ", size);`  
        `for (i = 0; i < size; i++)`  
		    `scanf("%d", &array[i]);`  
        `largest = array[0];`  
        `for (i = 1; i < size; i++)`   
        `{`  
		`if (largest < array[i])`  
			`largest = array[i];`  
	`}`  
    `printf("\n largest element present in the given array is : %d", largest);`  
    `return 0;`  
  `}`  
  
  ##  OUTPUT
  `Enter elements for array: 5`  
  `4`  
  `7`  
  `1`  
  `2`  
  `Maximum number=7`  
  
  
  # PROGRAM NO 16 :-PROGRAM TO PRINT A MATRIX

`#include <stdio.h>`  
`int main ()`  
`{`  
`int i,j,m,n;`  
`int matrix[10][20];`  
`printf ("Enter the number of rows:");`  
`scanf ("%d",&m);`  
`printf ("Enter the number of columns:");`  
`scanf ("%d",&n);`  
 
`for (i=0;i<m;i++)`  
`{ `  
`for (j=0;j<n;j++)`  
 `{`  
`printf ("Enter data in [%d][%d]:",i,j);`  
`scanf ("%d",&matrix [i][j]);`  
     `}`  
`}`  

`for (i=0;i<m;i++)`  
` {`  
 ` for (j=0;j<n;j++)`  
   ` { printf ("%d\t",matrix[i][j]);`  
     
   ` }`  
`printf  ("\n");`  
`}`  
`return 0;`  
`}`  

## OUTPUT

`Enter the number of rows:2`  
`Enter the number of columns:2`  
`Enter data in [0][0]:12`  
`Enter data in [0][1]:34`  
`Enter data in [1][0]:65`  
`Enter data in [1][1]:77`  
`12      34`  
`65      77`  

# PROGRAM NO 17 :-PROGRAM TO ADD TWO MATRIX

`#include <stdio.h>`  
`int main ()`  
`{`  
`int i,j,a[10][10],b[10][10],sum[10][10],m,n;  `
`printf ("Enter the number of Rows\n Enter the number of Columns:");`  
`scanf ("%d %d",&m,&n);`  
`for (i=0;i<m;i++)`  
`{`  
`for (j=0;j<n;j++)`  
`{`  
`printf ("Enter value of first matrix (%d %d) : ",i,j);`  
`scanf ("%d",&a[i][j]);`  
`}`  
`  }`  
`for (i=0;i<m;i++)`  
`{`  
`for (j=0;j<n;j++) `      
`{`  
`printf ("Enter value of second matrix (%d %d) : ",i,j);`  
`scanf ("%d",&b[i][j]);`  
`}`  
 ` }`  
`printf ("Sum of entered matrices :\n");`  
`for (i=0;i<m;i++)`  
`{`  
`for(j=0;j<n;j++)`  
`{`  
`sum [i][j]=a[i][j] + b[i][j];`  
`printf ("%d\t",sum [i][j]);`  
`}`  
`printf ("\n");`  
`}`  
`return 0;`  
`} `  

## OUTPUT 

`Enter the number of Rows`  
` Enter the number of Columns:2 2 `  
`Enter value of first matrix (0 0) : 12`  
`Enter value of first matrix (0 1) : 66`  
`Enter value of first matrix (1 0) : 34`  
`Enter value of first matrix (1 1) : 25`  
`Enter value of second matrix (0 0) : 22`  
`Enter value of second matrix (0 1) : 34`  
`Enter value of second matrix (1 0) : 97`  
`Enter value of second matrix (1 1) : 4`  
`Sum of entered matrices :`  
`34      100`  
`131     29`  

# PROGRAM NO 18 :-PROGRAM TO TRANSPOSE A MATRIX

`#include <stdio.h>`  
 
`void main()`  
`{`  
   ` static int array[10][10];`  
    `int i, j, m, n;`  
   ` printf("E8nter the order of the matrix \n");`  
    `scanf("%d %d", &m, &n);`  
   ` printf("Enter the coefiicients of the matrix\n");`  
    `for (i = 0; i < m; ++i)`  
   ` {`  
      `  for (j = 0; j < n; ++j)`  
       ` {`  
           ` scanf("%d", &array[i][j]);`  
        `}`  
   ` }`  
   ` printf("The given matrix is \n");`  
   ` for (i = 0; i < m; ++i)`  
   ` {`  
        `for (j = 0; j < n; ++j)`  
      `  {`  
           ` printf(" %d", array[i][j]);`  
      `  }`  
        `printf("\n");`  
   ` }  
   ` printf("Transpose of matrix is \n");  `
    `for (j = 0; j < n; ++j)`  
    `{`  
      `  for (i = 0; i < m; ++i)`  
       ` {`    
           ` printf(" %d", array[i][j]);`    
     `   }`    
       ` printf("\n");`    
   ` }`    
`}`    

## OUTPUT

`Enter the order of the matrix`  
`3 3`  
`Enter the coefiicients of the matrix`  
`3 7 9`  
`2 7 5`  
`6 3 4`  
`The given matrix is`  
` 3 7 9`  
` 2 7 5`  
` 6 3 4`  
`Transpose of matrix is`  
 `3 2 6`  
 `7 7 3`  
` 9 5 4`


# PROGRAM NO 19 :-PROGRAM TO SUBTRACT TWO MATRIX
`#include <stdio.h>`  
`int main ()`  
`{`  
`int i,j,a[10][10],b[10][10],minus[10][10],m,n;`  
`printf("Enter the number of Rows :");`  
`scanf ("%d",&m);`  
`printf ("Enter the number of columns :");`  
`scanf ("%d",&n);`  
`for (i=0 ; i<m ; i++)`  
`{`  
`for (j=0 ; j<n ;j++)`  
`{`  
`printf("Enter value of first matrix(%d %d) : ",i,j);`  
`scanf ("%d",&a[i][j]);`  
`}`  
  `}`  
`for(i=0;i<m;i++)`        
`{`  
`for (j=0;j<n;j++)`  
`{`  
`printf ("Enter value of second matrix (%d %d) : ",i,j);`  
`scanf ("%d",&b[i][j]);`  
`}`  
  `}`  
`for (i=0;i<m;i++)`  
`{`  
`for (j=0;j<n;j++)`  
`{`  
`minus [i][j] = a[i][j] - b[i][j] ;`  
`printf ("%d\t",minus[i][j] );`  
`}`  
`printf ("\n");`  
`}`  
`return 0;`  

## OUTPUT

`Enter the number of Rows :2`  
`Enter the number of columns :2`  
`Enter value of first matrix(0 0) : 143`  
`Enter value of first matrix(0 1) : 32`  
`Enter value of first matrix(1 0) : 56`  
`Enter value of first matrix(1 1) : 78`  
`Enter value of second matrix (0 0) : 22`  
`Enter value of second matrix (0 1) : 9 `  
`Enter value of second matrix (1 0) : 19`  
`Enter value of second matrix (1 1) : 56`  
`121     23`  
`37      22`  


# PROGRAM NO 20:- PROGRAM TO MULTIPLY TWO MATRIX  

`#include<stdio.h>`  
`void main()`  
`{`  
   ` int a[10][10],b[10][10],c[10][10],i,j,k,r1,c1,r2,c2;`  
    `int sum=0;`  
   ` printf("Enter number of rows and columns of first matrix (MAX 10)\n");`  
   ` scanf("%d%d",&r1,&c1);`  
    `printf("Enter number of rows and columns of second matrix MAX 10)\n");`  
    `scanf("%d%d",&r2,&c2);`  
    `if(r2==c1)``  
    `{`  
 
        `printf("\n Enter First Matrix:");`  
        `for(i=0; i<r1; i++)`  
        `{`  
            `for(j=0; j<c1; j++)`  
              `  scanf("%d",&a[i][j]);`  
        `}`  
        `printf("\n Enter Second Matrix: ");`  
       ` for(i=0; i<r2; i++)`  
        `{`  
           ` for(j=0; j<c2; j++)`  
              `  scanf("%d",&b[i][j]);`  
       ` }`  
        `printf("The First Matrix Is: \n");`  
       ` for(i=0; i<r1; i++)`  
        `{`  
           ` for(j=0; j<c1; j++)`  
              `  printf(" %d ",a[i][j]);`  
            `printf("\n");`  
       ` }`  
       ` printf("The Second Matrix Is:\n");`  
      `  for(i=0; i<r2; i++)`  
      `  {`  
          `  for(j=0; j<c2; j++)`  
              `  printf(" %d ",b[i][j]);`  
           ` printf("\n");`  
        `}`  
       ` printf("Multiplication of the Matrices:\n");`  
      `  for(i=0; i<r1; i++)`  
       ` {`  
          `  for(j=0; j<c2; j++)`  
           ` {`  
              `  c[i][j]=0;`  
                `for(k=0; k<r1; k++)`  
                    `c[i][j]+=a[i][k]*b[k][j];`  
                `printf("%d  ",c[i][j]);`  
           ` }`  
           ` printf("\n");`  
       ` }`  
 
   ` }`   
   ` else`  
   ` {`  
   `     printf("Matrix Multiplication is Not Possible");`  
    `}`  
`}`  

## OUTPUT 

`Enter number of rows and columns of first matrix (MAX 10)`  
`3`  
`3`  
`Enter number of rows and columns of second matrix MAX 10)`  
`3`  
`3`  
 
 `Enter First Matrix:2 2 2 2 2 2 2 2 2`  
 `Enter Second Matrix: 3 3 3 3 3 3 3 3 3`  
`The First Matrix Is:`  
 `2  2  2`  
` 2  2  2`  
 `2  2  2`  
`The Second Matrix Is:`  
 `3  3  3`  
 `3  3  3`  
` 3  3  3`  
`Multiplication of the Matrices:`  
`18  18  18`  
`18  18  18`  
`18  18  18` 


   # PROGRAM NO 21 : PROGRAM TO FIND TRANSPOSE OF A MATRIX
   `#include <stdio.h>`  
   `void main()`  
`{`  
    `int a[3][2],b[2][3],i,j;`  
    `printf("Enter the order of the matrix \n");`  
    `scanf("%d %d", &m, &n);`  
    `printf("Enter the coefiicients of the matrix\n");`  
    `for (i = 0; i < 3; ++i)`  
    `{`  
        `for (j = 0; j < 2; ++j)`  
        `{`  
            `scanf("%d", &array[i][j]);`  
        `}`  
    `}`  
    `printf("The given matrix is \n");`  
    `for (i = 0; i < 3; ++i)`  
    `{`  
        `for (j = 0; j < 2; ++j)`  
        `{`  
            `printf(" %d", array[i][j]);`  
        `}`  
        `printf("\n");`  
    `}`  
    `printf("Transpose of matrix is \n");`  
    `for (j = 0; j < 2; ++j)`  
    `{`  
        `for (i = 0; i < 3; ++i)`  
        `{`  
            `printf(" %d", array[i][j]);`
        `}`  
        `printf("\n");`  
    `getch();`  
    `}`  
    
     ##  OUTPUT
     `Enter value for matrix: 4`  
     `5`  
     `6`  
     `1`  
     `2`  
     `3`  
     `Matrix:`  
     `4 5`  
     `6 1`  
     `2 3`  
     `Transpose matrix:`  
     `4 6 2`  
     `5 1 3`  
     
     
 # PROGRAM NO 22 : PROGRAM TO SHOW INPUT AND OUTPUT OF A STRING
     `#include<stdio.h>`  
  `#include<conio.h>`    
`void main()`  
`{`  
`char a[50];`  
`clrscr();`  
`printf(“Enter any string: “);`  
`gets(a);`  
`printf(“Inputted string is: “);`  
`puts(a);`  
`getch();`  
`}`  

 ##  OUTPUT
 `Enter any string: hi everyone`  
 `hi everyone`  
 
 
 # PROGRAM NO 23 : PROGRAM TO FIND SQUARE OF A NUMBER USING FUNCTIONS
 `#include<stdio.h>`  
 `#include<conio.h>`  
 `void main()`  
 `{`
 `int rev(int);`  
 `int r,a;`  
 `clsrc();`  
 `printf("enter any no:");`  
 `scanf("%d,&a);`  
 `r=rev(a);`  
 `printf("square is : %d",x);` 
 `getch();`  
 `}`    
 `int rev(int x)` 
 `{` 
 `return(x*x);`  
 }
 
 ##  OUTPUT
 `enter any no: 5`  
 `square is: 25`  
 
 
 # PROGRAM NO 24 : PROGRAM TO SWAP TWO NUMBERS 
 
 `#include<stdio.h>`  

`void swap(int *,int *);`  
`int main()`  
`{`  

    `int n1,n2;`  
	`printf("\n\n Function : swap two numbers using function :\n");`  
	`printf("------------------------------------------------\n");`  	   
    `printf("Input 1st number : ");`  
    `scanf("%d",&n1);`  
    `printf("Input 2nd number : ");` 
    `scanf("%d",&n2);`  	

    `printf("Before swapping: n1 = %d, n2 = %d ",n1,n2);`  
    `swap(&n1,&n2);`  

    `printf("\nAfter swapping: n1 = %d, n2 = %d \n\n",n1,n2);`  
     `return 0;`  
`}`  

`void swap(int *p,int *q)`  
`{`  
    `int tmp;`  
    `tmp = *p;`   
    `*p=*q;`    
    `*q=tmp;`     
`}`  

## OUTPUT 

`Function : swap two numbers using function :`  
`------------------------------------------------`  
`Input 1st number : 2`  
`Input 2nd number : 4`  
`Before swapping: n1 = 2, n2 = 4`  
`After swapping: n1 = 4, n2 = 2`  
