# Basic-C-programs
   Console Input and Output Functions
                                                  
░█████╗░░█████╗░███╗░░██╗░██████╗░█████╗░██╗░░░░░███████╗  ██╗███╗░░██╗██████╗░██╗░░░██╗████████╗
██╔══██╗██╔══██╗████╗░██║██╔════╝██╔══██╗██║░░░░░██╔════╝  ██║████╗░██║██╔══██╗██║░░░██║╚══██╔══╝
██║░░╚═╝██║░░██║██╔██╗██║╚█████╗░██║░░██║██║░░░░░█████╗░░  ██║██╔██╗██║██████╔╝██║░░░██║░░░██║░░░
██║░░██╗██║░░██║██║╚████║░╚═══██╗██║░░██║██║░░░░░██╔══╝░░  ██║██║╚████║██╔═══╝░██║░░░██║░░░██║░░░
╚█████╔╝╚█████╔╝██║░╚███║██████╔╝╚█████╔╝███████╗███████╗  ██║██║░╚███║██║░░░░░╚██████╔╝░░░██║░░░
░╚════╝░░╚════╝░╚═╝░░╚══╝╚═════╝░░╚════╝░╚══════╝╚══════╝  ╚═╝╚═╝░░╚══╝╚═╝░░░░░░╚═════╝░░░░╚═╝░░░

░█████╗░███╗░░██╗██████╗░  ░█████╗░██╗░░░██╗████████╗██████╗░██╗░░░██╗████████╗
██╔══██╗████╗░██║██╔══██╗  ██╔══██╗██║░░░██║╚══██╔══╝██╔══██╗██║░░░██║╚══██╔══╝
███████║██╔██╗██║██║░░██║  ██║░░██║██║░░░██║░░░██║░░░██████╔╝██║░░░██║░░░██║░░░
██╔══██║██║╚████║██║░░██║  ██║░░██║██║░░░██║░░░██║░░░██╔═══╝░██║░░░██║░░░██║░░░
██║░░██║██║░╚███║██████╔╝  ╚█████╔╝╚██████╔╝░░░██║░░░██║░░░░░╚██████╔╝░░░██║░░░
╚═╝░░╚═╝╚═╝░░╚══╝╚═════╝░  ░╚════╝░░╚═════╝░░░░╚═╝░░░╚═╝░░░░░░╚═════╝░░░░╚═╝░░░

███████╗██╗░░░██╗███╗░░██╗░█████╗░████████╗██╗░█████╗░███╗░░██╗░██████╗
██╔════╝██║░░░██║████╗░██║██╔══██╗╚══██╔══╝██║██╔══██╗████╗░██║██╔════╝
█████╗░░██║░░░██║██╔██╗██║██║░░╚═╝░░░██║░░░██║██║░░██║██╔██╗██║╚█████╗░
██╔══╝░░██║░░░██║██║╚████║██║░░██╗░░░██║░░░██║██║░░██║██║╚████║░╚═══██╗
██║░░░░░╚██████╔╝██║░╚███║╚█████╔╝░░░██║░░░██║╚█████╔╝██║░╚███║██████╔╝
╚═╝░░░░░░╚═════╝░╚═╝░░╚══╝░╚════╝░░░░╚═╝░░░╚═╝░╚════╝░╚═╝░░╚══╝╚═════╝░

Write a C program to perform addition, subtraction, multiplication and division of 2 numbers.
Aim:
To perform addition, subtraction, multiplication and division of 2 numbers.

Algorithm:
Step 1: Start the program.
Step 2: Declare the required variables a (1st number) and b(2nd number)
Step 3: Declare the required variables sm, diff, my, div
Step 4: Read the Input values a and b
Step 5: Compute sm = a + b, dif = a - b, my = a * b, div = a / b
Step 6: Display “sum is”,sm.
Step 7: Display “difference is”,dif.
Step 8: Display “Multiplication is”,my.
Step 9: Display “Division is”,div.
Step 10: Stop the Program.

Program:
#include &lt;stdio.h&gt;
void main()
{
int a,b;
float sm,dif,my,div;
printf(&quot;Enter the value of a:&quot;);
scanf(&quot;%d&quot;,&amp;a);
printf(&quot;Enter the value of b:&quot;);
scanf(&quot;%d&quot;,&amp;b);
sm = a+b;
dif = a-b;
my = a*b;
div = a/b;
printf(&quot;Sum is :%f\n&quot;,sm);
printf(&quot;Difference is :%f\n&quot;,dif);
printf(&quot;Multiplication is :%f\n&quot;,my);
printf(&quot;Division is :%f\n&quot;,div);
}

Result:
This program is executed successfully and the arithmetic functions is displayed in the screen using
input and output function.

b) Write a C program to swap values of 2 numbers with and without a third variable.
Aim:
To swap value of 2 numbers with and without a third variable.

Algorithm:
Step 1: Start the program.
Step 2: Declare the required variables 1st value(a) and 2nd value(b) and third variable(x)
Step 3: Read the Input values a and b
Step 4: Swap a and b using a third variable x
Step 5: Print the swapped value of a and b
Step 6: Declare the required variables 1st value(c) and 2nd value(d)
Step 7: Read the Input values c and d
Step 8: Swap c and d [c = c+d,d = c-d,c = c-d]
Step 9: Print the swapped value of c and d
Step 10: Stop the Program.

Program:
#include &lt;stdio.h&gt
void main()
{
int a,b,x;
float c,d;
printf(&quot;a and b are with another variable\n&quot;);
printf(&quot;Enter the value of a:&quot;);
scanf(&quot;%d&quot;,&amp;a);
printf(&quot;Enter the value of b:&quot;);
scanf(&quot;%d&quot;,&amp;b);
x = a;
a = b;
b = x;
printf(&quot;a = %d\n&quot;,a);
printf(&quot;b = %d\n&quot;,b);
printf(&quot;c and d are without variable\n&quot;);
printf(&quot;Enter the value of c:&quot;);
scanf(&quot;%f&quot;,&amp;c);
printf(&quot;Enter the value of d:&quot;);
scanf(&quot;%f&quot;,&amp;d);
c = c + d;
d = c - d;
c = c - d;
printf(&quot;c = %f\n&quot;,c);
printf(&quot;d = %f\n&quot;,d);
}

Result:
This program is executed successfully and swapped with and without the third variable is displayed
in the screen using input and output function.

c) Write a C program to read a 3 digit number and produce the following output
Aim:
To read a 3 digit number and produce the output

Algorithm:
Step 1: Start the program.
Step 2: Declare the required variables num, h(number of hundreds), t(number of tens), o(number of
ones)
Step 3: Read the Input value of num
Step 4: Compute h = num / 100, num = num % 100, t = num / 10, o = num % 10
Step 5: Print hundreds,tens and ones
Step 6: Stop the Program.

Program:
#include &lt;stdio.h&gt;
void main()
{
int num,h,t,o;
printf(&quot;Enter a three digit number:&quot;);
scanf(&quot;%d&quot;,&amp;num);
h = num / 100;
num = num % 100;
t = num / 10;
o = num % 10;
printf(&quot;hundreth = %d\n&quot;,h);
printf(&quot;Tenth = %d\n&quot;,t);
printf(&quot;Ones = %d\n&quot;,o);
}

Result:
This program is executed successfully and gave the right output of the number of hundreds,tens and
ones is displayed in the screen using input and output function.

d) Write a C program to accept the number of days from the user and convert into years, weeks and
days.

Aim:
To accept the number of days from the user and convert into years, weeks and days.

Algorithm:
Step 1: Start the program.
Step 2: Declare the required variables num, y(number of years), w(number of weeks), d(number of
days)
Step 3: Read the Input value of num
Step 4: Compute y = num / 365, num = num % 365, w = num / 7, d = num % 7
Step 5: Print hundreds,tens and ones
Step 6: Stop the Program.

Program:
#include &lt;stdio.h&gt;
void main()
{
int days,y,w,d;
printf(&quot;Enter the number of days:&quot;);
scanf(&quot;%d&quot;,&amp;days);
y = days / 365;
days = days % 365;
w = days / 7;
d = days % 7;
printf(&quot;number of years = %d\n&quot;,y);
printf(&quot;number of weeks = %d\n&quot;,w);
printf(&quot;number of days = %d\n&quot;,d);
}

Result:
This program is executed successfully and the number of years, weeks and days are displayed in the
screen using input and output function.

e) Write a C program to accept the temperature in fahrenheit and convert to celsius.

Aim:
To accept temperature in fahrenheit and convert it into celsius.

Algorithm:
Step 1: Start the program.
Step 2: Declare the required variable F( fahrenheit) and C(celsius)
Step 3: Read the Input value F
Step 4: Compute (F - 32)/1.8
Step 5: Print the temperature in Celsius
Step 6: Stop the Program.

Program:
#include &lt;stdio.h&gt;
void main()
{
float f,c;
printf(&quot;Enter the temperature in fahrenheit:\n&quot;);
scanf(&quot;%f&quot;,&amp;f);
c = (f - 32)/1.8;
printf(&quot;The temperature in celcius :%f&quot;,c);
}

Result:
This program is executed successfully and the temperature in farenheit is converted to celcius.
