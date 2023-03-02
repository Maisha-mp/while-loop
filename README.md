#include <stdio.h>

int main() {

  int i,j,k;

 i=1;

 while(i<=10)

 {

     j=1;

     while(j<=10)
     {
        k= i * j;

         printf("%d * %d = %d\n", i,j,k);

         j++;
     }
        i++;

          printf("\n");
     }



    return 0;
}
