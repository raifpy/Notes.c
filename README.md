Table of Contents
=================
- [Table of Contents](#table-of-contents)
- [Comments](#comments)
- [Variables](#variables)
- [Operators](#operators)
  - [Arithmetic operators](#arithmetic-operators)
    - [Differences in left and right increase and decrease](#differences-in-left-and-right-increase-and-decrease)
  - [Bitwise operators](#bitwise-operators)
    - [OR](#or)
    - [AND](#and)
    - [NOT](#not)
    - [XOR](#xor)
    - [Shifting](#shifting)
  - [Logical Operators](#logical-operators)
  - [Triple-Argument Operator](#triple-argument-operator)
- [String formating](#string-formating)
- [Exercises](#exercises)
  - [The program that printing biggest number](#the-program-that-printing-biggest-number)
  - [The program that printing biggest char from ascii table](#the-program-that-printing-biggest-char-from-ascii-table)
  - [The program that taking numbers and operating bitwise operators](#the-program-that-taking-numbers-and-operating-bitwise-operators)
  - [The program that printing default C type values for some types](#the-program-that-printing-default-c-type-values-for-some-types)
  - [The program that taking two numbers from user and dividing to each other](#the-program-that-taking-two-numbers-from-user-and-dividing-to-each-other)
  - [The program that taking two numbers from user and dividing normaly and oppositely to each other.](#the-program-that-taking-two-numbers-from-user-and-dividing-normaly-and-oppositely-to-each-other)
  - [The program that checking number is even or not](#the-program-that-checking-number-is-even-or-not)
  - [The program that overflowing](#the-program-that-overflowing)
  - [The program that has own bitwise conjunction and disjunction operators](#the-program-that-has-own-bitwise-conjunction-and-disjunction-operators)
    - [Algorithm](#algorithm)
    - [Notes](#notes)
- [Conditional operations](#conditional-operations)
  - [if else](#if-else)
  - [ternary (triple-argument)](#ternary-triple-argument)
  - [switch-case](#switch-case)
- [Iteratives](#iteratives)
  - [for loop](#for-loop)
  - [while and do-while](#while-and-do-while)
    - [do-while loop](#do-while-loop)
  - [infinite loops](#infinite-loops)
  - [break](#break)
  - [continue](#continue)
- [Exercises](#exercises-1)
  - [The program that counting to 0 as a English](#the-program-that-counting-to-0-as-a-english)
    - [Brief explanation](#brief-explanation)
  - [The program that counting the sum of the arithmetic series](#the-program-that-counting-the-sum-of-the-arithmetic-series)
  - [Brief explanation](#brief-explanation-1)
    - [Do same exercise with other loops](#do-same-exercise-with-other-loops)
  - [The program that counting the sum of the geometric series](#the-program-that-counting-the-sum-of-the-geometric-series)
    - [Brief explanation](#brief-explanation-2)
    - [Do same exercise with other loops](#do-same-exercise-with-other-loops-1)
  - [Rewrite second exercise with possible shortest time.](#rewrite-second-exercise-with-possible-shortest-time)
    - [Brief explanation](#brief-explanation-3)
  - [The program that calculating factorial for the range \[0,10\]](#the-program-that-calculating-factorial-for-the-range-010)
  - [The program that calculating sin(π/3) with Maclaurin formula](#the-program-that-calculating-sinπ3-with-maclaurin-formula)
    - [Brief explanation](#brief-explanation-4)
  - [The program that calculating π with Leibniz formula](#the-program-that-calculating-π-with-leibniz-formula)
    - [Brief explanation](#brief-explanation-5)
  - [The program that calculating positive numbers square root with Newton's formula](#the-program-that-calculating-positive-numbers-square-root-with-newtons-formula)
- [Functions](#functions)
  - [Defination](#defination)
  - [Return values](#return-values)
  - [Calls](#calls)
- [Local Variables](#local-variables)
  - [static keyword](#static-keyword)
  - [register keyword](#register-keyword)
- [Pointers](#pointers)
  - [Local Pointers](#local-pointers)
- [Exercises](#exercises-2)
  - [The program that gives biggest number](#the-program-that-gives-biggest-number)
    - [Brief explanation](#brief-explanation-6)
  - [The program that counts days of week](#the-program-that-counts-days-of-week)
    - [Brief explanation](#brief-explanation-7)
  - [The program that counts arithmetic or geometric series sum](#the-program-that-counts-arithmetic-or-geometric-series-sum)
    - [Brief explanation](#brief-explanation-8)
  - [The program that calculates cuboids surface area](#the-program-that-calculates-cuboids-surface-area)
    - [Brief explanation](#brief-explanation-9)
  - [The program that calculates pyramids surface area](#the-program-that-calculates-pyramids-surface-area)
    - [Brief explanation](#brief-explanation-10)
  - [The program that determines pi value with given accuracy](#the-program-that-determines-pi-value-with-given-accuracy)
    - [Brief explanation](#brief-explanation-11)
  - [The program that determines the square root value with given digit and accuracy](#the-program-that-determines-the-square-root-value-with-given-digit-and-accuracy)
    - [Brief explanation](#brief-explanation-12)
  - [The program that calculates mod with only subtract operation](#the-program-that-calculates-mod-with-only-subtract-operation)
    - [Brief explanation](#brief-explanation-13)
  - [The program that takes charapter input from user and checks 'abba' combination](#the-program-that-takes-charapter-input-from-user-and-checks-abba-combination)
    - [Brief explanation](#brief-explanation-14)
- [Arrays](#arrays)
  - [Accessing array elements](#accessing-array-elements)
  - [Pointers](#pointers-1)
    - [Pointer Arithmetics](#pointer-arithmetics)
    - [Copy and Fill](#copy-and-fill)
- [Typedef](#typedef)
- [Enum](#enum)
- [Pseudo-Random](#pseudo-random)
- [Exercises](#exercises-3)
  - [Enum application](#enum-application)
  - [Random int array - Calculate the average number](#random-int-array---calculate-the-average-number)
  - [Random int array - Do the formula](#random-int-array---do-the-formula)
  - [Random int array - Find max and min values from the array](#random-int-array---find-max-and-min-values-from-the-array)
  - [Random int array - Compare with second and third exercise](#random-int-array---compare-with-second-and-third-exercise)
  - [Array with 4 elements which user takes - Do Horner formula](#array-with-4-elements-which-user-takes---do-horner-formula)
  - [Array which filled by user - Take opposite](#array-which-filled-by-user---take-opposite)
  - [Random int array - Half opposite](#random-int-array---half-opposite)
- [Sorting and binary search](#sorting-and-binary-search)
- [Sorting](#sorting)
  - [Selection Sort](#selection-sort)
- [Search in sorted arrays](#search-in-sorted-arrays)
  - [Binary Search](#binary-search)
- [Exercises](#exercises-4)
  - [Histogram of random array](#histogram-of-random-array)
  - [Random array sorting](#random-array-sorting)
  - [Random array sorting with counting algorithm](#random-array-sorting-with-counting-algorithm)
  - [Histogram of random array with range of -5 to 5](#histogram-of-random-array-with-range-of--5-to-5)
  - [Declare random array, calculate median and find the first and third quartiles](#declare-random-array-calculate-median-and-find-the-first-and-third-quartiles)
- [Strings](#strings)
  - [String Operations](#string-operations)
    - [fgets](#fgets)
    - [strlen](#strlen)
    - [strcmp](#strcmp)
    - [strcpy](#strcpy)
    - [strcat](#strcat)
    - [atoi](#atoi)
    - [strstr](#strstr)
    - [strtok](#strtok)
- [Exercises](#exercises-5)
  - [Check if the given string is palindrome](#check-if-the-given-string-is-palindrome)
  - [Check if the given strings are anagram](#check-if-the-given-strings-are-anagram)
  - [The program that takes real number with coma, and prints again with coma](#the-program-that-takes-real-number-with-coma-and-prints-again-with-coma)
  - [The program that re-indexes the sentence](#the-program-that-re-indexes-the-sentence)
  - [The program that doing find and replace](#the-program-that-doing-find-and-replace)
  - [The program that splitting the URL scheme](#the-program-that-splitting-the-url-scheme)
- [Arrays](#arrays-1)
  - [Multidimensional Arrays](#multidimensional-arrays)
- [Exercises](#exercises-6)
  - [Multiple random which filled 4x3 array with user given scaler](#multiple-random-which-filled-4x3-array-with-user-given-scaler)
    - [Memo](#memo)
  - [Find biggest and lowest values in 3x4 random filled matrix](#find-biggest-and-lowest-values-in-3x4-random-filled-matrix)
    - [Memo](#memo-1)
  - [Fill the matrix with random values than sort the matrix](#fill-the-matrix-with-random-values-than-sort-the-matrix)
    - [Memo](#memo-2)
  - [Fill 4x4 matrix randomly and get sum of rows and columns](#fill-4x4-matrix-randomly-and-get-sum-of-rows-and-columns)
  - [Fill 5x5 matrix with random numbers and compare diagonal sum with counter diagonal sum](#fill-5x5-matrix-with-random-numbers-and-compare-diagonal-sum-with-counter-diagonal-sum)
    - [Memo](#memo-3)
  - [Fill 5x5 matrix and reverse order the diagonal](#fill-5x5-matrix-and-reverse-order-the-diagonal)
  - [Do the same thing with counter diagonal matrix](#do-the-same-thing-with-counter-diagonal-matrix)
  - [Do the same thing with using both](#do-the-same-thing-with-using-both)
  - [The program that takes 10 words from user and prints the longest one](#the-program-that-takes-10-words-from-user-and-prints-the-longest-one)
- [Structures](#structures)
  - [Size of Structers](#size-of-structers)
  - [Accessing struct values from pointer](#accessing-struct-values-from-pointer)
  - [Bit Fields](#bit-fields)
  - [Structure Arrays](#structure-arrays)
- [Unions](#unions)
- [Exercises](#exercises-7)
  - [1. Declare struct with different kind of types and compare sizes](#1-declare-struct-with-different-kind-of-types-and-compare-sizes)
  - [2. Declare union with different kind of types and compare sizes](#2-declare-union-with-different-kind-of-types-and-compare-sizes)
  - [3. Program to print and convert coordinate systems to each other.](#3-program-to-print-and-convert-coordinate-systems-to-each-other)
  - [4. Sort personal data array by name and surname](#4-sort-personal-data-array-by-name-and-surname)
  - [5. Find two most distant cartesian points from random filled point array](#5-find-two-most-distant-cartesian-points-from-random-filled-point-array)


# Comments
Sometimes we need to think about our code lines. We writes little notes about our functions, variables, contsant etc. At this moment, we will use comments in our programming language. Every programming language have a comments syntax for theirselfs. In C language, we can use `// note` or `/* note */` with multiple commentments. Also we have another option with using compiler operators `#if #endif`.

Lets using singleline commentments. They are starting with `//` and ending with new line.
```c
// This is my comments
#include <stdio.h>
// #inclde <stdio.h> // You can also comment wrong code line

int main(){ // program starts with the main function

}
```
Very usefull. But lets say we have multiple lines to convert the comment. Of course you can add `//` line by line but it takes many time. This is why we have `/*  */` comment lines. There is no special name for this comments but lets say that multiple comments to this comment lines.  
```c
#include <stdio.h>

int main(){
    int testvalue;
    /*
    printf("Number: ")
    scanf("%d",&testvalue);
    if (testvalue != 10){
        return -1;
    }
    
    */
    testvalue = 10;
}
```
As you can see we used `/* */` instead of `//` comment. In this comment type you can add infinty lines betwen the `/*` and `*/`. Nevertheless sometimes this comment method works improperly. If you add second `*/` in among of `/* */`, it brokes all comment lines. 

I think third one is the most interesting way for the comments. We are using the compiler operators.

```c
#if 0
    Those lines are comments anymore!
#endif

#if 1
    // Those lines are not comments! So I have to use '//'
#endif
```
Of course this `compiler operators` are more deep than comments. However this isn't our topic for now.

# Variables
We can use `variables` to declare some values into memory. You can declare those variables as a `variable_type variable_name = value;`
```c
int global_counter;

int main(){
    int scope_counter;
}
```
As you can see, we can declare variables as a global or local. Also we didn't give them to any value. They are 0 anymore. They are occupy same size in the memory. What about other types and sizes?


|Variable Type|Size (byte)|Example|Declare
|-|-|-|-|
|int|4|10|`int _ = 10`
|short int|2|10|`short int _ = 10`
|long int|8|10|`long int _ = 10`
|float|4|10.0|`float _ = 10.0`
|double|8|10.0|`double _ = 10.0`
|long double|12|10.0|`long double _ = 10.0`
|unsigned **copy some number type**|*same as a copied type*|10|`unsigned int = 10`|
|char|1|a, 69(ASCII)|`char _ = 'a'`
*(These values are valid on a 64bit processor)* Also we can ensure variable sizes with `sizeof` function.

Example type convertetion and sizeof usage program
```c
#include <stdio.h>
int main(){
    char c = 'a';
    int c_as_ascii = (int)c; // type convertion

    printf("Char: %c\n",c);
    printf("Char in ascii: %d\n",c);
    printf("Char as int: %d\n",c_as_ascii);

    printf("Sizeof char: %d:%d\n",sizeof(c),sizeof(char));
    printf("Sizeof int: %d:%d\n",sizeof(c_as_ascii),sizeof(int));
}
```


```bash
$ gcc main.c -o out ; ./out
Char: a
Char in ascii: 97
Char as int: 97
Sizeof char: 1:1
Sizeof int: 4:4
```
# Operators
Magic starts here.
We created some 'read input-write something' application before. Now time to be more intelligent. Because we learned operators anymore.

## Arithmetic operators

- `increase by 1 ++ | decrease by 1 --`
- `add + | substract -`
* `multiplication * | division \`
* `rest of division %`

Let's say we have an `short int` value. We want to increase this value by 1. Of course we can increase and redeclare value by 1 `v = v + 1;`. Bu we have more brief and usefull solutions.
```c
short int sponge_bob = 10;

sponge_bob = sponge_bob + 1; // Adding
//or
sponge_bob += 1;
// or
sponge_bob++;
//or
++sponge_bob;
```

Also we can use these syntax to compute other operators.
```c
sponge_bob -= 10; // Substracting
sponge_bob *= sponge_bob; // sponge_bob = sponge_bob²  Multipling
sponge_bob /= 1; // Divising
sponge_bob %= 10; // Rest of divising
```

### Differences in left and right increase and decrease
```c
int hundered_1 = 100,hundered_2 = 100;
int value2 = ++hundered_1;
int value3 = hundered_2++;

printf("hundered_1: %d\n",hundered_1);
printf("hundered_2: %d\n",hundered_2);
printf("value2: %d\n",value2);
printf("value3: %d\n",value3);
```
We declared 100 as `hundered_1` and `hundered_2` as inital value in first line.  On the second line, we declared new value, named `value2`, with using the `left increased` `hundered_1`. On the third line, we changed `left increased` to `right increased` and we did same thing for `value3` variable. Let's execute and check what happend.
```c
hundered_1: 101
hundered_2: 101
value2: 101
value3: 100
```
We can see both incresing operators doing their job. But right increasing operator is selfish.

## Bitwise operators

* `OR |`
* `AND &`
* `NOT ~`
* `XOR ^`
* `Right shift >>`
* `Left shift <<`

We are using bitwise operators with binary. Also they are faster than [logical operators](#logical-operators).

### OR

Lets compute `7 | 4`

* `7 = 111` in binary format
* `4 = 100` in binary format
* `| = OR` bitwise operation
* `1 | 1 = 1`
* `1 | 0 = 1`
* `1 | 1 = 1`

Our result is `111` in binary format that equals to `7` in decimal format.
So we found `7 | 4` is `7`

### AND

Lets calculate same numbers with `&` bitwise operator.

* `7 = 111` in binary format
* `4 = 100` in binary format
* `& = AND` bitwise operation
* `1 & 1 = 1`
* `1 & 0 = 0`
* `1 & 0 = 0`

Our result is `100` in binary format that equals to `4` in decimal format.
```c
printf("7 OR 4 = %d\n", 7 | 4); // 7
printf("7 AND 4 = %d\n", 7 & 4); // 4
```

### NOT 

NOT `(~)` is an unary operator. That means we have to use single.
Let's say we have `7` and we want to calculate what is `~7`.
* `7 = 0111` in binary format, sign is `0`
* `7 = 0 0111` 7 is positive
* `~7 = 1 1000` not 7

Our sign bit is `1`. That means our digit is `negative` anymore.
`1000 (2)` = `8 (10)` -> `-8`
```c
printf("NOT 7 = %d\n", ~7); // NOT 7 = -8
```
Also we can try `NOT` operator with any negative number. It will be positive.

### XOR

We can say "if two bits are not 1 and 0 at the same time, XOR will be 1". I think this is the best explanation.

Let's compute `7 ^ 4`
* `7 = 0111` in binary format
* `4 = 0100` in binary format
* `^ = XOR` bitwise operation
* `1 ^ 1 = 0`
* `1 ^ 0 = 1`
* `1 ^ 0 = 1`
* `011`
`11` equals to `3` in decimal format. `7 ^ 4 = 3`

### Shifting
They are also very easy either. 
Lets say we have `7` and we want to left shifting by 1. `7<<1`
* `7 = 0111` in binary format
* `7 << 1 = 1110 `

`1110` is equals to `8+4+2 = 14`
- While left shifting growst the number, right shifting shrinks the number.
- Shiftings *doesn't effect* `positive` or `negative`.
- We can use same product to solve right shifting `>>`.

## Logical Operators
This time we will compare 1 and 0 again. But this time they are not bits.
We have `OR`, `AND`, `NOT` and others, again.
* `OR ||`
* `AND &&`
* `NOT !`
* `EQ ==`
* `NEQ !=`
* `Less <`
* `More >`
* `Less or equal <=`
* `More or equal >=`
They are all returns `1` or `0`. And if the value is not `0`, it will be `1`. 
```c
(1 && 2)  // 1
(0 && 1)  // 0
(4 && 3)  // 1
(1 || 0)  // 1
(0 || 10) // 1
(0 || 0)  // 0

(1 <= 1)  // 1
(1 < 1)   // 0
```
## Triple-Argument Operator
Briefly, with triple-argument operator, we can short if-else condition. Also it can be called as `ternary` operator in different programming languages. Syntax:
```c
type var = (condition1) ? if_condition__variable_1 : if_not_variable_2;
```
Let's say we have two numbers. We want to choose biggest one and multiple by 2 or 3.*

```c
int a,b,c;

if (a > b) c =  a *2;
else c = a*3;
```
We can do same thing with Triple-Argument Operator with one line.
```c
c = (a > b) ? (a*2) : (b*3)
```
`If` `a` is bigger than `b`, our `c` value will be `a*2`.
`If` `not`, our `c` value will be `b*3`.
It looks like confusing but it is very usefull.

# String formating
We can use `printf` function to print some formatted things to the console screen, who comes with `stdio.h`.
Also we can use `sprintf` function to save formatted value as string (char array) who comes with `stdio.h` either.
```c
int digit_bip_bop = 1;
printf("Hello World! bip_bop: %d |EOL|\n",digit_bip_bop);
```
```c
float float_number = 14.56755;
char string_buffer[100];
sprintf(string_buffer,"I can use %%f to format float number %f. Also I can change length visibility with %%.<number>f. See: %.2f",float_number,float_number);

puts(string_buffer); // print string_buffer
```
As you can see we formatted values with `sprintf / printf` functions. Also you can disable formatting with `%%` keyword.

|format|introduce|example|
|-|-|-|
|`%d`|digit|10|
|`%u`|unsigned int|10|
|`%f`|float|10.0|
|`%lf`|double|10.0|
|`%ld`|long int|10|
|`%e`|decimal|3e-9|
|`%x`|hex|10|
|`%o`|octal|10|
|`%c`|char|'a'|
|`%hhu`|unsigned char|69|

# Exercises
## The program that printing biggest number
User gives us a three numbers. And we calculates biggest one.
```c
#include <stdio.h>

void readDigits()
{
    int digit1, digit2, digit3;
    printf("First digit:");
    scanf("%d", &digit1);
    printf("Second digit:");
    scanf("%d", &digit2);
    printf("Thirth digit:");
    scanf("%d", &digit3);
    // Without any loop, we are using scanf by line by line

    int largest = (digit1 > digit2) ? (((digit1 > digit3) ? digit1 : digit3)) : (((digit2 > digit3) ? digit2 : digit3)); // without any loop, we are using operators by variable by variable
    printf("Your biggest digit is %d\n", largest);
}

int main(void){
    
    readDigits();
}
```

As you can see, we used `triple argument operator` instead of classical `if-else`.

## The program that printing biggest char from ascii table
We can develop our application with to following diagram but it is not good choice.
```c
char a,b,c;
printf("Char1: ");
scanf("%c",&a);
printf("Char2: ");
scanf(" %c",&b);
printf("Char3: ");
scanf(" %c",&c);
```

This time we won't use line by line `scanf` function. This time we will take `string` from user. Than we can cut char by char or range by range.
```c
#include <stdio.h>

char convertToSmaller(char upper){
    return (upper + 32);
}

char checkIsItUpper(char _alp){
    return ((_alp >= 65 && _alp <= 90));
}

char checkIsItLetter(char alp){
    return ( checkIsItUpper(alp) || (alp >= 97 && alp <= 122));
}

int main(){
    char chars[3]; // char array capable of 3 char 
    printf("Give me 3 charapter: ");
    scanf("%s",chars);
    printf("Processing data: [%c%c%c]..\n",chars[0],chars[1],chars[2]);

    if (!checkIsItLetter(chars[0])){
        printf("Index:0 char %c (%d) is not letter on ASCII.\n",chars[0],(int)chars[0]);
        return -1; 
    }

    chars[0] = ( checkIsItUpper(chars[0]) ) ? convertToSmaller(chars[0]) : chars[0];


    if (!checkIsItLetter(chars[1])){
        printf("Index:1 char %c (%d) is not letter on ASCII.\n",chars[1],(int)chars[1]);
        return -1; 
    }

    chars[1] = ( checkIsItUpper(chars[1]) )  ? convertToSmaller(chars[1]) : chars[1];


    if (!checkIsItLetter(chars[2])){
        printf("Index:2 char %c (%d) is not letter on ASCII.\n",chars[2],(int)chars[2]);
        return -1; 
    }

    chars[2] = ( checkIsItUpper(chars[2]) )  ? convertToSmaller(chars[2]) : chars[2];
    // Programming is pain when we didn't learn any loops.

    char biggest = (chars[0] > chars[1]) ? chars[0] : chars[1];
    biggest = (chars[2] > biggest) ? chars[2] : biggest;

    printf("Your biggest char is %c (%d as an ascii)\n",biggest,(int)biggest);
    return 0;
}
```

Both algorithms are not well either. Because when we want to increase 3 char to 4 char, we have to re-write almost whole code again. However let me explain the code! I used char array instead of the 3 times char variable. With char array, I can increase or decrease user input number easyly and I can give more talent to the application. Arrays counter starts in 0. So if array has a 1 length, you must use 0th index to access/modifiy array value. We created array of size 3 and assigned values one by one. We want to compare chars with their ascii table equivalent. Because computer can't compare the charapters without else.

We have 2 types letters in `ASCII table`. `Upper` letters and `Lower` letters. Every letter has an equivalent of as a Upper or Lower. So we can turn them into each other with basic add and substract process. Also we know ascii equivalents of all english letters. Our algorithm is using this.
Char is digit type like a int. So we can use number operators on char type to check char is letter or not. If is it, we can use number operators to check letter is upper or lower, again. Than we are converting upper letter to lower to compare letters ascii value correctly. Last step is check which one is biggest. Wspaniale!

Also you can see our `non-zero` return code effect in my command shell.

## The program that taking numbers and operating bitwise operators

```c
#include <stdio.h>

int main(){
    unsigned char input1,input2;

    printf("Number1: ");
    scanf("%hhu",&input1);

    printf("Number2: ");
    scanf("%hhu",&input2);

    printf("Numbers:\n*\t%d (hex=%x)\n*\t%d (hex=%x)\n\n",input1,input1,input2,input2);

    unsigned char and = input1 & (input2);
    unsigned char or = input1 | (input2);
    unsigned char xor = input1 ^ (input2);

    printf("%d AND %d = %d |\033[31m hex= %x \033[0m\n",input1,input2,and,and);
    printf("%d OR %d = %d |\033[31m hex= %x \033[0m\n",input1,input2,or,or);
    printf("%d XOR %d = %d |\033[31m hex= %x \033[0m\n",input1,input2,xor,xor);
    // I hope that target computer supporting terminal colors.
}
```

You can use `\033[<color_code>m` `TEXT` `\033[0m` format to colorize your output. However if you are using Windows's cmd console to run the application, it won't work.
## The program that printing default C type values for some types
```c
#incude <stdio>.h
int global_integer;

int main(){
        int integer;
    short int short_integer;
    double _double;

    printf("equality: %d\n",(integer == 0));
    printf("equality global_int: %d\n",(global_integer == 0));

    printf("int: %d\n",integer);
    printf("short int: %d\n",short_integer);
    printf("double: %lf\n",_double);

    printf("global_int: %d\n",global_integer);
}
```
```bash
equality: 0
equality global_int: 1
int: 32767
short int: -2050
double: 0.000000
global_int: 0
```
I didn't expecting this response either. However with short [Googling](https://stackoverflow.com/questions/6212921/is-un-initialized-integer-always-default-to-0-in-c), I found why this is happening.
```
automatic (local) variables are not guaranteed to be zero, can contain garbage.
global variables and static variables are guaranteed to be zero.
-
It depends on how the variable is allocated. Statically allocated variables are initialized to zero, whereas variables allocated on the stack or with malloc() are not.
```
We didn't learn alloc, malloc, heap etc. memory terms yet

## The program that taking two numbers from user and dividing to each other

```c
#include <stdio.h>

int main(){
    int num1,num2;
    printf("Number1: ");
    scanf("%d",&num1);
    printf("Number2: ");
    scanf("%d",&num2);

    if (num2 == 0){
        puts("Number2 can't be zero!"); // We can't divide numbers with 0
        return -1;
    }

    printf("%d/%d= %d\n",num1,num2,(num1/num2));

    printf("%d/%d= %f\n",num1,num2,(float)(num1/num2));
    
    printf("%d/%d= %f\n",num1,num2,((float)num1/num2));
}
```
```go
Number1: 10
Number2: 3
10/3= 3
10/3= 3.000000
10/3= 3.333333
```
As you can see if we divide `int` to another `int` our response will be also `int`. This is why we have to convert least one int to `float`, to find `float` in result.

## The program that taking two numbers from user and dividing normaly and oppositely to each other.

```c
#include <stdio.h>

void div_message(char *buf,int num1,int num2){

    if (num2 != 0)
        sprintf(buf,"We can divide (%%d) with (%%d): %.2f",((float)num1 / num2));
    else 
        sprintf(buf,"We can't divide (%%d) with (%%d). Diviser can't be zero.");

    sprintf(buf,buf,num1,num2);
}
int main(){
    int num1,num2;
    printf("Number1: ");
    scanf("%d",&num1);

    printf("Number2: ");
    scanf("%d",&num2);

    char buf[1024];  // 1kb buffer for messages

    div_message(buf,num1,num2);
    printf("%s\n",buf);

    div_message(buf,num2,num1);
    printf("%s\n",buf);
}
```
```bash
Number1: 10
Number2: 0
We can't divide (10) with (0). Diviser can't be zero.
We can divide (0) with (10): 0.00
```

I used char buffer communication who useless for arithmetic operators but great for strings. Program uses least 1kb memory when allocates `char buf[1024]`. However developer have to use`free` in complex programs who allocated buffer when done with it.

## The program that checking number is even or not

I had my first idea was converting decimal number to binary as a char array. But they are requiring the loops -or function who calls itself-. I don't want to use any loop in this part. Also there is a very easy method more than converting bits. We can divide to 2 as a int type. Then we can multiple answer with 2, and substract multiplied answer with user input. Then we can check to response is 0 or 1.
```c
int num;
printf("Number: ");
scanf("%d",&num);

if (num-(num / 2)*2){ // rule of math operation priority
    printf("Number is odd");
} else{
    printf("Number is even");
}
```
It is working well!

## The program that overflowing
```c
#include <stdio.h>

int main(){
    unsigned char c;
    printf("char size: %d byte\n",sizeof(c));
    printf("char before: %d\n",c);

    printf("char after: %d\n",--c);
}
```
```
char size: 1 byte
char before: 0
char after: 255
```
We know that `char` has a 1 byte size. That means char occupy 8 bits in memory.
`0000 0000` Also we know that in `signed maginute` first bit is `sign bit`, others are `magnitude`. But our type is `unsigned char`. So we don't have to worry about sign bit because there is no sign bit in unsigned types. Also this is why they are just positive.

*Reminder:* When we add `1` to '1' response will be `10` in binary format. But we can't store 2 numbers in 1 bit, so the incremantel 1 is transffered to the next digit.

*Example:*
```
0101
0001
+___
0110
```

Also we can do some addification process on decimal. `5` + `1` = `6` (`0110`). Same rules are exists on substraction processes either.
\
`0 is in 1 unsigned byte` ` ->  ` `00000000` \
`1 is in 1 unsigned byte` ` ->  ` `00000001` 

If we add those 2 bits we will find `1` in decimal and binary.
However let's try to substract.
\
`0` `0` `0` `0` `0` `0` `0` `0` \
`0` `0` `0` `0` `0` `0` `0` `1` \
`- __________`

It is looking like impossible. But not. 
Let's image our first number have `9` bits and starting with `1`
`100000000`. This is actually `-0` in `signed` types but don't hung up on it. We are just imaginering. Our new process is as follows

`1` `0` `0` `0` `0` `0` `0` `0` `0` \
&nbsp;&nbsp;&nbsp;`0` `0` `0` `0` `0` `0` `0` `1` \
`- ____________`

Let's substract 1 from 10 in every decimal.

= `0` `1` `1` `1` `1` `1` `1` `1` `1` \
And we are realized that we have only 8 bits! \
= `1` `1` `1` `1` `1` `1` `1` `1` \
Last step is process to binary to decimal. \
= `255` \
Also we take `0` answer when we try to add `1` to `255` in signed char.

Let's say we used `signed char` instead of `unsigned char`.
Our response will be `-127`. Because our first bit is `signed bit` and number does negative when the signed bit is `1`

## The program that has own bitwise conjunction and disjunction operators
There is a lot of thing to talk about this program. First of all developer have to know how programming working point by point. Otherwise this program prepration going to be impossible.

### Algorithm
`|` and `&` are bitwise operators. They are working with bits. So I have to follow same scheme. I created function that converting the int to the char array. This converted char array is our bits anymore. We are doing compare process with these bits by index by index.


### Notes
I don't want to use loops in this part. So I used self-called functions as a last resort. This is why I spent a lot of time to write those code lines. However that was very fun to think and create.

Algorithm was easy but C tired me.
```c
#include <stdio.h>
#include <stdlib.h> // abs
#include <math.h> // pow
#define array_size 32

int binaryToInt(char *buf,char size,char _index,int total){
    if (_index == size){
        if (buf[0] == 1){
            total *= -1;
        }
        return total;
    }
    return binaryToInt(buf,size , 1+_index , total+(buf[_index] * pow(2,size-(_index+1))));
}


int bitwise_or(int num1,int num2){
    char num1_buf[array_size] = {};
    convertToBinary(num1_buf,num1);
    
    char num2_buf[array_size] = {};
    convertToBinary(num2_buf,num2);

    char output_buf[array_size] = {};
    _bitwise_or(num1_buf,num2_buf,output_buf,0);


    return binaryToInt(output_buf,32,0,0);
}


void _bitwise_or(char *array1,char *array2,char *out,char index){
    if (index == array_size){
        return;
    }

    out[index] =  (char)(array1[index] || array2[index]); // I hope that I am still not using | 
    
    _bitwise_or(array1,array2,out,index+1);
}

int bitwise_and(int num1,int num2){
    char num1_buf[array_size] = {};
    convertToBinary(num1_buf,num1);
    
    char num2_buf[array_size] = {};
    convertToBinary(num2_buf,num2);

    char output_buf[array_size] = {};
    _bitwise_and(num1_buf,num2_buf,output_buf,0);
    return binaryToInt(output_buf,32,0,0);
}

void _bitwise_and(char *array1,char *array2,char *out,char index){
    if (index == array_size){
        return;
    }

    out[index] =  (char)(array1[index] && array2[index]); // I hope that I am still not using &
    _bitwise_and(array1,array2,out,index+1);
}


void convertToBinary(char *list,int _num){
    if (_num == 0){
        return;
    }


    int num = (_num < 0) ? abs(_num) : _num;

    _2_divider_self(list,num,0);

    opposite_array(list,0,array_size);

    if (_num < 0){
        list[0] = 1;
    }
}

void _2_divider_self(char *list,int num,char _index){

    //char index = (array_size-1-_index);
    char index = _index;

    //printf("debug num: %d\n",num);    
    //printf("debug _index: %d\n",_index);
    //printf("debug index: %d\n",index);

    if (num == array_size-1){
        //opposite_array(list,0,(char)sizeof(array)/sizeof(char));
        //printf("\033[31m return \033[0m");
        return;
    }
    else if (num < 2){
        list[index] = 1;
        //printf("adding last: %d\n",1);
        //opposite_array(list,0,(char)sizeof(array)/sizeof(char));
        return;
    }

    char div = num / 2;
    //printf("debug div: %d\n",div);
    list[index] = num - (div * 2);
    //printf("added %d\n",list[index]);
    //printf("add in index %d\n",index);
    _2_divider_self(list,div,_index+1);
}

int _bitwise(){
    int operand1,operand2,response;
    char operator,reliability;
    
    printf("Process (1 & 2): ");
    scanf("%d %c %d",&operand1,&operator,&operand2);
    
    
    switch (operator){
    case '|':
        // OR

        response = bitwise_or(operand1,operand2);
        reliability = response == operand1 | operand2;

        break;
    case '&':
        // AND
        response= bitwise_and(operand1,operand2);
        reliability = response == (operand1 & operand2);

        break;
    default:
        printf("operator have to be '|' or '&'. Not %c (%d)!\n",operator,operator);
        return -1;
    }

    printf("(%d %c %d) = %d | Response is %s\n",operand1,operator,operand2,response, ( (reliability) ? "\033[32mTRUE\033[0m" : "\033[31mFALSE\033[0m" ));
}

void opposite_array(char *array,char num,char size){
    char reindex = size-(num+1);

    //printf("debug opposite num=%d to=%d size=%d\n",num,reindex,size);
    if (num == size/2){
        return;
    }

    //printf("SWAP %d(%d)-> %d(%d)\n",num,array[num],reindex,array[reindex]);

    char nume = array[num];
    char value = array[reindex];
    array[num] = value;
    array[reindex] = nume;
    
    //printf("array-%d: %d\n",num,array[num]);
    //printf("array-%d: %d\n",reindex,array[reindex]);
    
    return opposite_array(array,num+1,size);
}

int bitwise(){
    puts("Press ctrl+c to exit");
    while (1) _bitwise(); // I know sir, you need this loop
}

int main(void){
    bitwise();
}
```
Also the program using `libmath` extarnel library. 

# Conditional operations

## if else

if-else condition is briefly commands `"do something if condition is true, do something else if condition is not true"`.
Finally we can use if-else condition into our program.

```c
if ( 10 > 9 ){
    printf("Hello World!\n")
}
```
`10` is bigger than `9`. So our condition is valid. We can see `Hello World!` on terminal after executing.

What about `else`?
`else` keyword is doing opposite of `if` condition. `else` block runs when `if` condition is not `true`.

```c
if ( 0 );
else{
    printf("else-block working!\n");
}
```
You can see "else-block-working" text in your terminal. Also I am sure that you noticed that `0` and without bracket usage in the above example. They are legal usage of C syntax. `0` equivelent to `false` exactly. And if a 'thing' is not `0`, that 'thing' equilivent to `true`. Also there is not thing like `true - false` in C language. Everything is zero or not.

```c
if ( -1 ) printf("don't forget that -1 is not 0");
```
This condition is also valid. Because as mentioned in the code, `-1` is not `0`. Also you can write your statement without brackets if your statement is only __1 line__. But bracketless statements are not suggested. The best, learn keyboard combination to { and }. :)

Let's say we need more than 2 conditions. We are trying to create some redirector who takes input from user. Can we use more `if` than single?

```c
int a = 10;
if ( a ==10 ) printf("a is 10");
if ( a ==9 ) printf("a is 9");
if ( a ==8 ) printf("a is 8");
```
This usage is also legal. But this is not good for CPU. Because first condition is valid and we don't need to check others in runtime. This means more unnecessary work for the CPU. However we can solve this extra problem with `else if` keyword easily.

```c
if (0) printf("first condition");
else if (1) printf("second condition");
else if (1) printf("thirth condition");
else printf("else condition");
```
We have 3 valid condition right? `1` is always `true` and `if` is not valid so `else` condition is also valid. But you will see only `second condition` text on the screen. Let me fix myself. I had wrote `else` is valid when `if` is not. But it is wrong. `else` is valid only when the other conditions are not valid. And unlike the `if-if-if` condition, `if-elseif` condition stops the looking other conditions when finds valid one. In above example first `else if` condition is valid so it is enought. You should convert all other conditions to invalid to work with `else` block.

## ternary (triple-argument)

This condition is doing same job with if-else condition. But main difference is ternay operator has an able to usable with variable defination.

```c
int i;
//i = if (1) 10; else 20; // syntax error
int and = (i == 0) ? 5 : i*2; 

// if else form:
if (i == 0) and = 5; 
else and = i*2;
```
Turnary maybe not conformatable for the code review but it is very usefull for clean code.

## switch-case
Let's say we have an multiple inputs coming from somewhere. And we want condition them. Of course we can use if-else condition but we have alternative.
We can use switch-case operation.
```c
#include <stdio.h>
int main(){
    int i = 10;
    switch(i){
        case 1:
            printf("condition 1 matched!\n");
            // fill it
            break;
        
        case 2:
            printf("condition 2 matched!\n");
            // fill it
            break;
   
        default: printf("The i variable (%d) not matched with our conditions.\n",i);
    }   
}
```
In fact, it is doing same job with if-else. The important thing is `break` keyword. You have to add `break` keyword into the end of the statement. Otherwise your other condition -whatever are they- will be valid. Weird huh?

# Iteratives
We have 2 type of loop in C language. I think the thirth one is same with second one so I will mention it in the second one's section. Loops are briefly operators who help us to run our statement without duplicate lines.

## for loop
We are mostly using `for loops` for the counting. 
```c
for (int i = 0;i<10;i++) printf("Counter: %d\n",i);
```
In the above example, we are assigning new variable as a int, then we are checking condition, then running statement. After all we are doing `i++` -increasing i to 1- statement. I know it is hard to savvy exactly. However not finished yet.
```c
for (int i=0;i<10;i*=2) printf("Counter: %d\n",i);
```
I sayed 'start counting from 0 and while condition is valid, assign i multiple by 2 to the i variable' to the for loop. Let us check what is for loop's answer.
```
Counter: 0
Counter: 0
Counter: 0
Counter: 0
Counter: 0
Counter: 0
Counter: 0
Counter: 0
Counter: 0
Counter: 0
Counter: 0
Counter: 0
Counter: 0
Counter: 0
...
```
We are stucked in a infinite loop! Whatever, we have the os signals to terminate the application friendly and we can use with pressing `ctrl`+`c`. What happened?
Basicly our for loop is checking condition given to it. And we gave `i is less than 10` condition. After the condition confirmation, our for loop executing statement, what we gave to it. And we had gave `multiple i with 2` to it. The problem is `i` initialized from for loop, by 0. So we are trying to multiple 0 with 2. Answer is always 0. And condition is always valid.

## while and do-while

We are using the while loops for repeated statements. It is helping us to 'do not repeat yourself'.

```c
char some_function_that_unstable(){
    // fill it!
    return (1) ? 1 : 0;
}

printf("Waiting to initiliaze");
while ( some_function_that_unstable() == 0);
printf("Initiliazed");
```
If you run it, you will see that your CPU usage will be crazy.  Because this is an infinite loop in this case.

### do-while loop
I think `do-while` loop is most unnecessary loop in C language. Modern languages don't even have `do-while` loop. 
```c
int _ = 0;
do{
    _++;
} while(_ < 10);
```
As you can see we can use `while` loops for counting. In the do-while loop, do case works before while's condition check. So in above example, first condition is `1 < 10`.
Both loops are have a very large uses cases.

## infinite loops
As I mentioned in `for` and `while` loops. They are hard-worker statements. Never finishes their jobs. Actually they are very usefull in programming. But we have to learn how to exit from the infinite loops.
```c
while(1); // condition is always true
```
```c
for(;1;); // condition is always true
```
Also you can use `for(;;)` instead of `for(;1;)`. They are same for C compiler.

## break 

We had used `break` keyword in the `switch-case` condition. Other uses case is in the loops. We are using `break` for break the any loop.
```c
for (int i = 0;i<10;i++){
    if (i == 4) break;

    printf("i: %d\n",i);
}
```
The loop will break when i arrives a value of `4`. Our program will count from `0` to `4` `(4 not included)` `[0,4)`

## continue
Let's say we have for loop and we want to do nothing if our variable equals to `5`. But otherwise we want to calculate something.
```c
for (char i = 0; i<10;i++){
    if (i == 5){
        // Don't do anything
    }else{
        // Calculate something
    }
}
```
This usage is legal. But not that perfect. Let us use `continue` keyword.
```c
for(char i = 0;i<10;i++){
    if (i == 5) continue;

    // Caulculate something
}
```
Better huh? `continue` keyword keeps the cycle going.

# Exercises

## The program that counting to 0 as a English

```c
#include "stdio.h"
#include "stdlib.h"

char *intToText(int i){
    char *word;
    word = malloc(6); // 1*6
    switch (i){
        case 0:

            word = "zero";
            //strcpy(word,"zero");
            break;

        case 1:             word="one"; break;
        case 2:             word="two"; break;
        case 3:             word="three"; break;
        case 4:             word="four"; break;
        case 5:             word="five"; break;
        case 6:             word="six"; break;
        case 7:             word="seven"; break;
        case 8:             word="eight"; break;
        case 9:             word="nine"; break;
        case 10:
            word="ten";break;
        default:
            word="unknown";

    }

    return word;
}

char *intToTextP(int i,char power){
    char *response = intToText( (power) ? i : -1*i );
    if (power || !i) return response;

    char *buf = malloc(5+6+1);
    sprintf(buf,"minus %s",response);
    //free(response); // :/
    return  buf;
}

int main(){
    char v;
    _:
    printf("digit: ");
    scanf("%hhu",&v);


    if (v > 10){
        printf("I am not that smart algorithm to count more than 10. I am sorry about that.\n");
        goto _;
    }
    char _b =  (char)(v > 0);
    while (  (_b) ?  v>=0 : v <= 0){
        char* j = intToTextP(v,_b);
        printf("%s %c", j,  ((v == 0) ? 10:32)  );
        (_b) ? v-- : v++;
    }
    return 0;
}
```

### Brief explanation

* `stdio.h` used for printf and scanf functions
* `stdlib.h` used for malloc and free functions
* `intToText` converting positive 0-10 int to the english equilivent
* `intToTextP` converting negative equilivent of `intToText`

## The program that counting the sum of the arithmetic series

```c
#include "stdio.h"


// We can combine also as a one function
int positive(int first,int last,int c){
    int sum = 0;
    while (first <= last){
        sum += first;
        first += c;
    }
    return sum;
}
int negative(int first,int last,int c){
    int sum = 0;
    while(first >= last){
        sum += first;
        first += c;
    }

    return  sum;
}
int main(){
    int first,last,cd;
    printf("give me\nfirst:int last:int common_difference:int\nExample:\n10 0 -1\n0 10 1\n\n$: ");

    scanf("%d %d %d",&first,&last,&cd);
    if ((first == last) || ( first < last && cd <= 0 ) || ( first > last && cd >= 0)) {
        printf("\033[31m>\033[0m I can't do this product.\n");
        return sumOfArth();
    }

    int response = ((  cd > 0 ) ? positive : negative)(first,last,cd);
    printf("$: %d\n",response);
    return 0;
}
```

## Brief explanation

* `negative` to calculate sum of negative common difference
* `positive` to calculate sum of positive common difference


### Do same exercise with other loops

Shortly I changed `negative` and `positive` functions as follows.
```c
int positive(int first,int last,int c){
    int sum = 0;
    
    for(;first <= last;first += c){
        sum += first;
    }
    return sum;
}

int negative(int first,int last,int c){
    int sum = 0;

    do{
        sum += first;
        first += c;
    } while(first >= last);

    return  sum;
}
```
## The program that counting the sum of the geometric series

```c
#include "stdio.h"

int Ppow(int s,int p){
    int l = 1;
    for (int i=0;i<p;i++){
        l *= s;
    }

    return l;
}
// a + a.r + a.r² + a.r³ ... n
// a = initial term
// r = common ratio
// final?
int _sumOfGeo(int init,int final,int cr){
    if (!init || !final || !cr) return 0;
    int total=0;
    for (int i=0;total<=final;i++){
        int _ = init * Ppow(cr,i);
        total += _;
        /*if (_ == final){
                // ?
        }*/
    }
    return total;
}

int main(){
    int init,final,cr;
    printf("give me\ninit:int final:int common_ratio:int\nExample:\n1 10 5\n\n$: ");
    scanf("%d %d %d",&init,&final,&cr);
    int geoalg = _sumOfGeo(init,final,cr);
    printf("What did you wait: ");
    int result;
    scanf("%d",&result);

    printf("Response: %d\n",geoalg);
    printf("Confirm: %s\n", (result == geoalg) ? "TRUE" : "FALSE"  );

}
```

### Brief explanation

* I created `Ppow` function to calculate postive exponential numbers

### Do same exercise with other loops

Shortly I created new functions that who uses other loops.
```c
int _sumOfGeo__while__(int init,int final,int cr){
    if (!init || !final || !cr) return 0;
    int total=0,i=0;
    while(total<final){
        total += init * Ppow(cr,i);
        i++;
    }
}
int _sumOfGeo__dowhile__(int init,int final,int cr){
    if (!init || !final || !cr) return 0;
    int total=0,i=0;
    do{
        total += init * Ppow(cr,i++);
    }
    while(total<final);
}
```
I hope that my algorithm is not wrong.

## Rewrite second exercise with possible shortest time.

I think we should use mathematical formula in here: `S = n/2 * (a + L)`
```c
#include <stdio.h>

int main(){
    int first,last,cd;
    printf("give me\nfirst:int last:int common_difference:int\nExample:\n0 10 1\n\n$: ");

    scanf("%d %d %d",&first,&last,&cd);
    if ((first == last) || ( first < last && cd <= 0 ) || ( first > last && cd >= 0)) {
        printf("\033[31m>\033[0m I can't do this product.\n");
        return -1;
    }
    int res =   (((last-first)/cd)+1) /2 * (first+last);
    printf("result: %d\n",res);
}
```

### Brief explanation

* `n` = total numbers of terms in the sequence. We have to calculate term size of our sequence
* `L` = the last term
* `d` = the common difference
* `a` = the first term
  
## The program that calculating factorial for the range [0,10]
```c
#include "stdio.h"

int calculateFactorial(int num){
    if (!num) return 0;

    int result = 1;

    while(num > 1){
        result *= num;
        num--;
    }
    return  result;
}

int main(){
    int i = 0;
    do{
        printf("Factorial of %d = %d\n",i, calculateFactorial(i));
        i++;
    } while (i < 11 );
}
```

I think all the code is clean for the understand.

## The program that calculating sin(π/3) with Maclaurin formula
```c
#include "stdio.h"

long double _Ppow(double s,int p){
    long double l = 1;
    for (int i=0;i<p;i++){
        l *= s;
    }

    return l;
}
long int _calculateFactorial(int num){
    if (!num) return 0;

    long int result = 1;

    while(num > 1){
        result *= num;
        num--;
    }
    return  result;
}

long double _sincal(double radian,int salt){

    long double result = 0;
    for (int i=0;i<salt;i++){

        // I used these variables to debugging. They are my friends anymore! I can't delete them :)
        long double pow = _Ppow(-1,i);
        long int fact = _calculateFactorial(2*i+1);
        long double xwithpower= _Ppow(radian,2*i+1);

        long double before = pow * xwithpower;
        long int after = fact;

        result += before / fact;
    }

    return  result;
}

int main(){
    double radian = 3.14159265/3; // pi/3

    printf("Calculate power: ");
    int salt;
    scanf("%d",&salt);

    long double res = _sincal(radian,salt);
    printf("result: %Lf\n",res);
    return 0;
}
```

### Brief explanation

* `_Ppow` function used to calculate pozitive power powers.
* `_calculateFactorial` function used to calculate factorial
* I took Both functions from other exercises.
* Maclaurin formula working with radians. So 180/3 (degree) not working -tested- :) 

## The program that calculating π with Leibniz formula
```c
#include "stdio.h"
#include "math.h"

long double leibniz(unsigned long int n){
    long double response = 0;
    for (unsigned long int i=1;i<n;++i){
        printf("> %lu rest (%lu) digit\r",i,(n-i)/10);
        response += ( 1.0 / (double)(  2*i-1  ) ) * pow(-1,(double)(i-1));;
    }
    printf(">>> %lu\n",n);
    return response * 4;
}

long double leibniz_infinity(){
    long double response = 0;
    for (unsigned long int i=1;;++i){
        response += ( 1.0 / (double)(  2*i-1  ) ) * pow(-1,(double)(i-1));;
        printf("π: %.24Lf > loop %lu\r",(response*4),i);
    }
}

int main_safe(){ // for user gived series 
    unsigned long int value;
    printf("Number: ");
    scanf("%lu",&value);
    printf("Leibniz π:  %.23Lf\n", leibniz(value));
    printf("π:          %.23lf\n",M_PI);
}

int main(){
    printf("Press ctrl+c to stop program! [enter]");
    getchar();
    leibniz_infinity();
}
```

### Brief explanation

* My code is using math external code from math.h. This library need some pre-compiled library. So we have to add `-lm` (`libmath`) tag as a compiler parameter.
* `leibniz` function has a limit given by user.
* `leibniz_infinity` function has not a limit. It is infinity.

## The program that calculating positive numbers square root with Newton's formula
```c
#include "stdio.h"

double _newton(int num,int itt){
    int last = 0; // last is our approximating root
    for (int i = 0;i<itt;i++){
        if (i*i > num) break;
        last = i;
    }
    // formula:
    return ( last + ( num / (double)last ) ) / 2.0;
}


int main(){
    int number;
    printf("Number: ");
    scanf("%d",&number);

    int itterative;
    printf("Itterative (exp 100): ");
    scanf("%d",&itterative);


    double answer = _newton(number,itterative);
    printf("Answer: %f\n",answer);
    return 0;
}
```

# Functions

Functions are big part of 'clean code' think. You can split your code as a function. And with that way, you can re-use anytime when you want without type extra code.

## Defination

We can define C language functions with `return_type function_name(paramters){}` format. We have to use brackets here, even our function has a 1 line code. Also we can call that function after the decleration. Note that you should call your function after determine in C language. Otherwise compiler might be convert your code as a 'compilable' but this way is not healty.
```c
void my_awesome_function(void){}
```
`void` means 'Nothing' in C language. This is also a type. Therefore our function returning nothing, and giving nothing as a parameter.
```c
int main(){
    my_awesome_function();
}
```
And we called our function on the above.

## Return values

We can return C language type in function. Even pointer types.
```c
int* give_me_int(){
    int a = 10;
    return &a;
}
```
Also our `a` variable will be deleted automaticly so our return value will be `NULL`. I will mention pointers in [pointer capture](#pointers).

## Calls

Basicly we can call our function with `function_name(parameter_if_exists);` Also if we want to store response -if there is any response- we can declare with variable.
```c
char hello_world(char times){
    do{
        printf("Hello World!\n");
        times--;
    } while(times > 0);

    return 0;
}

int main(){
    if (!hello_world()){
        printf("Oh hello world returned zero!");
    }
}
```
As we can see, we can use function call as a condition part either.

# Local Variables

They are called as `automatic variable`. That mean if you don't declare startup variable while declaration, instead of fixed defination, it will be define something else. In fact local variables don't have fixed values. Remember that we can use local variables only inside their declared scope. 

```c
void function(){
    int _; // something other than 0
    int a = 10;
}

int main(){
    printf("%d",a);  // error: There is no decleration for a
}
```

## static keyword
It is hard for me to explain this keyword. But briefly we can say we are declaring global variable inside of the local scope. `static` is also an `automatic variable`.

```c

void fn(){
    static int counter = 0;
    printf("C: %d %p\n",counter,&counter);
    counter++;
}

void main(){
    fn();
    fn();
}
```
Also counter's inital value is compile time value. So you can't declare variable in runtime. 
```c
// static int counter = some_variable; // error!
```

We are waiting the `0` at every `fn function` call right? But static keyword doing something else. On second `fn function` call, we will see that we have same pointer for counter variable. That means we are increasing exactly same variable. This is why second `fn function` giving us a `1` answer. To be like this, compiler have to don't delete variable even scope ends. Therefore compiler never deletes automaticly decleration which has a `static` keyword.

## register keyword
Inside of the `CPU`, we have `register` compenents. We can think them as a small physical memory which inside of the CPU. CPU does almost everything with these tiny helpers. In C language, we can define variable inside these registers. Probably you have `64bit` CPU and accordingly `64bit` register capacity. With a quick division, we can store `8 byte` variables inside of the this register. Anyway this choise is not exactly ours. Even you add or don't add register keyword into the head of variable decleration, compiler might be ignore your choice and puts variable into normal memory.

```c
static int counter = 0;
```
Also there is no [pointer](#pointers) for the `register` variables and you can't use the `register` keyword with the `static` keyword. Because they are not inside of the memory. :)
 
```c
// printf("%p\n",&counter); //error
```

# Pointers
We can mark our declared variables with `pointers`. They are very import to the programming. Because when program goes to complex, you have to split codes structerly. I mean we can't write everything inside of the main scope. And sometimes we have to manipulate variables with someway. However my explenation will be better with an example. On `64bit` CPU, our pointers occupies `8 bytes` in the memory. As I wrote, these pointers are only marks. They are not exactly variables. 

```c
int value = 10;
int *pointer_value = &value;
```
This 2 line of code occupying `4+8` byte in theory.
```c
unsigned short value=1;
unsigned short *pointer  = &value;

printf("size of real variable: %lu\n",sizeof(value));
printf("size of pointer: %lu\n",sizeof(pointer));
```
Type of `short` occupies only `2 bytes` in the memory. But `pointer` occupying `8 byte`. So at the moment we have more memory usage.

If we change `pointer_value`, `value` will also change.

```c
*pointer_value = 30;
printf("%d\n",value);
```
Actually we are using this change-method in functions.

```c
void process(int* value){
    *value = 10;
}

void main(){
    int v;
    process(&v);
    printf("process: %d\n",v);
}
```
Note that `&` symbol is mean "give memory adress of this variable". So you have to use `&` with variables.
```c
// process(&5); // error
```
At this moment `5` is not a variable. `5` is just `constant` for compiler. Also we can access/modify original variable's value with adding `*` into the head of the pointer variable name. Otherwise it won't change.

## Local Pointers

We can use use and return pointers in local variables. But they wants extra care. Let's say we have we have function and has a int variable. What happening after the end of function? All declared **stack** variables will be delete.

```c
void fn(){
    int var = 10;
}
```
What happens if we return the `var`'s `pointer`?
```c
int *fn(){
    int var = 10;
    return &var;
}
int main(){
    // int *i = fn();  // Same
    printf("%p\n",fn());
}
```
> Output: ``` (nil) ```

Because stack variables were deleted.


# Exercises

## The program that gives biggest number

```c
#include "stdio.h"

int biggest(const int i){
    static int compare = 0;
    if (i > compare){
        compare = i;
    }
    return compare;
}

int readStdIO(){
    int i;
    printf("Digit: ");
    scanf("%d",&i);
    return i;
}

int main(){
    int response = 0;
    for (short i=2;i>=0;i--,response = biggest(readStdIO())){
        // response = biggest(readStdIO()); // unnecessary when i!=0
    }

    printf("Biggest: %d\n",response);
}
```

### Brief explanation
I used `static` keyword to store newest biggest value. At this moment it is causing memory leak because out declared `compare` variable never removing by compiler, at least for this code.

## The program that counts days of week

```c
#include "stdio.h"

struct Day{
    char day[10];
};

const struct Day Days[7] = {"Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"};

struct Day getweek (char day){
    return (day >= 1 && day <= 7) ?Days[day-1] : (struct Day){.day = "Moon"};
}


int week_text(){

    int d;
    printf("day: ");
    scanf("%d",&d);
    struct Day answer = getweek((char)d);
    printf("Answer: %s\n",answer.day);


     week_text();
}
```


### Brief explanation
I used `struct` type in here because we can't return `byte array array` in C language directly. Also `struct` is based of functional programming. However, I declare `Days` array into memory. In this case, usage is very basic.

## The program that counts arithmetic or geometric series sum

```c
#include "stdio.h"
#include "math.h"

int sAr(int num1,int num2,int num3){
    return  (((num2-num1)/num3)+1) /2 * (num1+num2); // :))
}

int sGe(int num1,int num2,int num3){
    int total=0;
    for (int i=0;total<=num2;i++){
        int _ = num1 * pow(num3,i);
        total += _;
    }
    return total;
}

int main(){
    char w;
    int value1,value2,value3;
    start:
    printf("Welcome to calculator\n(G/A) Number Number Number\n: ");
    scanf("%c %d %d %d",&w,&value1,&value2,&value3);
    if (w != 'G' && w != 'A') goto start;

    int raw = ((w == 'G') ? sGe : sAr)(value1,value2,value3) ;
    printf("Answer: %d\n",raw);
}
```


### Brief explanation
I used `math.h` header to use `pow` function. `sAr` function is formula of arithmetic series sum and `sGe` function is calculate of geometric series sum.

## The program that calculates cuboids surface area

```c
#include "stdio.h"

float surface_area(float heigth,float width,float length){
    return 2 * ((heigth*width) + (width*length) + (heigth*length));
}

int main(){
    float value1,value2,value3;
    printf("Welcome to cuboid surface calculator\nHeight Width Length\n: ");
    scanf("%f %f %f",&value1,&value2,&value3);

    printf("> %f\n", surface_area(value1,value2,value3));
    return 0;
}
```


### Brief explanation
Cuboid surface area's mathematical formula $$ sa=2.[(x.y)+(x.z)+(y.z)] $$

## The program that calculates pyramids surface area

```c
#include "stdio.h"
#include "math.h"
#define BASE_DECIMAL 3 // CHANGE TO 4 TO CONVERT PYRAMID TO 4 ANGLE

/*
    top    1
    top-1  3
    1/3*3 = 1 -> 3 3^1
    3*3*1/3 = 3 -> 9 3^2
    3*3*3/1/3 = 9 -> 27 3^3
 */

/*
 * top     1
 * top-1   4 (uses 1/4)
 * top-2   4 * 4 * 1/4 (uses 1/4)
 * top-3   4 * 4 * 4 * 1/4
 */

double surface_cal(double length){  return (length*length)*6; }

int _floor(double length, double height){
    return (int)(height/length);
}

char ensure_true_height(double length,double height){
    return !(height- _floor(length,height)*length); // double mod
}
long double calc_surface(int floor,double length){
    unsigned long long total = 0;
    for(int i=floor;i>=0;i--){
        unsigned long long int count = pow(BASE_DECIMAL,i); // Is it true?
        printf("DEBUG: floor: %d count: %llu\n",floor-i,count);
        total += count;
    }

    return surface_cal(length)  * total ;
}

int main(){
    double length,height;
    printf("length height\n> ");
    scanf("%lf %lf",&length,&height);

    if (!ensure_true_height(length,height)){
        printf("Wrong dimensions!\n");
        return -1;
    }

    printf("Total surface: %Lf\n", calc_surface(_floor(length,height) ,length));
    return 0;
}
```

### Brief explanation
What we should know to solve this exercise
$$ sa = 2.((x.y)+(x.z)+(y.z)) $$
We have cuboid. So all dimensions length will be same.
$$ csa = 2.3.(length.length) $$
This is why I used `length*length*6` in code to calculate surface area. `_floor` function calculating rolled floor. `ensure_true_height` function is doing same job with `%` operator. We can't exactly reach 109cm height with 10cm lengths right? This function checking that dimensions.

## The program that determines pi value with given accuracy

```c
#include "stdio.h"
#include "math.h"

// Nilakantha series -> 4 + (4/2*3*4) - (4/4*5*6) + (4/6*7*8) ..
long double calculate_nilakantha(int accuracy){
    long double total = 0;
    for(int i=0,s = 2;i<accuracy;i++,s+=2){
        total +=  pow(-1,i) * ((long double)4 / (s*(s+1)*(s+2) ));
    }
    return total + 3;
}

int main(){
    int acc = 0;
    printf("Accuracy: ");
    scanf("%d",&acc);

    printf("%d accuracy pi: %.25Lf\n",acc,calculate_nilakantha(acc));
    return 0;
}
```


### Brief explanation
We have several method to calculate pi value. However in this case, I used `Nilakantga Series` to solve this exercise.
$$ pi = 4+\dfrac{4}{2.3.4}-\dfrac4{4.5.6}+\dfrac4{6.7.8}-... $$

## The program that determines the square root value with given digit and accuracy

```c
#include "stdio.h"
#include "math.h"

long double square_root(int digit,int accuracy){
    int last = 0;
    for (int i=1;i<digit;i++){
            if (i*i <= digit) last = i;
            else break;
    }
    if (!last) return -1;
    long double value = 0;
    for (int tenpower=1;tenpower<=(int)(accuracy/10);tenpower++){
        if (value*value == digit) break;
        for (int i=last*pow(accuracy,tenpower);i<(last+1)*pow(accuracy,tenpower) ;i++){
            long double care = i/(long double)accuracy; // I tried to solve floating point math but not worked exactly :)
            if (  care*care <= (long double)digit) value = care;
            else break;
        }
    }
    return value;
}
int main(){
    printf("Digit: ");
    int digit;
    scanf("%d",&digit);

    printf("(\033[31mIt will be power of ten!\033[0m) Accuracy: ");
    int acc;
    scanf("%d",&acc);
    printf("%Lf\n",square_root(digit, pow(10,acc)));
    return 0;
}
```

### Brief explanation
Let's call user input to _digit_. We can determine _digit_'s approximate square root with from 0 to _digit_ with counting. _(We don't need to count to the digit. Nevertheless we can't put constant integer to here)_ We can learn smallest (or equal) than _digit_, most biggest number with that loop. Then we are continue with that most biggest number. Now we can calculate smallest (or equal) than _digit_ number with using same process with float numbers.

## The program that calculates mod with only subtract operation

```c
#include "stdio.h"

int _remainder(int digit1,int digit2){
    int basefactor = 1;
    if (digit1 < 0){
        basefactor*=-1;
        digit1 *= -1;
    }

    if (digit2 < 0){
        basefactor*=-1;
        digit2 *= -1;
    } // Enough for basic calculator :))

    while(digit1 >= digit2){
        digit1 -= digit2;
    } return digit1*basefactor;
}

int main(){ printf("%d",_remainder(10,-4)); }
```

### Brief explanation
I calculated remainder with only use subtract operation.

## The program that takes charapter input from user and checks 'abba' combination

```c
#include "stdio.h"
char checkNAB(char *list){
    for (char i = 0;i<sizeof(*list);i++){
        if (list[i] != 'a' && list[i] != 'b') return 0;
    }

    for(char i = 0;i<7;i++){ // org: sizeof(*list)-4

        if (list[i] == 'a' && list[i+1] == 'b' && list[i+2] == 'b' && list[i+3] == 'a'){
            printf("index: [%d-%d] contains 'abba' combination.\n",i,i+3);
        }
    }
    return 1;
}

int main(){
    printf("Please write something with ab keyboard: ");
    char buf[8]; // enough?
    scanf("%s",buf); // char array is already pointer

    if (!checkNAB(buf)){
        printf("Please use only a and b\n");
        main();
    }
    printf("what: %s",buf);
}
```

### Brief explanation
I used char array instead of take characters by line by line. Then I checked is there any illegal character in char array. Lastly, with the for loop, _(to compare input combination)_ all process is done!


# Arrays

We are using arrays to many of things. They are indispensable for us.

```c
int myAwesomeArray[10];
```

In above `sized array` example, we declared array with 10 initial element. We don't know the above decleration is local or global so we can't say anything about `myAwesomeArray`'s default values. However same rules exists with int global-local declare. If we declare array out of the main function, it will be consist by 0, otherwise it will be something else.

```c
int myAwesomeArray[] = {1,2,3};
```
In above example we declared array with 3 values. This is same thing with first sized array example. But we declared array with values. `myAwesomeArray[3] = {1,2,3}`

## Accessing array elements

```c
int myNotes[] = {5,6,7,1,4}

void main(){
    int myFirstNote = myNotes[0];
    int mySecondNote = myNotes[1];
}
```
As you can see, we are using [<index>] combination to access elements. Also with above example, we learned that computer starts counting from 0.

```c
int myNotes[] = {5,6,7,1,4}

void main(){
    myNotes[3] = 5
}
```
In above contiuned example, we changed `myNotes array`'s `4th` _(index:3)_ element. Also we can use other assigment operators either.

```c
myNotes[3]++;
myNotes[3] += myNotes[2];
```

## Pointers

All arrays points to the pointer. What?

```c
int *pointerNotes;
```
We declared `NULL` array/integer variable. So actually we can use this variable as both types. However we can't declare value to pointer type directly in the C language.

```c
#include <stdio.h>
int buffer = 10;
int *pointerNotes = &buffer;

void main() { printf("%p -> %d\n",pointerNotes,*pointerNotes);  }
```
It will print like `0x7ffe8e20961c -> 10`  to the console. However it is also array.

```c
int main()
{   
    int buf = 10;
    int *list = &buf;
    printf("list: %p %d\n",list,*list);
    
    list[0] = 1;
    printf("list: %p %d\n",list,*list);
}
```
As you can see,we changed our variable with array method.
However we can't declare any variables for other indexes directly

```c
list[1] = 10; // Invalid usage for in this case
```
It will be gave `SIGSEGV` error on unix based systems.

Also we have more fantastic way to set values into the arrays.

### Pointer Arithmetics

```c
int list[10];

*(list+1)  = 10;

*(list+1) += 2; // Legal {*/+-%}

printf(":%d\n",list[1]);
```
We know that arrays points the pointer. So `list+1` is pointer either. With `*` symbol we accesses/modify the original value. You can think this method as "hack the memory". Because this method wrote  values into the ram with custom pointer. It is calling as `pointer arithmetics`. We can add and subtract to the pointer.

```c
*(list+0) = list + sizeof(<TypeOfList>) * 0 // index:0
*(list+1) = list + sizeof(<TypeOfList>) * 1 // index:1
*(list+2) = list + sizeof(<TypeOfList>) * 2 // index:2
...
```
Pointer arithmetics working with this formula.

### Copy and Fill

We have some usefull libraries which called `string.h`. With this library, we can copy or fill arrays (of course with all any others) easily.

```c
#include <string.h>
#include <stdio.h>

void main(){
    int list[] = {1,2,3};
    int list2[3];
    
    memcpy(list2,list,sizeof(list)/sizeof(list[0]));
    
    printf("%d\n",*list2); // 1
}
```
Note that the first variable is the destination, the second is the source and the the last int_n type is length of the values that will be copy.

Also we can fill empty list with `memset` function.

```c
memset(list2,9,2);
```
We saied '`fill first 2 element`' with 9 to the function.

Note that, the function can change the array because the array is pointers themself. This is important.

# Typedef

This is another fantastic keyword in the C language (also in Go language). This keyword allow us to declare our types! We can do something like that with typeof keyword:

```c 
myAwesomeType yeee;
```
In above example we used our imagine type `myAwesomeType` as a declaration type. 

```c
typedef myCustomInt int;
.
.
.

myCustomInt variable = 10;
```
We can create and customize new referenced types like that.

```c
typedef struct MojStruct{
    Age int;
    Year int;
} MojStruct;
```
However above example is not our topic yet. But structs are another life-saver stuff in the C language.

# Enum

Mostly we are using this keyword as a 'you can use this as a option'

```c
enum Numbers{Zero,One,Two,Three,Four,Five};
```
Also they are initially consecutive numbers. `Zero` is really `0`. And `Five` is `5` either. Also we can manipulate this equality.

```c
enum Numbers{Zero,One,Seven=7,Eight};
```

Example application which uses enumators.
```c
#include <stdio.h>
#include <time.h>
#include <stdlib.h>

// Source: https://en.wikipedia.org/wiki/SOCKS#SOCKS4
enum Socks4ConnectionResponse{Granted=510,ROFail,CFail,IFail};

enum Socks4ConnectionResponse ConnectSocks4ProxySimulation(){
    return 510 + (rand() % 5);
}
void main(){
    srand(time(0)); // FEED
    
    switch(ConnectSocks4ProxySimulation()){
        case Granted:
            printf("connected!");
            break;
        case ROFail:
            printf("rejected or failed");
            break;
        case CFail:
            printf("client fail");
            break;
        case IFail:
            printf("client identity failed");
            break;
        default:
            printf("unknown socks4 server response!");
    }
}
```
I will explain what is `rand` function in the next topic.

# Pseudo-Random
A pseudorandom sequence of numbers is one that appears to be statistically random, despite having been produced by a completely deterministic and repeatable process. [Wikipedia]

However we are not jump into that deep. We only want random numbers with somehow.
In the above example, I was used `srand`,`time` and `rand` functions to generate random numbers.
We can use `time` function to get current time. It will return `time_t` type and it takes `time_t pointer` parameter optionally (probably C developers added returned value after the release and they couldn't remove inner parameters after release -because of applications which already using time function with parameter-). However you can use returned value or with parameter pointer. The both will be same. It will return time as a `unix time`. Unix time starts from `1 January 1970`. Anyway this is not our topic yet. We feeded `srand` function with current time. Otherwise the random number will be the same after the all executation. Finally we can call our random number with `rand` function. It returns bigger number than we want. So we shorted this big number with modula operator.

```c
#include <stdio.h>
#include <time.h>
#include <stdlib.h>

int main()
{   
    //srand(time(NULL));
    printf("rand number: %d",rand());
    printf("recall:%d\n",rand());
    printf("recall:%d\n",rand());
    printf("recall:%d\n",rand());

    return 0;
}
```
Without any seed, It will return always the same numbers.

```
rand number: 1804289383
recall:846930886
recall:1681692777
recall:1714636915
recall:1957747793
recall:424238335
```
Well, you can call the above code. It will be same with my output.

After seeding with the unix time, random output will be different:
```
rand number: 2039507104
recall:311727392
recall:1421364319
recall:1523998225
```
By the way, we can use the modula operator with range of from 0 to what we what.
```c
rand() % 8 // -> [0,8)
```
Other ranges can be derive from this formula.

# Exercises

## Enum application

I hope that my example on the enum topic will be enough for this exercise.

```c
#include <stdio.h>
#include <time.h>
#include <stdlib.h>

// Source: https://en.wikipedia.org/wiki/SOCKS#SOCKS4
enum Socks4ConnectionResponse{Granted=510,ROFail,CFail,IFail};

enum Socks4ConnectionResponse ConnectSocks4ProxySimulation(){
    return 510 + (rand() % 5);
}
void main(){
    srand(time(0)); // FEED
    
    switch(ConnectSocks4ProxySimulation()){
        case Granted:
            printf("connected!");
            break;
        case ROFail:
            printf("rejected or failed");
            break;
        case CFail:
            printf("client fail");
            break;
        case IFail:
            printf("client identity failed");
            break;
        default:
            printf("unknown socks4 server response!");
    }
}
```

## Random int array - Calculate the average number

```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#define LIST_SIZE 30

struct fixedListStruct{
    int list[LIST_SIZE];
}; // C is not allowing return list


struct fixedListStruct fillAndGetList(){
    srand(time(0));
    struct fixedListStruct st = {
            {},
    };
    for(int i=0;i<LIST_SIZE; st.list[i++] = (rand()%201)-100); // It will be range -100 100
    return st;
}

void main(){
    struct fixedListStruct calculate = fillAndGetList();
    int avg = 0;
    for (int i = 0;i<LIST_SIZE;i++){
        printf("index: %d value: %d\n",i,calculate.list[i]);
        avg += calculate.list[i];

    }
    printf("Avg: %d\n", (avg/ LIST_SIZE));
}
```

I used `struct` type to return fixed-size array (list) with function.

## Random int array - Do the formula

```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#include <math.h>

#define LIST_SIZE 30

struct fixedListStruct2{
    int list[LIST_SIZE];
}; // C is not allowing return list

struct fixedListStruct2 fillAndGetList2(){
    srand(time(0));
    struct fixedListStruct2 st = {
            {},
    };
    for(int i=0;i<LIST_SIZE; st.list[i++] = (rand()%201)-100); // It will be range -100 100
    return st;
}

long double sq(long double v){
    return v*v;
}

void main(){
    struct fixedListStruct2 getter = fillAndGetList2();
    int total = 0;
    long double product = 0;

    for(int i = 0;i<LIST_SIZE;) {
        total += getter.list[i++];
        product += sq(i- ((long double)total / (i) ) );
    }
    printf("result: %Lf\n", sqrtl((long double)product / LIST_SIZE));
}
```

I used `math.h` to use `sqrt` function which requires `-lm` tag while compilation.

## Random int array - Find max and min values from the array

```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

#define LIST_SIZE 30
struct MaxMin{
    int max;
    int min;
};


struct fixedListStruct3{
    int list[LIST_SIZE];
    struct MaxMin MaxAndMin;
}; // C is not allowing return list

void findAndSetMaxMin(struct fixedListStruct3 *list){
    for(int i=0;i<LIST_SIZE;i++){
        if (list->list[i] > list->MaxAndMin.max) list->MaxAndMin.max=list->list[i];
        else if (list->list[i] < list->MaxAndMin.min) list->MaxAndMin.min=list->list[i];
        // Well, could be better ways
    }
}

struct fixedListStruct3 fillAndGetList3(){
    srand(time(0));
    struct fixedListStruct3 st = {
            {},
            {},
    };
    for(int i=0;i<LIST_SIZE; st.list[i++] = (rand()%201)-100); // It will be range -100 100

    findAndSetMaxMin(&st); // not in correct location! It should be outside of the fillAndGetList3 function because the function's purpose is not separate the max and min.
    return st;
}

void main(){
    struct fixedListStruct3 list = fillAndGetList3();
    for(int i = 0;i<LIST_SIZE;i++){
        printf("value: %d\n",list.list[i]);
    }

    printf("Max: %d Min: %d\n",list.MaxAndMin.max,list.MaxAndMin.min);
}
```

## Random int array - Compare with second and third exercise

```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#include <math.h>

#define LIST_SIZE 30

struct fixedListStruct4{
    int list[LIST_SIZE];
}; // C is not allowing return list

struct fixedListStruct4 fillAndGetList4(){
    srand(time(0));
    struct fixedListStruct4 st = {
            {},
    };
    for(int i=0;i<LIST_SIZE; st.list[i++] = (rand()%201)-100); // It will be range -100 100
    return st;
}

long double calculateAlpha(struct fixedListStruct4 *list){

    long double product = 0;

    for(int i = 0,total = 0;i<LIST_SIZE;) {
        total += list->list[i++];
        product += sq(i- ((long double)total / (i) ) );
    }
   return sqrtl((long double)product / LIST_SIZE);
}

long double calculateAverage(struct fixedListStruct4 *list){
    long double average = 0 ;
    for(int i = 0,total = 0;i<LIST_SIZE;i++) {
        average += list->list[i];
    }

    return average / LIST_SIZE;

}

void main(){
    struct fixedListStruct4 list = fillAndGetList4();
    long double average = calculateAverage(&list);
    long double alpha = calculateAlpha(&list);

    for (int i = 0,buf = 0; i < LIST_SIZE; ++i) {
            buf = list.list[i];
            if (buf > average-alpha || buf > average+alpha) printf("number: %d\n",buf);
    }
}
```

## Array with 4 elements which user takes - Do Horner formula

```c
#include <stdio.h>
#include <stdlib.h>
#include "math.h"

#define LIST_SIZE 4

struct polinamlstuff{
    int list[LIST_SIZE];
    int x;
};

struct polinamlstuff get(){
    struct polinamlstuff p = {{}};
    printf("X:");
    scanf("%d", &p.x);
    for (int i = 0; i < LIST_SIZE; ++i) {
        printf("index: %d value: ",i);
        scanf("%d", &p.list[i]);
    }
    return p;
}

long double hornerFormula(struct polinamlstuff *p){ // We don't want to copy all the variables even temporarily
    long int sum = 0;

    for (int i = 0; i < LIST_SIZE; ++i) {
        sum+= p->list[i] + pow(p->x,LIST_SIZE-i);
    }

    return sum;
}

void main(){
    struct polinamlstuff p = get();
    long int horner = hornerFormula(&p);
    printf("Horner: %ld\n", horner);
}
```

In above and other examples we used pointers variables instead of normal ones. Because they are more cheap than fixed-array variables. They are occupying only 8 bits. Even they are more expensive than normal variables, they are saving us to copy all the variables. So they are efficient.

## Array which filled by user - Take opposite

```c
#include <stdio.h>
#define LIST_SIZE 5

struct oppositestuff{
    int list[LIST_SIZE];
};

struct oppositestuff get2(){
    struct oppositestuff p = {{}};
    for (int i = 0; i < LIST_SIZE; ++i) {
        printf("index: %d value: ",i);
        scanf("%d", &p.list[i]);
    }
    return p;
}

void swap(struct oppositestuff *p,int i,int j){
    int temp = p->list[i];
    p->list[i] = p->list[j];
    p->list[j] = temp;
}

void opposite(struct oppositestuff *p){
    for (int i = 0; i < LIST_SIZE/2; ++i) {
        swap(p,i,LIST_SIZE-i-1);
    }
}

void main(){
    struct oppositestuff list = get2();
    for(int i = 0; i < LIST_SIZE;i++) {
        printf("index: %d value:%d\n",i,list.list[i]);
    }

    printf("Opposite:\n");
    opposite(&list);

    for(int i = 0; i < LIST_SIZE;i++) {
        printf("index: %d value:%d\n",i,list.list[i]);
    }
}
```

We are using buffer value to swap array values.

## Random int array - Half opposite

```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

#define LIST_SIZE 10

struct randomlist{
    int list[LIST_SIZE];
};
struct randomlist create_randomlist(){
    srand(time(NULL));
    struct randomlist randomlist = {{}};
    for(int i = 0; i < LIST_SIZE; i++){
        randomlist.list[i] = rand()%21;
    }
    return randomlist;
}

void print_randomlist(struct randomlist *randomlist){
    for (int i = 0; i < LIST_SIZE; i ++){
        printf("%d ",randomlist->list[i]);
    }
}

void swap_randomlist(struct randomlist *list,int i,int j){
    int temp = list->list[i];
    list->list[i] = list->list[j];
    list->list[j] = temp;
}

void half_opposite_randomlist(struct randomlist *randomlist){
    for (int i = 0; i < LIST_SIZE/2; i++){
        int to= LIST_SIZE/2+i; // Some debug variable
        swap_randomlist(randomlist,i, to);
    }
}

int main(){
    struct randomlist randomlist = create_randomlist();
    print_randomlist(&randomlist);
    half_opposite_randomlist(&randomlist);
    printf("\nhalf_opposite_randomlist:\n");
    print_randomlist(&randomlist);
    return 0;
}
```

# Sorting and binary search

I will mention about sorting selection sort and binary search algorithm to write more fertile softwares in C and exercise solves.
# Sorting
We are using sorted arrays -even we don't know- on everywhere in our daily life. Briefly, they are re-indexing all array values to be regular. There are a lot of sorting algorithms. They could be stable or unstable. They can use one or more extra variables or not. We should choose algorithms depends to our environment. If we are working on embeded or low memory system, we should choose algorithm which uses less memory while sorting. However we will discuss only a algorithm in this part: `Selection Sort`

## Selection Sort
This algorithm scans the array by index by index, unless the end of. While this scanning, it detects the current smallest value and stores that value's index in a variable. After scanning, it is re-indexing that smallest value.

```c
#include <stdio.h>

void swap(int *list,int index1,int index2){
    int temp=list[index1];
    list[index1]=list[index2];
    list[index2]=temp;
    return;
}

int main()
{
    int list[] = {0,1,5,6,4,4,7,8,0,8,60};
    int listsize = sizeof(list)/sizeof(int); 
    for (int i=0;i<listsize;i++){
        int lowest = i;
        for (int j=i+1;j < listsize;j++){
            if (list[j] < list[lowest]){
                lowest = j;
            }
        }
        if (lowest != i){ // lowest is not i anymore; we have really lowest value!
            swap(list,i,lowest);
        }
    }

    for (int i=0;i<listsize;i++){
        printf("%d ",list[i]);
    }
    return 0;
}
```

Also we saw that Selection Sort algorithm using 1 variable while processing on array (Other declarations are not related with the algorithm). It might be take more time than other algorithms.

# Search in sorted arrays
In normal arrays, we don't have much algorithms to search values inside the array. Because they array is not classified. We can't calculate or predict. But if the array is classified with some rule (like our case, sorted array) we can use different algorithms to search values. With this algorithms, we use more less memory, cpu and time. They are important.

## Binary Search

Binary search algorithm takes middle of the array and compares with given number. If the number is greater than the array middle value, it takes left of the array. If the number is smaller than the array middle value, it takes right of the array. And repeats this steps until the middle value is equal to searched number. Well, it can be very useful in the big arrays. But sometimes it can't win the race with traditional counting way. It depends the index. If the searched value is close to the arrays beggining, traditional counting algorithm will be faster than binary search algorithm. However we can't know that, so binary seach will be great choose.

```c

#include <stdio.h>
#include <time.h>
#include <stdlib.h>

int array[] = {1,2,3,4,5,6,7,8,9,10,11,12,13,14,15};
int arraylength = sizeof(array)/sizeof(int);

struct SearchResult{
    int Index;
    int TotalCount;
};


struct SearchResult binary_seach(int search){
    struct SearchResult result;
    
    result.Index = arraylength/2;
    result.TotalCount = 0;
    

    
    int start = 0 ,stop = arraylength-1;
    
    

    for(;array[result.Index] != search; result.Index = (stop-start)/2){
        result.TotalCount++;
        
        if (array[result.Index] > search){
            stop--;
        }else{
            start--;
        }

        if (result.Index >= arraylength || result.Index < 0){
            result.Index = -1; // not exist!
            break;
        }
    }

    return result;
}


struct SearchResult traditional_count_algorithm(int search){
    struct SearchResult result;
    
    result.Index = -1;

    for(int i=0;i<arraylength;i++){
        result.TotalCount++;
        if (array[i] == search){
            result.Index = i;
            result.TotalCount = i;
            break;
        }
    }

    return result;
}

void compare_and_analyz(){
    srand(time(0));

    int binary_search_counter = 0,trditional_count_counter = 0;
    
    for(int i=0;i<1000;i++){
        int search =  rand()%16;

        printf("Search: %d\n", search);

        struct SearchResult result1 = binary_seach(search);
        struct SearchResult result2 = traditional_count_algorithm(search);

        printf("binary-search: %d index: %d\n", result1.TotalCount,result1.Index);
        printf("traditional-s: %d index: %d\n", result2.TotalCount,result2.Index);

        if (result1.TotalCount < result2.TotalCount){
            binary_search_counter++;
        }else{
            trditional_count_counter++;
        }

        printf("\n\nbinary: %d\ntraditional: %d\n",binary_search_counter,trditional_count_counter);
    }
}

void main(){
    compare_and_analyz();
}
```

We will find different results for each executation. Probably binary search algorithm will be more successful.

> Output

```
Search: 0
binary-search: 16 index: -1
traditional-s: 31 index: -1

Search: 1
binary-search: 13 index: 0
traditional-s: 0 index: 0

Search: 0
binary-search: 16 index: -1
traditional-s: 31 index: -1

Search: 1
binary-search: 13 index: 0
traditional-s: 0 index: 0


binary: 626
traditional: 374
```

# Exercises

## Histogram of random array

```c
#include <stdio.h>
#include <stdlib.h>

int initList[30]; 

void fillRandomly(int *list,int max,int size){
    //int size = sizeof(list)/sizeof(int); // we have enough space, better than re-calculating it each time
    
    for(int i=0;i<size;i++){
        list[i] = rand()%max+1;
    }
    return;
}

int *histogram(int *list,int size){
    int *store = malloc(size * sizeof(int)); // not local declaration; default value is zero
    for(int i=0;i<size;i++){
        for(int j=0;j<size;j++){
            if (list[i]  == list[j]){
                store[i]++; // default value is zero; so it is okey
            }
        }
    }

    return store;
}

void main(){
    fillRandomly(initList,10,30);

    for(int i = 0; i < 30; i++){
        printf("%d ",initList[i]);
    }
    puts("\nhistrogram:");

    int *historgramlist = histogram(initList,30);
    for(int i = 0; i < 30; i++){
        printf("%d:%d ",initList[i],historgramlist[i]);
    }
}
```

Well, I don't know histogram consept on C. So I used the repeated histogram to access easily via index.
The above code is using `malloc` to allocate array into memory. So we have to `free` this array after usage.

## Random array sorting

```c
#include <stdio.h>
#include <stdlib.h>

int _initList[30]; 

void _fillRandomly(int *list,int max,int size){    
    for(int i=0;i<size;i++){
        list[i] = rand()%max+1;
    }
    return;
}

void _swap(int *list,int index1,int index2){
    int temp=list[index1];
    list[index1]=list[index2];
    list[index2]=temp;
    return;
}

void _sort(int *list,int size){
    for (int i=0;i<size;i++){
        int lowest = i;
        for (int j=i+1;j < size;j++){
            if (list[j] < list[lowest]){
                lowest = j;
            }
        }
        if (lowest != i){ // lowest is not i anymore; we have really lowest value!
            _swap(list,i,lowest);
        }
    }
}

void main(){
    _fillRandomly(_initList,8,30);

     for(int i = 0; i < 30; i++){
        printf("%d ",_initList[i]);
    }

    _sort(_initList,30);

    puts("\nsorted:");

    for(int i = 0; i < 30; i++){
        printf("%d ",_initList[i]);
    }

}
```

## Random array sorting with counting algorithm

```c
#include "stdio.h"
#include "stdlib.h"
#include "time.h"

int getMaxOfArray(int *array,int size){
    int max = 0;
    for (int i = 0; i < size;i++){
        if (array[i] > max){
            max = array[i];
        }
    }

    return max;
}

void countingSort(int *array,int size){
    
    int max = getMaxOfArray(array,size);
    int *max_array = malloc((max+1)*sizeof(int));
    for(int i = 0;i < size;i++){
        max_array[array[i]]++;
    }
    printf("DEBUG: ");
    for(int i = 0;i<max+1;i++){
        printf("%d:%d ",i,max_array[i]);
    }
    printf("\n"); // flush stdout
    
        
    for(int i = 1;i<max+1;i++){
        max_array[i]+= max_array[i-1];
    }
    printf("DEBUG: ");
    for(int i = 0;i<max+1;i++){
        printf("%d:%d ",i,max_array[i]);
    }
    printf("\n"); // flush

    int output[size];

    for(int i = (size-1);i>=0;i--){
        max_array[array[i]]--;
        output[max_array[array[i]]] = array[i];        
    }

    free(max_array);

    for(int i = 0;i<size;i++){
        array[i] = output[i];
    }

    return;
}

void _fillRandomly_(int *list,int max,int size){
    for(int i=0;i<size;i++){
        list[i] = rand()%max+1;
    }
    return;
}

void main(){
    int array[30];
    _fillRandomly_(array,8,30);
    
    for (int i = 0; i < 30; i++){
        printf("%d ", array[i]);
    }
    printf("\n"); // flush
    
    countingSort(array,30);
    puts("\nsorted:");
    for (int i = 0; i < 30; i++){
        printf("%d ", array[i]);
    }
}
```

Counting sort algorithm is might be more fast than selection sort. However it is using 2 extra array. If we want to sort array in tiny devices, we shouldn't use this algorithm.

## Histogram of random array with range of -5 to 5

```c
#include <stdio.h>
#include <stdlib.h>

int initList[30]; 

// I know that min is always less than zero!
void __fillRandomly(int *list,int min,int max,int size){
    //int size = sizeof(list)/sizeof(int); // we have enough space, better than re-calculating it each time
    
    for(int i=0;i<size;i++){
        list[i] = (rand()%(max+1-min))+min;
    }
    return;
}

int *__histogram(int *list,int size){
    int *store = malloc(size * sizeof(int)); // not local declaration; default value is zero
    for(int i=0;i<size;i++){
        for(int j=0;j<size;j++){
            if (list[i]  == list[j]){
                store[i]++; // default value is zero; so it is okey
            }
        }
    }
    return store;
}

void main(){
    __fillRandomly(initList,-5,5,30);

    for(int i = 0; i < 30; i++){
        printf("%d ",initList[i]);
    }
    puts("\nhistrogram:");

    int *historgramlist = __histogram(initList,30);
    for(int i = 0; i < 30; i++){
        printf("%d:%d ",initList[i],historgramlist[i]);
    }
}
```

## Declare random array, calculate median and find the first and third quartiles

```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int array20[20];


void randomizeTheArray20(){
    srand(time(0));
    for(int i=0;i<20;i++){
        array20[i] = (rand()%9)-4;
    }
}

void sortTheArray20(){
    for (int i=0;i<20;i++){
        int lowest = i;
        for (int j=i+1;j < 20;j++){
            if (array20[j] < array20[lowest]){
                lowest = j;
            }
        }
        if (lowest != i){ // swap
            int temp = array20[i];
            array20[i] = array20[lowest];
            array20[lowest] = temp;
        }
    }
}

int getTheMedianOfTheArray20(){
    if (!(20 % 2)){ // if array is odd
        return array20[20/2];
    }
    return (array20[20/2] + array20[(20/2)+1]) / 2;
}

int *getQuartileOfTheArray20(int whichone){
    int *list = malloc(5*sizeof(int));
    for(int i=(whichone-1)*5; i<whichone*5; i++){        
        list[i-(whichone-1)*5] = array20[i];
    }
    return list;
}

int main(){
    randomizeTheArray20();
    sortTheArray20();


    printf("sorted: ");
    for(int i=0; i<20; i++){
        printf("%d ", array20[i]);
    }
    printf("\n"); // flush

    printf("median: %d\n", getTheMedianOfTheArray20());

        int *firstQuartile = getQuartileOfTheArray20(1);

    printf("quartile1: ");
    for(int i=0; i<5; i++){
        printf("%d ", firstQuartile[i]);
    }
    printf("\n"); // flush


    int *thirdQuartile = getQuartileOfTheArray20(3);

        printf("quartile3: ");
    for(int i=0; i<5; i++){
        printf("%d ", thirdQuartile[i]);
    }
    printf("\n"); // flush

    free(thirdQuartile);
    free(firstQuartile);
}
```

# Strings

We don't have any `String`s in C language.  Every `string` consist by char array. Instead of `String`s, we have `char`s, and `array`s. So they are enough for us to create strings in C language.

```c
char python_developer[] = {'p','r','i','n','t','(','"','H','e','l','l','o',' ','W','o','r','l','d','!','"',')'};
```
This is a string. I know that it is look like a child trying to spell world. Note that we are using single `'` while declare characters.

> `Note from the author:` I didn't type those characters by hand. Here my solving with fish shell:
> `for i in (echo 'print("Hello World!")' | fold -w1); echo -n "'$i',"; end | xclip -selection -c`

Also we can write strings like that

```c
char c_developer[] = "printf(\"Hello World!\\n\");";
```
Both methods are valid and on compile time, C compiler will define fixed-size array for strings. Note that we are using `\` character to disable `\<char>` and `"` actions.

Also `string`s finishes when current character is \0 `(or equievent:0)`.

```c
char python_developer[] = {'p','r','i','n',0,'t','(','"','H','e','l','l','o',' ','W','o','r','l','d','!','"',')'};
char c_developer[] = "printf(\"Hello\0 World!\\n\");";

printf("python_dev says: %s\n",python_developer);
printf("c_dev says: %s\n",c_developer);
```


Also with above example, we saw that we are using `%s` seperator to format `strings` in stdlib. 

## String Operations

We are using `Strings` often in modern softwares. We need some built-in functions to help us while operating the `strings`. Well, C is not the best one but it is providing us to some benefical functions.

### fgets

fgets is not excatly `string` operatation. However, I think it is not problem to add in here.
fgets doing the same thing with scanf function. But it is more secure and practical than the scanf function. It requires array, text size and input source.

```c
#include <stdio.h>
#include <stdlib.h>

int main()
{
    char text[50];
    fgets(text,30,stdin); // max 30 characters
    // Last 20 char will be stay as unchanged local variable
    printf("text: %s\n",text);
}
```

We included the stdio.h header to access and read the stdin. In unix environment, every input is comes from the file system. In our case, our file (stdin) is my xterm console. Stdin is not our topic but it is very important.

In above example, we used char type as a buffer. And we know that is is supporting only ASCII characters. Let's say we want to store some Polish string.

It worked! But why? We don't have enought characters to provide Polish characters. Because C using UTF-8 encoding standard in `Strings`.

### strlen

Let us write the above example with `strlen` function again. `strlen` function returns length of the `string`. 

```c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
    char text[50];
    fgets(text,30,stdin);
    printf("text: %s\n",text);
    printf("strlen: %d\n",strlen(text));
}
```

We suppose to be size of the string is `3`. Because we only typed `3` characters. Also we press the 'ENTER' button to flush data to stdin. So our 4th string char is new line `(Line Feed -LF-)`. Also don't forget the end character `0`. C compiler appends the `0` automatically to the `string` to finish the `string`. We can check that with following example:

```c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
    char text[50] = {1,1,1,1,1};
    fgets(text,30,stdin);
    printf("text: %s\n",text);
    int length_of_text = strlen(text);
    printf("strlen: %d\n",length_of_text);


    for (int i=0;i<length_of_text+1;i++){
        printf("index: %d value: %c-%d\n",i,text[i],text[i]);
    }
}
```

We can see that our 4th char is "`new line`" (`10`). And 5th array value is `0` to finish the `string`. So, we can say that we need least length of 5 array to store `123\n`. Note that: `fgets` function adds `LF` to end of the string automatically. We can use `gets` function instead of the `fgets`. However, `gets` function is not safe.


Let's go back to the Polish example. Know we have all ability to check what is going on.

Everything looking like a normal example 11 and 12th indexes. Also It used 2 characters to provide Polish character. They are UTF-8 characters. Also compiler used 2 characters to provide 1 non-ascii Polish character. This number is not constant but with this example we showed UTF-8 characters might occupy more bytes than ASCII characters. `(1-4) bytes.`

### strcmp

Takes two strings and compares first one with the other one. And returns negative or positive integer. 

```c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
   char str1[] = "helloWorld";
   char str2[] = "HelloWorld";

   printf("strcmp str1,str2: %d\n",strcmp(str1,str2));
}
```

We know that C is not using `ASCII` table while operating `strings`. However, `ASCII` table will help us to imagine how this compare working. 

`strcmp` function compare strings by character by character. For `str1`, first character is "`h`". It is `104` in `ASCII` table. For `str2`, first character is "`H`". It is 72 in ASCII table. Obviously 104 not equels to `72`. For this reason the function returned `104-72` as a answer.

Also we have `strncmp` function which takes external integer to check first integer characters that doing the same thing with the `strcmp` function.

### strcpy

Briefly we are using `strcpy` function to copy from the `str2` to `str1`. It takes `two` `strings`. Also there another version that limits copy characters which called `strncpy`.

```c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
   char str1[] = "helloWorld";
   char str2[] = "987";

   strcpy(str1,str2);

   printf("str1: %s\n",str1);

   strncpy(str1,"123",1);

   printf("str1: %s\n",str1);
}
```

### strcat

Appends two strings from `str2` to `str1`. Also there another version that limits append characters which called `strncat`.

```c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
   char str1[30] = "helloWorld";
   char str2[] = "987";

    strcat(str1,str2);
    printf("new str1: %s\n",str1);
}
```

### atoi

atoi function (comes from stdlib.h) takes a string and try to give integer. It starts from first index to last one. While this process if it is shows any non-number character, it will return what it have heretofore.

```c
#include <stdio.h>
#include <stdlib.h>

int main()
{
    a_p("1"); // 1
    a_p("0"); // 0
    a_p(" 100"); // 100
    a_p("56K"); // 56
    a_p("none123"); // 0
}

void a_p(char *text){
    printf("%s -> %d\n",text,atoi(text));
}
```

### strstr

This function takes two strings and gaves us a second strings location point in the first strings. If second string is not inside of the first string, it returns NULL. My personal opinion is strstr function is useless. Why it is returning pointer instead of the index?

```c
#include <stdio.h>
#include <string.h>

int main () {
   const char haystack[20] = "HelloWorld";
   const char needle[10] = "World";
   printf("strstr: %s\n", strstr(haystack, needle)); // World 
}

```

### strtok

We are using this function to split our string with our characters.

```c
#include <stdio.h>
#include <string.h>
#define splitter ",\n"

typedef struct CSVDATA{
    char *value
} CSVDATA;

typedef CSVDATA CSVROW[3];

int main()
{
    char csv_data[] = "name,id,note\nabc,123,10\nqweqwe,998,6.5";
    char *res = strtok(csv_data,splitter);

    CSVROW rows[3];
    // first row is header row

    int counter = 0, index= 0;

    while(res != NULL){
        //printf("splitted: %s\n",res);
        rows[index][counter].value =  res;

        if (counter++ == 2){
                counter = 0;
                index++;
        }

        res=strtok(NULL,splitter);
    }

    for (int i=1;i<3;i++){
        printf("%d: ",i);
        for (int j=0;j<3;j++){
            printf("%s:%s ",rows[0][j].value,rows[i][j].value);
        }
        printf("\n"); // flush
    }
}
```

`Strtok` uses `static` decleration inside. Valid usage is feed the base string one, and call without base string as long as return value is not NULL. Actually It is very benefical but we have to be careful when using asynchronous (multithread) programming. Also the other point is we have to use heap allocation when we want to return `CSWROW`. Also we can use different index & counter algorithm to deploy program without external int variable. Also I used some topics (`struct`, `multiset`) to our next laboratories.

# Exercises

## Check if the given string is palindrome

```c
#include "stdlib.h"
#include <string.h>
#include "stdio.h"

char *convert_to_reverse(char *str,char *new){ // I will use same function for the other exercises
    size_t len = strlen(str);    
    for(int i = 0;i<len;i++){
        new[i] = str[len-i-1];
    }
    return new;
}

int main(){
    char buffer[100] ;
    char reversed[100];

    fgets(buffer,100,stdin);// Note that fgets includes the LF (new line) into the string buffer.
    if (buffer[strlen(buffer)-1] == 10){
        buffer[strlen(buffer)-1] = 0;
    }; 
    // Also it broke all my plan :) // strcmp(fgets(),convert_to_reverse())
    
    
    if (strcmp(buffer,convert_to_reverse(buffer,reversed))){
        printf("given word (%s) is NOT palindrome!\n",buffer);
        return -1;
    }

    printf("given word (%s) is palindrome!\n",buffer);
}
```

I used to `convert_to_reverse` function to convert the char as reverse. It requires two char arrays. First one is array to convert and the second one is the array to store the converted array. 

## Check if the given strings are anagram

```c
#include <stdio.h>
#include "string.h"

char check_is_anagram(char *base,char *target){
        char is_contains = 0;
        for (int i=strlen(target)-1; i>=0; i--){ // last char is always 0
            is_contains = 0;
            for(int j=strlen(base)-1; j>=0;j--){ // last char is always 0
                
            if (base[j] == target[i]){
                
                is_contains = 1;
                break;
                }
            }
            if (!is_contains) break;
        }
        return is_contains;
}

void main(){
    char buffer[100];
    char target[100];
    printf("base: ");
    scanf("%s",buffer);

    printf("target: ");
    scanf("%s",target);

    printf("is_anagram: %s\n",( (check_is_anagram(buffer,target)) ? "TRUE":"FALSE" ));

}
```

We have two different strings in our case. And we want to check is second string contains only first string's characters. We can type different algorithms but it is also enough.



## The program that takes real number with coma, and prints again with coma

```c
#include "string.h"
#include "stdio.h"
#include "stdlib.h"

int find_index(const char *list,const char character,int start,int end){
    for (;start<end;start++){
        if (list[start]==character){
            return start;
        }
    }
    return -1;
}

double take_real_number_with_coma(){
    char buffer[10];
    scanf("%s", buffer);

    for (int i = 0; i < sizeof(buffer)/sizeof(char);i++){
        if (buffer[i] == ','){
            buffer[i] = '.';
        }
    }    
    
    return atof(buffer); // similar to atoi
}

void print_result(double result){
    char buffer[20];
    sprintf(buffer, "%lf", result);
    int index = find_index(buffer, '.', 0, 20);
    buffer[index] = ',';
    printf("%s\n", buffer);
}

void main(){
    printf("Enter a number: ");
    print_result(take_real_number_with_coma()+0.001);
}
```

I used `atof` function to convert `string` to `double` number. However I didn't like my algorithm.



## The program that re-indexes the sentence

```c
#include "stdio.h"
#include "string.h"
#include "stdlib.h"

typedef struct Word{
    char *word; // Not good choose
} Word;

void *convert_reverse_words_print(char *sentence){
    
    char wordscounter = 0;
    for (int i = 0; i < strlen(sentence)-1; i++){
        if (sentence[i] == 32){
            wordscounter++;
        }
    }
    
    Word *words =(Word*)malloc((wordscounter+1)*sizeof(Word));
    
    char *v = strtok(sentence," ");
    char start = 0;
    while(v){
        words[start++].word = v;
        v = strtok(0," ");
    }
    for (int i = start-1; i >= 0; i--){
        printf("%s ",words[i].word);
    }
    printf("\n"); // flush
    
    free(words);
}

void deletenewline(char *text){
    text[strlen(text)-1] = 0;
}

void main(){
    char buffer[100];
    printf("sentence: ");
    fgets(buffer,100,stdin);
    deletenewline(buffer);
    convert_reverse_words_print(buffer);
}
```
Well, program is working but the algorithm is very bad. It is using unnecessary extra variables with could be very big sized. My opinion is this algorithm is not good choose for the real life application.

Also we can do the same thing with 'reverse counting' and character control. It would be much better :) 


## The program that doing find and replace

```c
#include "stdio.h"
#include "stdlib.h"
#include "string.h"

typedef struct Index{
    int start;
    int stop;
} Index;

Index find_index(const char *text,const char *search){
    int searchsize = strlen(search);
    int textlength = strlen(text);
    int searchindex = 0;
    Index response = {-1,-1};
    for(int i = 0; i < textlength;i++){
        if (i+(searchsize-searchindex) > textlength){
            return response; // not possible to match
        }

        if (search[searchindex] != text[i]){
            searchindex = 0;
            response.start = -1;
            response.stop = -1;
            continue;
        }
        
        if (searchindex++ == 0){
            response.start = i;

        }


        if (searchindex == searchsize){
            response.stop = i+1; // i < stop
            break;
        }

    }

    return response;
}



char *find_and_replace(const char *text,const char *search,const char *replace,char *output){
    int size = strlen(text)-strlen(search)+strlen(replace);
    // if (size >= sizeof(output)/sizeof(char)){
    //         return text; // not possible to fit!  
    //         // >= because also we have to add 0 on the end of the string
            
    // } // It is not working. sizeof function returning size of the pointer. Not array's itself. So we can't control the size.
    Index index = find_index(text,search);
    if (index.start == -1 || index.stop == -1){
        return output;
    }

    int replacelength = strlen(replace);
    int searchlength = strlen(search);

    for(int i = 0, rplc = 0;i<size;i++){
        if (i >= index.start && rplc < replacelength){
                output[i] = replace[rplc++];
                //printf("out: %s char: %c char-d: %d i:%d\n",output,replace[rplc-1],replace[rplc-1],i);
                size++;
                continue;   
        }
            output[i] = text[i-(( !rplc ) ? 0 : (replacelength-searchlength)) ];   
    }
    return output;
} // It took my 4 hour. But I am not regret. It is so beautiful :)

void main(){

   char text[50];
   char search[20];
   char replace[50];
   
   char output[100];
   
   printf("text: ");
   gets(text);

   printf("search: ");
   gets(search);

   printf("replace: ");
   gets(replace);

   printf("> %s\n",find_and_replace(text,search,replace,output) );
}
```

I think we have a lot of topic to talk about in this exercise solve. It took my 4 hour. But it is totally memory safe, and very basic to understand. Briefly, It is working with "changing indexes". I used `find_index` to find start and stop indexes. I think `strstr` function is useless in here too.
Then it is goes to iteration loop, changes all what it need. And done! It is my favorite exercise.



## The program that splitting the URL scheme

```c
#include <stdlib.h>
#include <string.h>
#include <stdio.h>

typedef struct Index{
    int start;
    int stop;
} Index;

Index find_index(const char *text,const char *search){
    int searchsize = strlen(search);
    int textlength = strlen(text);
    int searchindex = 0;
    Index response = {-1,-1};
    for(int i = 0; i < textlength;i++){
        if (i+(searchsize-searchindex) > textlength){
            return response; // not possible to match
        }

        if (search[searchindex] != text[i]){
            searchindex = 0;
            response.start = -1;
            response.stop = -1;
            continue;
        }
        
        if (searchindex++ == 0){
            response.start = i;

        }


        if (searchindex == searchsize){
            response.stop = i+1; // i < stop
            break;
        }

    }

    return response;
} // Coming from exercise 5

char is_valid_url(char *url){
    Index index = find_index(url, "://"); // It can be ftp:// tcp:// unix:// etc. They are all URL 
    return (index.start != -1 && index.stop != -1);
}

char *split_scheme_from_url(char *url,char *output){
    Index index = find_index(url, "://"); // It is not good for do not repeat yourself. However, I will use
    char _tmpbuffer[index.start]; // It could be unnecessary
    // Also It might be not work C99 standard. In this case, we can change output without truncate 
    
    for(int i = 0;i < index.start;i++){
        _tmpbuffer[i] = url[i];
    }
    _tmpbuffer[index.start] = 0; // EOS
    strcpy(output, _tmpbuffer); // To truncate the string
    return output;
}


void main(){
    char buffer[100];
    printf("URL: ");
    gets(buffer);
    if (is_valid_url(buffer)){
        printf("SCHEME (PROTOCOL): %s\n",split_scheme_from_url(buffer,buffer)); // This usage is valid
        // After the split_scheme_from_url call, buffer will change. So be careful while using the same array object.
    }else{
        printf("%s is not valid URL!\n",buffer);
    }
}
```
We have a lot of url schemes. They are not limited with only http or https. For this reason, our keyword is "`://`". If we can handle this keyword, rest is very easy. I used `find_index` function which coming from latest exercise. It returns `Index struct` with `start`, and `stop` indexes. We don't care `stop` index. We need only `start`. 

  
# Arrays

We are using arrays to store multiple elements in a variable. They are very beneficial and indispensable elements of programming.

```c
int array1[] = {1,2,3,4,5};
int array2[5] = {1,2,3,4,5};
```

We declared 2 arrays. For people, they are same. Actually, they are really same. Both are store 5 elements and starting from 1 to 5.
But computer can't know are they same. Arrays are not comparable items. We can't do something like that:

```c
// if (array1 == array2){ ... }
```

This code is not legal. Can we compare elements of arrays? Yes, of course!

```c
if (array1[0] == array2[0])
```

Also pointer arithmetic is valid. But IDE language-server might be not welcome this action.

```c
if (*(array1+1) == *(array2+1)){
    printf("Hurraaa!");
}
```

## Multidimensional Arrays

We know how to declare normal arrays. It is pretty simple. But we can also declare arrays inside on the arrays.

```c
int array[3][4];
```

We declared 3 elements in array. And those elements are array with 4 elements. 

```c
int array[][] = {
    {0,1,2,3},
    {4,5,6,7},
    {8,9,10,11}
};
```

They are same declaration. Also we can use those arrays like normal arrays.


```c

array[0]; // Gaves array pointer
array[2]; // Gaves array pointer

array[0][0]; // gaves int:0
array[1][3]; // gaves int:7

```

Let's think about this sentence. It is Containing five elements (words). We can declare this sentence in C with multidimensional array:

```c

char myReportSentence[][8] = {
       "Let's",
       "think",
       "about",
       "this",
       "sentence",
   };
   
printf("last word: %s\n",myReportSentence[4]);

```

We have to set inner array length. Compiler not provides this length automatically to use unlike outer array length.
Unfortunately char multidimensional array is not `String`. So we can't just print `myReportSentence` array directly.

```c
// printf("sentence: %s\n", myReportSentence);
```

Also we can't return any array in function directly.

```c

char *getString(){
    char array[] = "Hello World!";
    return array;
}

```

The above code is valid for C compiler. But array `array` declared in `stack`. That means the all variables will be deleted automatically after the end of the function call. So, our array `array` will be undefined. This is why we can't return directly arrays. However, we can store array into the `heap` memory. Keyword is 'allocating' but not our topic yet.

# Exercises

## Multiple random which filled 4x3 array with user given scaler

```c
#include "stdio.h"
#include "stdlib.h"
#include "time.h"
#define ROW 4
#define COLUMN 3

double getRandomDoubleInRange(){
 // rand is not enough to provide random numbers
    return (rand()/(double)RAND_MAX) * (double)((rand() % 23)-11);
}

void fillMatrix(char array[ROW][COLUMN]){
    srand(time(0)); // feed
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            array[i][j] = getRandomDoubleInRange();
        }
    }
}

void printMatrix(char array[ROW][COLUMN]){
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            printf("%d ",array[i][j]);
        }
        puts("");
    }
    
}


void multiplicationMatrix(int scaler,char matrix[ROW][COLUMN]){
        for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            matrix[i][j]*=scaler;
        }
    }
}

int main(){
    char array[ROW][COLUMN];
    fillMatrix(array);
    printf("Matrix:\n");
    printMatrix(array);

    printf("Please give me a scaler: ");
    int scaler;
    scanf("%d", &scaler);
    multiplicationMatrix(scaler, array);
    printf("Result Matrix:\n");
    printMatrix(array);
}
```
### Memo

I used (`double` `rand()` divided by `RAND_MAX`) which is providing by `stdlib.h` to get double number in range 0-1. Also `srand(time(0))` not good choice to feed pseudo-random number. If we use srand function in `getRandomDoubleInRange` function, it will return same numbers again and again. Because C is incredibly fast with modern hardware.

## Find biggest and lowest values in 3x4 random filled matrix

```c
#include "stdio.h"
#include "stdlib.h"
#include "time.h"
#define ROW 3
#define COLUMN 4

int getRandomInRange(){
    return ((rand() % 11)-5);
}

void fillMatrix(char array[ROW][COLUMN]){
    srand(time(0)); // feed
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            array[i][j] = getRandomInRange();
        }
    }
}

void printMatrix(char array[ROW][COLUMN]){
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            printf("%d ",array[i][j]);
        }
        puts("");
    }   
}

typedef struct{
    int biggest;
    int lowest;
} Est;

Est findEstesMatrix(char matrix[ROW][COLUMN]){
    Est est; // local variable
    est.biggest = matrix[0][0];
    est.lowest = matrix[0][0];
     for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            if (matrix[i][j] > est.biggest) est.biggest = matrix[i][j];
            else if (matrix[i][j] < est.lowest) est.lowest = matrix[i][j];
        }
    }   

    return est;     }

int main(){
    char array[ROW][COLUMN];
    fillMatrix(array);
    printf("Matrix:\n");
    printMatrix(array);

    Est est = findEstesMatrix(array);
    printf("Biggest value of matrix is %d\n",est.biggest);
    printf("Lowest value of matrix is %d\n",est.lowest);
}

```

### Memo

I used `struct` type to return biggest and lowest values. Also in `findEstesMatrix` function, I used matrix's 0.0 indexes to init `struct` declaration. Otherwise, It will be filled automatically with something unexpected. Because it is local declaration. Also I can't use 0 as a initial value, because all matrix elements might be bigger than 0. In this case, function will return 0 as lowest value which is definitely wrong!

## Fill the matrix with random values than sort the matrix

```c
#include "stdio.h"
#include "stdlib.h"
#include "time.h"
#define ROW 4
#define COLUMN 4

int getRandomInRange(){
    return ((rand() % 21)-10);
}

void fillMatrix(char array[ROW][COLUMN]){
    srand(time(0)); // feed
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            array[i][j] = getRandomInRange();
        }
    }
}

void printMatrix(char array[ROW][COLUMN]){
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            printf("%d ",array[i][j]);
        }
        puts("");
    }   
}

void swapMatrix(char array[ROW][COLUMN],int v1i,int v1j,int v2i,int v2j){
    int temp = array[v1i][v1j];
    array[v1i][v1j] = array[v2i][v2j];
    array[v2i][v2j] = temp;
}

// selection sort
void sortMatrix(char array[ROW][COLUMN]){

    for(int b = 0; b < ROW*COLUMN; b++){
        int lowestiindex = b/4;
        int lowestjindex = b%4;

        for (int d = b;d < ROW*COLUMN; d++){
            if (array[d/4][d%4] < array[lowestiindex][lowestjindex]){
                lowestiindex = d/4;
                lowestjindex = d%4;
            } 
        }
        swapMatrix(array,b/4,b%4,lowestiindex,lowestjindex);
    }
}

void main(){
    char array[ROW][COLUMN];
    fillMatrix(array);
    printf("Matrix:\n");
    printMatrix(array);

    sortMatrix(array);

    printf("Sorted Matrix:\n");
    printMatrix(array);
}
```

### Memo

I used selection sort algorithm to sort the matrix. Briefly the algorithm is addressing the matrix like an array.



## Fill 4x4 matrix randomly and get sum of rows and columns

```c
#include "stdio.h"
#include "stdlib.h"
#include "time.h"
#define ROW 4
#define COLUMN 4

int getRandomInRange(){
 // rand is not enough to provide random numbers
    return ((rand() % 21)-10);
}

void fillMatrix(char array[ROW][COLUMN]){
    srand(time(0)); // feed
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            array[i][j] = getRandomInRange();
        }
    }
}

void printMatrix(char array[ROW][COLUMN]){
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            printf("%d ",array[i][j]);
        }
        puts("");
    }   
}

int getSumOfMatrixAlone(char array[ROW][COLUMN],char row, char column){
    int sum = 0;
    for (int i = 0; i < ROW; i++){
        if (row >= 0 && i != row){
            continue;
        }
        for(int j = 0; j < COLUMN; j++){
            if (column >= 0 && j == column || row >= 0){
                sum+=array[i][j];
            }
        }
    }
    return sum;

}

void _print_well(int value){
    printf("%s%d%s", ((value < 0) ? " ":"  "),value,(value >= 10 || value <= -10) ? "":" ");
}

void printWithSumMatrix(char array[ROW][COLUMN]){
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            //printf("%s%d ",((i > 0 && array[i-1][j] < 0 && array[i][j] >= 0)?" ":""),  array[i][j]);
            _print_well(array[i][j]);
        }
        printf(" |+= %d\n",getSumOfMatrixAlone(array,i,-1));
    }
    printf("+-----------------\n");
    for(int i = 0; i < COLUMN; i++){
        _print_well(getSumOfMatrixAlone(array,-1,i));
    }
    puts("");
}

void main(){
    char array[ROW][COLUMN];
    fillMatrix(array);
    printf("Matrix:\n");
    printMatrix(array);

    puts("Sum of Matrix:");

    printWithSumMatrix(array);

}
```

## Fill 5x5 matrix with random numbers and compare diagonal sum with counter diagonal sum

```c
#include "stdio.h"
#include "stdlib.h"
#include "time.h"
#define ROW 5
#define COLUMN 5

int getRandomInRange(){
    return ((rand() % 20)+6);
}

void fillMatrix(char array[ROW][COLUMN]){
    srand(time(0)); // feed
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            array[i][j] = getRandomInRange();
        }
    }
}

void _print_well(int value){printf("%s\033[32m%d\033[0m%s", ((value < 0) ? " ":"  "),value,(value >= 10 || value <= -10) ? "":" ");}

void printMatrix(char array[ROW][COLUMN]){
    printf("   ");
    for(int i = 0; i < COLUMN; i++){
        _print_well(i);
    }
    printf("\n  _____________________\n");
    for(int i = 0; i < ROW; i++){
        printf("%d| ",i);
        for (int j = 0; j < COLUMN; j++){
            _print_well(array[i][j]);
            printf(" %d:%d ",i,j);
        }
        puts("");
    }   
}

typedef struct{
    int diagonal;
    int counterdiagonal;
} Sum;

Sum getSums(char matrix[ROW][COLUMN]){
    Sum su = {.diagonal = 0, .counterdiagonal = 0};
   
    for(int i = 0;i < ROW;i++){
        // if (i > COLUMN-1){
        //     continue; 
        // } // Square matrix is ok.
        su.diagonal += matrix[i][i];
        
        // for(int j = 0,b=i; j < ROW && b >= 0; j++,b--){
        //     printf("\033[33m%d\033[0m ",matrix[b][j]);

        //     su.counterdiagonal += matrix[b][j];
            
        //     if (i < ROW-1){
        //         su.counterdiagonal += matrix[ROW-b-1][ROW-j-1]; // reverse order
        //         printf("=> \033[31m%d\033[0m ",matrix[ROW-b-1][ROW-j-1]);}
        // }
        // printf("\n"); // They are for all matrix rows and columns!

        su.counterdiagonal += matrix[i][ROW-i-1];
    }
    return su;
}

void main(){
    char array[ROW][COLUMN];
    fillMatrix(array);
    printf("Matrix:\n");
    printMatrix(array);

    Sum sums = getSums(array);
    printf("diagonal sum: %d\ncounter-diagonal sum: %d\n\n", sums.diagonal, sums.counterdiagonal);

    printf("Diff(cd-d): %d\n",sums.counterdiagonal-sums.diagonal);
}
```

### Memo

I declare `GetSums` function to get sums of diagonal and counter diagonal matrix but it also debugging. So the function is not just doing it's job. Not for production. Also I wrote algorithm to calculate all counterdiagonal values. You can see in commented code.



## Fill 5x5 matrix and reverse order the diagonal

```c
#include "stdio.h"
#include "stdlib.h"
#include "time.h"
#define ROW 5
#define COLUMN 5

int getRandomInRange(){
    return (rand() % 16);
}

void fillMatrix(char array[ROW][COLUMN]){
    srand(time(0)); // feed
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            array[i][j] = getRandomInRange();
        }
    }
}

void _print_well(int value){printf("%s%d%s", ((value < 0) ? " ":"  "),value,(value >= 10 || value <= -10) ? "":" ");}

void printMatrix(char array[ROW][COLUMN]){
    printf("   ");
    for(int i = 0; i < COLUMN; i++){
        _print_well(i);
    }
    printf("\n  _____________________\n");
    for(int i = 0; i < ROW; i++){
        printf("%d| ",i);
        for (int j = 0; j < COLUMN; j++){
            if (j == i) printf("\033[33m");
            _print_well(array[i][j]);
            if (j == i) printf("\033[0m");


        }
        puts("");
    }   
}


void swapMatrix(char array[ROW][COLUMN],int v1i,int v1j,int v2i,int v2j){
    int temp = array[v1i][v1j];
    array[v1i][v1j] = array[v2i][v2j];
    array[v2i][v2j] = temp;
}

void reverseDiagonalMatrix(char matrix[ROW][COLUMN]){
    for (int i = 0; i < ROW/2;i++){
        swapMatrix(matrix,i,i,ROW-1-i,ROW-1-i);
    }
}

void main(){
    char array[ROW][COLUMN];
    fillMatrix(array);
    printf("Matrix:\n");
    printMatrix(array);
    reverseDiagonalMatrix(array);

    printf("\nReverse Order Diagonal Matrix:\n");
    printMatrix(array);
}
```


## Do the same thing with counter diagonal matrix

```c
#include "stdio.h"
#include "stdlib.h"
#include "time.h"
#define ROW 5
#define COLUMN 5

int getRandomInRange(){
    return (rand() % 16);
}

void fillMatrix(char array[ROW][COLUMN]){
    srand(time(0)); // feed
    for(int i = 0; i < ROW; i++){
        for (int j = 0; j < COLUMN; j++){
            array[i][j] = getRandomInRange();
        }
    }
}

void _print_well(int value){printf("%s%d%s", ((value < 0) ? " ":"  "),value,(value >= 10 || value <= -10) ? "":" ");}

void printMatrix(char array[ROW][COLUMN]){
    printf("   ");
    for(int i = 0; i < COLUMN; i++){
        _print_well(i);
    }
    printf("\n  _____________________\n");
    for(int i = 0; i < ROW; i++){
        printf("%d| ",i);
        for (int j = 0; j < COLUMN; j++){
            if (i+j == 4) printf("\033[33m");
            _print_well(array[i][j]);
            if (i+j == 4) printf("\033[0m");


        }
        puts("");
    }   
}


void swapMatrix(char array[ROW][COLUMN],int v1i,int v1j,int v2i,int v2j){
    int temp = array[v1i][v1j];
    array[v1i][v1j] = array[v2i][v2j];
    array[v2i][v2j] = temp;
}

void reverseCounterDiagonalMatrix(char matrix[ROW][COLUMN]){
    for (int i = 0; i < ROW/2;i++){
        swapMatrix(matrix,i,COLUMN-1-i,ROW-1-i,i);
    }
}

void main(){
    char array[ROW][COLUMN];
    fillMatrix(array);
    printf("Matrix:\n");
    printMatrix(array);
    reverseCounterDiagonalMatrix(array);

    printf("\nReverse Order Diagonal Matrix:\n");
    printMatrix(array);
}
```

## Do the same thing with using both

I changed only following functions to provide this exercise.

```c
void reverseBothMatrix(char matrix[ROW][COLUMN]){
    for (int i = 0; i < ROW/2;i++){
        swapMatrix(matrix,i,COLUMN-1-i,ROW-1-i,i);
        swapMatrix(matrix,i,i,ROW-1-i,ROW-1-i);
    }
}

void printMatrix(char array[ROW][COLUMN]){
    printf("   ");
    for(int i = 0; i < COLUMN; i++){
        _print_well(i);
    }
    printf("\n  _____________________\n");
    for(int i = 0; i < ROW; i++){
        printf("%d| ",i);
        for (int j = 0; j < COLUMN; j++){
            if (i == 2 && j == 2) printf("\033[31m");
            else if (i+j == 4) printf("\033[33m");
            else if(i == j) printf("\033[34m");
            _print_well(array[i][j]);
            if (i+j == 4 || i == j) printf("\033[0m");


        }
        puts("");
    }   
}
```


## The program that takes 10 words from user and prints the longest one

```c
#include "stdio.h"
#include "string.h"

void getInput(char array[10][30]){
    char buffer[300];
    scanf("%[^\n]",buffer);
    char *word = strtok(buffer," ");
    for(int i = 0;word != NULL && i < 10; word = strtok(NULL," "), i++) {
            strcpy(array[i],word);
    }
}

char *getBiggest(char sentence[10][30]){
    int index = 0;
    for (int i = 0; i < 10; i++){
        if (strlen(sentence[i]) >  strlen(sentence[index])){
            index = i;
        }
    }
    return sentence[index];
}

void main(){

    printf("Sentence: ");
    char sentence[10][30];
    getInput(sentence);

    char *longest = getBiggest(sentence);
    printf("longest word: %s\n",longest);
}
```

# Structures

In C language, we are using `struct`s to represent variables with only one element. Use case are not narrow with only storing elements.
They can initialize with types or empty.

```c
struct Student{
    char *Name;
    char *Surname;
    unsigned int Id;
};
```

In above example, we declared a `struct` which name is `Student`. However, this declaration is not variable. We created just a new type.

```c
struct Student John;
```

Now, `John` is a variable which freely changeable. 

```c
char name[] = "John";

John.Name = name;
John.Surname = "Turker";
```

We can change `Name` and `Surname` like the above example.

```c
struct Student john = {.Id = 10, .Name = "john"};
```
This usage is also legal. I think this usage is more convenient.

Also we can declare Student struct and John in the same line

```c
struct Student{
    char *Name;
    char *Surname;
    unsigned int Id;
} John;
```


## Size of Structers

We can use `sizeof` function to find the size of the `struct`.

```c
#include <stdio.h>

struct Student{
    
    char *Name;
    char *Surname;
} Variable;

int main()
{
    printf("Sizeof(Variable): %lu\n",sizeof(Variable)); // Sizeof(Variable): 16
}
```

It gave us to 16 byte output. Note that in C language -with 64bit processor-, pointers occupies 8bytes in memory. We stored 2 pointers in struct, so size of struct is 16. With that example we saw that there is no size for empty struct.
Let's try to add another types into our `struct Student`.

```c
#include <stdio.h>

struct Student{
    
    char *Name;
    char *Surname;
    unsigned Id;


} Variable;

int main()
{
    printf("Sizeof(Variable): %lu\n",sizeof(Variable)); // Sizeof(Variable): 24
}
```

We know that size of unsigned int (unsigned shortly) is 4 bytes. But sizeof function saying size of Student is 24 bytes. Maybe we really don't know what is the size of unsigned. Let's check

```c
printf("Sizeof(Variable.Id): %lu\n",sizeof(Variable.Id)); // Sizeof(Variable): 4
```

We proofed that unsigned type is 4 bytes. What happened to us is that we saw 24 bytes instead of 20 bytes?

Answer is 'padding'. Briefly, C compiler adding padding bytes to synchronize lowest bytes to biggest type's size.

```c
struct Student{
    
    char *Name; // 8
    char *Surname; // 8
    unsigned Id; // 4
    char _padding[4]; // simulation to what compiler doing automatically: 4
} // Sizeof(Student): 24
```

Also we can add another type of variable instead of padding. 

```c
struct Student{
    
    char *Name; // 8
    char *Surname; // 8
    unsigned Id; // 4
    unsigned Other; // 4
} John; // Sizeof(John): 24
```
As you can see, they are same size!

Not related note with C: `We are using struct-reindexing in Golang to solve this auto 'padding' act.`
Also it can be `packable` with `#pragma pack(push,1)` header tag. And you can disable this feature with `#pragma pack(pop)`. They are compile-time properties which provided by compiler.

This topic is very important and definitely it is deserving more time. However, not our topic *yet*.

## Accessing struct values from pointer

We have to use pointers when we want to change struct variables with function. Otherwise function just copies struct's it self and changes only as a local variable.

```c
void readValues(struct Student s){
    printf("name: %s\n", s.Name);
}
```

Again. We don't have any problem with reading. However when we want to change struct variable;

```c
void changeValues(struct Student s){
    s.Name = "changed";
}
```
Usage is legal. But variable of `s` is local variable. So change not effects the original variable. 

```c

void changeValues(struct Student s){
    s->Name = "changed";
    (*s).Surname = "surname";
}

void main(){
    changeValues(&John);
}
```

We used `&` symbol in here. This symbol mean extract the pointer of the value. With that way we can change our variable from different function freely.


## Bit Fields

We can change our variable's size as what we want in structers. 

```c
struct Student{
    
    char *Name; // 8
    char *Surname; // 8
    unsigned Id; // 4
    unsigned Other; // 4
    unsigned Language:1; // 1?
} John;
```
`Language` is an `unsigned int` but it can only store `1` `bit`. It could be 0 or 1. Otherwise it will overflow!

```c
John.Language = 2; // 0
John.Language = 3; // 1
```

Also we can use `signed` type for `Language` if we want a little fun. It will work as `Two's Complement`.

```c
John.Language = 0; // 0
John.Language = 1; // -1
John.Language = 99998; // 0
```

However, we can't use sizeof function on variables who has a bit field.

## Structure Arrays

We can use `structures` as an array.


```c
struct Student StudentList[100];

StudentList[0].Name = "John";
StudentList[0].Surname = "Turker";
StudentList[0].Id = 1010;
```

Also `structers` can store another `structers` or another types.
```c

struct Person{
    char *Name;
    char *Surname;
};

typedef struct Person Student;

struct Class{
    Student Students[100];
};
```

# Unions

We can store one only variable with different types with `unions`. This property is very interesting.

```c
#include <stdio.h>

union Data{
    int asInteger;
    char character;
    unsigned asUInt;
    unsigned asBitField:4;
};


void main(){
    union Data data;
    data.asInteger = 70;
    printf("character: %c\n",data.character);
    printf("asUInt: %u\n",data.asUInt);
    printf("asBitField: %u\n",data.asBitField);
}

```

All this other types are storing in same memory. If you want to change data from asUInt, you are free to change. But your change will effect all other types.

```c
#include <stdio.h>


union Data{
    int asInteger;
    char character;
    unsigned asUInt;
    unsigned asBitField:4;
};


void main(){
    union Data data;
    data.asInteger = 70;
    printf("character: %c\n",data.character);
    printf("asUInt: %u\n",data.asUInt);
    printf("asBitField: %u\n\n",data.asBitField);
    
    data.asBitField = 10000; // overflow
    
    printf("character: %c\n",data.character);
    printf("asUInt: %u\n",data.asUInt);
    printf("asBitField: %u\n\n",data.asBitField);
    
    data.asInteger = 0;
    
    printf("character: %c\n",data.character);
    printf("asUInt: %u\n",data.asUInt);
    printf("asBitField: %u\n\n",data.asBitField);
    
    data.asBitField = 10000; // overflow
    
    printf("character: %c\n",data.character);
    printf("asUInt: %u\n",data.asUInt);
    printf("asBitField: %u\n\n",data.asBitField);
}
```
```
character: F
asUInt: 70
asBitField: 6

character: @
asUInt: 64
asBitField: 0

character: 
asUInt: 0
asBitField: 0

character: 
asUInt: 0
asBitField: 0
```

I think we had already knew the first answer. However, what about the second one? Number is same with `Third` declaration. But answer is different.
Because on `Second` assignment, we are assigning 0 into the bit field type which is limited with only 4 bits. That mean, our program will change only the first 4 bits while assigning. Remains will stay same. On `Second` assignment, we assign 0 into the unsigned type which is not limited and size is 8. Assign type has a same size with biggest size. So all of variables were changed. Then, on `Fourth` assignment, we assign 0 into the bit field type which is limited with only 4 bits. But our remains are already 0. So, technically nothing changed.

Also, sizeof will give the size of the biggest type inside of the union.


# Exercises

## 1. Declare struct with different kind of types and compare sizes

```c
#include "stdio.h"

#pragma pack(push,1)

struct { 
    char lang;
    int id;
} pack;

#pragma pack(pop)


struct{
    char lang;
    int id;
} pad;


void main(){
    printf("sizeof normal struct: %lu\n",sizeof(pad)); //8
    printf("sum of normal struct: %lu\n",sizeof(pad.lang)+sizeof(pad.id)); //5

    printf("sizeof pack struct: %lu\n",sizeof(pack)); //5
    printf("sum of pack struct: %lu\n",sizeof(pack.lang)+sizeof(pack.id)); //5
}
```

Well, I had try to explain why it is happening. Also `#pragma` attribute works on compile-time. There is no way to change this field after compiling.

## 2. Declare union with different kind of types and compare sizes

```c
#include "stdio.h"

union Avengers{
    char *pointer; // 8
    long long int grandpa; // 8
    long int pa;
    int ma;
    short int ki;
    char ba;
};

long unsigned getSum(union Avengers a){
    return sizeof(a.pointer) + sizeof(a.grandpa) + sizeof(a.pa) + sizeof(a.ma) + sizeof(a.ki) + sizeof(a.ba);
}

long unsigned getSize(union Avengers *a){
    return sizeof(*a); // same thing with plain a
}

void main(){
    union Avengers a;
    printf("sizeof Avengers a: %lu\n",getSize(&a)); // 8
    printf("sum of Avengers a: %lu\n",getSum(a)); //  31
}
```

Briefly, union type takes given biggest types size. Biggest types are `pointer` and `long long int`. Both are the 8 bytes. So, `sizeof` `union` is `8 bytes`. 

## 3. Program to print and convert coordinate systems to each other.

```c
#include "stdio.h"
#include "math.h"
#include "time.h"
#include "stdlib.h"

enum CordinateSystem{Cartesian,Polar};

union first_field{
    int x;
    double angle;
};

union second_field{
    int y;
    double magnitude;
};

typedef struct {
    union first_field first; // x or angle
    union second_field second; // y or magnitude
    enum CordinateSystem type;
} cordinate;

cordinate convertCartesianToPolar(const cordinate cor){
    cordinate new;
    new.type = Polar;
    
    new.first.angle =  atan(cor.second.y/(double)cor.first.x);
    new.second.magnitude = sqrt(      (cor.first.x*cor.first.x) +  (cor.second.y*cor.second.y)          );

    return new;
}

cordinate convertPolarToCartesian(const cordinate cor){
    cordinate new;
    new.type = Cartesian;
    new.first.x = round(cos(cor.first.angle)*cor.second.magnitude);
    new.second.y = round( sin(cor.first.angle) * cor.second.magnitude);

    return new;
}
// It could be universal converter which is checks by enum type

void printCartesian(const cordinate cor){
    switch (cor.type){
        case Cartesian:
            printf("\033[32mX\033[0m: %d\n\033[33mY\033[0m: %d\n",cor.first.x,cor.second.y);
            break;
        case Polar:
            printf("\033[32mDegre\033[0m: %lf\n\033[33mMagnitude\033[0m: %lf\n",cor.first.angle,cor.second.magnitude);
            break;
        default: printf("unknown cartesian type: %d\n",cor.type);
    }
}

void main(){
    srand(time(NULL));

    cordinate cordinateSystem;
    cordinateSystem.type = Cartesian;
    cordinateSystem.first.x = (rand() % 200)-100;
    cordinateSystem.second.y = (rand() % 200)-100;


    printCartesian(cordinateSystem);
    cordinateSystem = convertCartesianToPolar(cordinateSystem);
    printCartesian(cordinateSystem);
    cordinateSystem = convertPolarToCartesian(cordinateSystem);
    printCartesian(cordinateSystem);  
}
```

Program is feeding the initial cordinate system which is cartesian with random numbers and converting to other cordinate system which is polar. And finally it is converting back to the original cordinate system. It might be eat signs of negative numbers :)

## 4. Sort personal data array by name and surname

```c
#include "stdio.h"
#include "time.h"
#include "stdlib.h"


enum Sortby{Name,Surname,Age};

struct userData {
    char *name;
    char *surname;
    unsigned short age;
};

struct userData database[12];
char names[12][10] = {
    "John",
    "Micheal",
    "Ince",
    "Ricard",
    "Ronaldo",
    "Bedro",
    "Khontkar",
    "Messi",
    "Muharrem",
    "Raif",
    "Algendo",
    "Snopdog",
}; // It won't good if some names starts with lower case :)

void initDatabase(){
    srand(time(0));
    for (int i = 0; i<12; i++) {
        database[i].name = names[i];
        database[i].surname = names[rand()%12];
        database[i].age = rand()%100;
    }
}

void printDatabase(){
    for (int i = 0; i<12; i++) {
        printf("name: %s\nsurname: %s\nage: %d\n\n", database[i].name,database[i].surname,database[i].age);
    }
}

void swap_userData(struct userData *first, struct userData *second){
    struct userData tmp = *first;
    *first = *second;
    *second = tmp;
}

void sortDatabase(struct userData *database,enum Sortby sortvia){

    for (int i = 0; i<12-1; i++) {
        int min = i;
        for (int j = i+1; j<12;j++){

            if (
                
                (sortvia == Name && database[j].name[0] < database[min].name[0])  || 
                (sortvia == Surname && database[j].surname[0] < database[min].surname[0]) ||
                (sortvia == Age && database[j].age < database[min].age) 
                
               )   min = j;
        }

        if (min != i){
            swap_userData(&database[min], &database[i]);
        }
    }
}

void main(){
    initDatabase();
    printDatabase();
    
    sortDatabase(database,Name);
    printf("\033[33mSorted\033[0m by \033[32mname\033[0m\n\n");
    printDatabase();

    sortDatabase(database,Surname);
    printf("\033[33mSorted\033[0m by \033[32msurname\033[0m\n\n");
    printDatabase();

    sortDatabase(database,Age);
    printf("\033[33mSorted\033[0m by \033[32mage\033[0m\n\n");
    printDatabase();
}
```

Also I added `Age` field into database. It is using selection sort algorithm which is very easy to write :)

## 5. Find two most distant cartesian points from random filled point array

```c
#include "stdio.h"
#include "stdlib.h"
#include "time.h"
#include <math.h>

struct Cordinates{
    int X,Y;
};

void fillCordinatesByRange(struct Cordinates *cords,int size){
    srand(time(NULL));
    for (int i = 0; i < size; i++){
        cords[i].X = (rand() % 21)-10;
        cords[i].Y = (rand() % 21)-10;
    }
}

void printCordinates(struct Cordinates *cords,int size){
    for (int i = 0; i < size; i++){
        printf("X: %d\nY: %d\n\n",cords[i].X,cords[i].Y);
    }
}

double calculateDistance(struct Cordinates first, struct Cordinates second){
    return sqrt( (abs(first.X) + abs(second.X)) * (abs(first.X) + abs(second.X)) ) + (  (abs(first.Y) + abs(second.Y)) * (abs(first.Y) + abs(second.Y))  ); 
}

struct Result{
    int first,second;
    double result;
};

struct Result getMostDistant(struct Cordinates *cords,int size){

    struct Result result = {0,1,calculateDistance(cords[0],cords[1])};

    for(int i = 0; i < size; i++){

        for (int j = 0; j < size; j++){
            if (i == j || result.first == j && result.second == i) continue; // Duplicate stuffs

            
            if (calculateDistance(cords[i],cords[j])  > result.result)  {
                result.result = calculateDistance(cords[i],cords[j]);
                result.first = i;
                result.second = j;
            }  
        }
    }
    return result;
}

void main(){
    struct Cordinates array[10];
    fillCordinatesByRange(array,10);
    printCordinates(array,10);
    struct Result result = getMostDistant(array,10);

    printf("most distance %lf\ncordinates: (%d,%d) and (%d,%d)\n",result.result,array[result.first].X,array[result.first].Y,array[result.second].X,array[result.second].Y);

}
```
