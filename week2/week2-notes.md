There are libraries that lets you use certain functionality

heuristics: rules of writing code

**Source Code:** 

The code that you write

**Compiler:**

A program that translates on language to another

source code → Compiler → Machine code

**Interface command:**

code hello.c: *creates code*

make hello: *compiles file*

./hello: *runs file*

`.h` : is a library (A header file)

`#include <stdio.h>` : printf lives in <stdio.h> / includes says to the computer find the file

`int main(void)`

`{`

`printf(”hello, world**\n**”);`

`}`

`\n` lets you create a new line

`\\n` lets you print the characters by adding another backslash

`get_string` : gets string of text

arguments → function → return value

`string answer = get_string("What's your name?");` 

`**answer**` = name of variable

`**string`** = types of variable

`printf("hello, %s\n", answer);`

`%s` is a placeholder

`,` second argument goes after comma

`get_int` numbers

`%i` for integers

### **Boolean + Flow Control:**

`if (x < y)`

`{`

`printf(’x is less than y);`

`}`

`**else**`

`**else if**`

`==` is equal to

### **Variables**

`int counter = 0;`

- specify type which is **int**
- set name which is **counter**
- set value which is **0**

`counter += 1` is also equal to `counter++`

**char** is always a single character

`get-char` gets single character

`char c = get_char(”Do you agre”);`

**More characters** use double quotes

**Single character** use single quotes

### **logical operators**

`||` is or

`&&` is and

### **Loops**

while loop

`while (counter > 0)`

`{`

`printf(meow\n”);`

`counter = counter - 1;`

`}`

**For Loop**

`for ( I = 3; I < 3; I++) {`

`printf("Meow\n");`

`}`

**do…while:**

`do {`

`code`

`} while () {`

`code`

`}`

**//comments are written like this** 

### **Functions**

Can copy the first line of a function to the top of the code in **C** with a semicolon, which will tell it to look for that function below. 

`void add(void) {`

`int add(void) {`

`int add(int a, int b)` can pass numbers via parameters

`const` in the beginning adds a **constant** integer

**Scope:** Context in which variables exist

`void meow(**int n**)` if you pass this prototype inside of your function you can take on multiple arguments

`int main(void) {`

`meow(3)`

`}`

**Running operations:**

`int x = get_int(”x: ”);`

`int y = get_int(”y: ”);`

`printf(”%I\n”, x + y);`

`printf(”%**.5f**\n”, x + y);` the .5 will show 5 decimal places

**Integer overflow:** If you count past the allotted amount of ram (memory)

**Truncation:** If you divide an integer by an integer if the value is a long decimal value it gets thrown away— *it gets truncated or discard*

**Type Casting:** converting one type to another:

`(float) x / (float) y;`

**Floating-point imprecision:** can’t possibly represent the amount of decimal floating point numbers on the screen
