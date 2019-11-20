#include <stdio.h>
int b = 3;
int h = 3;
void drawSquare(char c){
	
   for(int i = 0; i < h; i++){
      for(int j = 0; i < b; j++){
		 print("%c", c);
	  }
	  printf("\n");
   }
	
	
}

void drawSquare(char c, int b, int h){
	
    for(int i = 0; i < h; i++){
      for(int j = 0; i < b; j++){
		 print("%c", c);
	  }
	  printf("\n");
   }
	
	
}

int main()
{
   int n;
   
   printf("INPUT NUMBER\n");
   scanf("%d", &n);
   if((n == 1 || n == 2) == 1){
	   printf("INPUT BASE: \n");
	   scanf("%d", &b);
       print("INPUT HEIGHT: \n");
	   scanf("%d", &h);
   }
   switch(n){
    
	   case '1':
		   drawSquare('#', b, h);
		   break;
		   
	   case '2':
		   drawSquare('@', b, h);
		   break;
		   
	   default:
		   drawSquare('#');
		   break;
		      
   }
   
   
   return 0;
}
