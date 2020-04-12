# marks
To display grades based on marks
#include <stdio.h>

int main() {
 int x;
 printf("Enter the marks\n");
 scanf("%d",&x);
 if(x<=100 && x>=85)
  printf("Grade A\n");
  else if(x<=84 && x>=70)
  printf("Grade B\n");
  else if(x<=69 && x>=55)
  printf("Grade C\n");
  else if(x<=54 && x>=40)
  printf("Grade D\n");
  else 
  printf("Grade F");
    return 0;
}
