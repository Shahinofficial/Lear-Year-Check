#include <stdio.h>
#include <stdlib.h>

int main()
{
  int year;
  
  printf("Enter year: ");
  
  scanf("%d",&year);

  if (year%4==0 && year%400==0 && year%100==0){
  
    printf("%d is a leap year",year);
    
  }
  
  else{
  
    printf("%d is not leap year",year);
    
  }
  
    return 0;
    
}
