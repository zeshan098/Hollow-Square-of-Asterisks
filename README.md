#include<stdio.h>
int main(){
	int row=1;
	int b,c,a=1;
	int col=1;
	 printf("enter the astrik");
	 scanf("%d", &b);
	 
     while(row<=b){
     
  
    col=b;
    
    while(col>=a){
    	printf("*");
           
    	if(row>a){
	if(row==b){
		    		 while(col>a){
				    	printf("*");
				    	col--;
			      	}
				}	 
    		c=a+1;
    		while(col>c){
    			printf(" ");
    		col--;
    		
			}
			
		
		}
    	col--;
    
	}
		 printf("\n");
		 row++;
		 
		
	
	 }
	
	}
