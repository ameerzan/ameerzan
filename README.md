My learning journey

#include <stdio.h> /*header file library (input & output function), something that always appear in your program,
header files add functionality to C++*/

 //main is a function, any code inside of {} would be executed
 main() {
  //use this function (for a single line comment)
  //printf used to output text on the screen
  printf("Hi\noh\n"); /*use this function to comment in multiply line*/
  /*escape sequence, \n to insert new line, \n\n to create blank line, \t to create horizontal tab,
  \\ to insert backlash character, \" to insert " " character*/
  //to insert variable, int = integer(1,2,3), float = decimal no.(2.999), char = alphabet (Y,U)
  //all C variable must be named with a unique name, int totalofcars = 29; (to create understandable and maintainable code)
  char myLetter = "A";
  int tree =12;
  int mango=27, banana=28, orange=9;
  int sum = tree+mango+banana+orange;
  printf("%i,%i",sum,tree);
  int q, w, r;
  q = w = r = 30;
  printf("%d\n", w / r);
  printf("My integer is %d,%d and \nmy letter is %c\n",tree,q,myLetter);
  const int SAYANG = 88; //for constant variable good to practice UPPERCASE, useful for code readability and common for programmers
  int abang = 98;
  printf("%d\n",SAYANG);
  int Pizza = 20;
  Pizza += 5;
  printf("%d\n",Pizza);

  int x = 10;
  x += 5;
  printf("%d\n", x);



  return 0; //ends the main function
}
