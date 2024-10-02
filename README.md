# C
Dennis Ritche developed in 1972 at Bell labs.
It is standard by ANSI in 1989. It is a compiler language. The file extension is (.c).
# Features
1. High level language.
2. 32 Keywords
3. Portable
4. Has builtin functions.
5. Structured language and modular programing. 
6. It supports use of pointers.
7. extensible langugae.
8. compilation is faster.
9. Dynamic memory allocation.
10. Case sensitive.
11. We can use it in embedded systems.
12. It is platform dependent.
# Structure
1. Documentation. (Like comments single line(//), multiple lines(/* */))
2. Link section. (#include<stdio.h>, <conio.h>, <math.h>, etc)
3. Definition section. (declaring of constants like #define PI 3.14)
4. Global declaration.
5. Main section.
   5.1 Declartion
   5.2 Executable
6. sub program section. (user defined)
   
   ex:
   
         #include<stdio.h>   //link section
         void main()         //main section
         {
              printf("Hello World");  //executable 
          }
# Variables, Keywords, Identifiers in C
Variable : The name of the variable can be consist of alphabets(both upper and lower), numbers, and one special character that is underscore(_). There are some certain rules like.
1. Variable name should not start with number.
2. No space between words.
3. Variable name should not be keyword.
   example:
         Number_of_people = 10    (correct)
         _n = 1                   (correct)
         hel no = 10              (wrong)
   
Keywords : They are called as reserved words, pre-defined words. There are 32 keywords in C. They are also known as building blocks. Keywords are in lowercase letters. Some of the keywords like int, float, break, goto, if, for, continue, while, do, switch, auto, double, etc.

Identifiers : Name of an variable, function,  etc will be known as identifiers. The keyword should not be used as Identifiers. The identifers name follows the same rule as variables follow.
