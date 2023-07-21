#include <stdio.h>
#include <string.h>

int main()
{
   char name[25];

   printf("\nWhat's your name? ", name);
   fgets(name, 25, stdin);
   name[strlen(name)-1] = '\0';
  
   printf("\nHello %s, Nice to meet you !!! ", name);
}
