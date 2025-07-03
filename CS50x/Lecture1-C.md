## Source Code
- Humans code programs in source code
- Source code provide a level of lucidity when it comes to writing programs, which is why they are used as opposed to writing programs directly in machine code which is binary and not understandable
- Machines, however, do not understand said source code. Machines only understand machine code
- Thus, machines use a compiler to translate the source code into machine code.

## Hello, world!
A program printing "Hello world" would be structured like so in the C programming language:
#include <stdio.h> - "standard io", this line is what's known as a header and is essential for access to the default libraries of C
int main(void)
{
 printf("hello world\n"); - \n brings the cursor to a new line, ";" to finish the line
}
- Once ran, this program would output "hello world"

- Backslashes can be used to escape within strings, i.e, suppose you want to print example:"Test", you would do
- printf("example:\"Test"\)
- Otherwise, the program wouldn't work

- \\ for a single backslash

## Variables
string example = "working";
- So, there is a semicolon to end the line, the variable name of 'example', and the variable type, which must be defined, at the beginning.
- To print out variables we make use of placeholder symbols.
printf("Test: %s", example)
- outputs: "Test: working"

## Command commands
- cd: moves to a directory
- ls: lists files
- mkdir: creates a new file
- mv: moves files
- rm: removes a file
- rmdir: removes a directory

## Conditionals
- The structure for comparing two items are as follows:
if (x < y) {
...
}
Other operators are:
- =: assignment
- <: less than
- <=: less than or equal to
- >: greater than
- >=: greater than or equal to
- ==: equal to
- !=: not equal to (the exclamation mark is often used to invert)
  
## Loops
A loop to 3 may look like:
int i = 3;
while (i > 0){
 i--;
}
But, it's more common practice to code it in the format:
for (int i = 0; i < 3; i++) {
 ...
}
There is also a 'do' loop, similair to a while loop, except it'll run a function at least once definitively 
do 
{
 ... - Whatever is here will run at least once, unlike a while loop which may never run in the first place
}
while (true) - The 'true' here may be any condition

## Functions

void meow(void) - no input, no output (nothing returned)
{
 printf("meow\n");
}
meow(); - Calling the function here
