# Module 1

## History of the C programming language

- The C programming language was created by Ken Thompson and Dennis Ritchie
- The key phrase, "Hello, world", was created by Brian Kernighan, a Canadian scientist who worked at Bell laboratories with the two creators

# Module 2

## Structure of a simple C program

```c

// preprocessor directive
#include <stdio.h>

// main function
int main(void) {
  
  // variable declaration
  int i = 0;
  
  // executable statements
  printf("+");
  
  for(i = 0; i < 45; i++) {
    printf("-");
  }
  
  printf("+\n");
  
  printf("Hello, world!  This is my first program in C!\n+");
  
  for(i = 0; i < 45; i++) {
    printf("-");
  }
  
  printf("+");
  
  // return statement
  return 0;
}

```

# Module 3

## Simple calculations with format specifiers

- %d specifies an integer number in a string of characters
  - The integer gets passed in as additional parameters to the function

```c

#include <stdio.h>

int main(void){
    printf("The product of %d and %d is %d.",50,2,50*2);
    
    return 0;
}

```
