# validparentasis
#include <stdio.h>

#include <stdlib.h>



// This is where the parentheses are stored in memory

char buffer[1024];

char stack_pop();

void stack_push(char ch);

int stack_size();





int main(){

FILE *fp;

  // The parentheses sequences is in the parentheses.txt file.

  fp=fopen("parentheses.txt","r");

  if(fp==NULL){

   printf("The input file does not exist.\n");

   exit(-1);

  }

  // Read the parenthese sequences into buffer array.

  fgets(buffer,1024,fp);

  //printf("%s",buffer);

}



// The pop operation in the stack. To be done.

char stack_pop(){

return ')';

}





// The push operation in the stack. To be done.

void stack_push(char ch){

}





// The number of elements in the stack. To be done.

int stack_size(){

return 0;

}

