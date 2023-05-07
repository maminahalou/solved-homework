Download Link: https://assignmentchef.com/product/solved-homework
<br>
5/5 - (1 vote)

1) Call foo() three times to print below.

1 2

3 4

5 6

2) Modify the calculator in lect16 as follows using argument-passing functions.

………………..

// function prototypes

void show_menu();

void add(int x, int y);

void sub(int x, int y);

………….

// function definitions

void main(){

int s;

for(;;){

show_menu();

scanf(“%d”, &amp;s);

if (s==1){

int x, y;

printf(“enter two numbers
”);

scanf(“%d %d”, &amp;x, &amp;y);

add(x, y);

}else if (s==2){

……………

}

……………..

}

}

void show_menu(){

printf(“1. add 2. sub 3. square 4. factor_of 5. power 6. factor 7. quit
”);

printf(“select operation
”);

}

void add(int x, int y){

// print x+y

int z;

z=x+y;

printf(“the sum is %d
”, z);

}

void sub(int x, int y){

// print x-y

………

}

void square(int x){

// print x*x

……..

}

void power(int x, int y){

// print x*x*…*x (y times)

……..

}

void factor_of(int x, int y){

// if x is a factor of y, print “x is a factor of y”

// otherwise “x is not a factor of y”

// for example if x=3, y=12, x is a factor of y

// because 12%3 = 0

…….

}

void factor(int x){

// display all factors of x

……………….