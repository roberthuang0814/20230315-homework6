#include <stdlib.h>    
#include <stdio.h>    
    
int main(){    
    int x;    
    scanf("%d",&x); //讀取值存到變量x中   
    switch(x){    
        case 3:    
        case 4:    
        case 5:    
            printf("Spring\n");    
            break; 如果x為3 4 5，則輸出Spring，如果x為其他值，則不進行任何處理。    
        case 6:    
        case 7:    
        case 8:    
            printf("Summer\n");    
            break; //如果x為6 7 8，則輸出Summer，如果x為其他值，則不進行任何處理。    
        case 9:    
        case 10:    
        case 11:    
            printf("Autumn\n");    
            break; //如果x為7 8 9，則輸出Autumn，如果x為其他值，則不進行任何處理。   
        case 12:    
        case 1:    
        case 2:    
            printf("Winter\n");    
            break; //如果x為12 1 2，則輸出Winter，如果x為其他值，則不進行任何處理。   
    }    
}  
