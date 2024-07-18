# Calculator-project-


#include <stdio.h>

int main() {
    int i;
    float num1;
    float num2;
    float operations;
    
    
    
    printf("enter a 1st number\n");
    scanf("%f", &num1);
    
    printf("enter a 2nd number\n");
    scanf("%f", &num2);
    
printf("choose operation:-\n 1) Addition\n 2) Subtraction\n 3) Multiplication\n 4) Division\n");
scanf("%f", &operations);
    
    if(operations==1){
        
      printf("%f", num1+num2);
        
    }
    else if(operations==2){
        
      printf("%f", num1-num2);
        
    }
else if(operations==3){
        
      printf("%f", num1*num2);
        
    }
 else if(operations==4){
        
      printf("%f", num1/num2);
        
    }
 else{
        
      printf("invalid choice");
        
    }
    
    return 0;
}
