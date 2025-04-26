#include <stdio.h>

int main() {
   int choice;

printf("Do You Have A Problem In Life?\n");
printf("1. Yes\n");
printf("2. No\n");
printf("Enter your choice (1 or 2): ");
scanf("%d", &choice);

if (choice == 1) {
    
printf("You chose: Yes\n");
printf("Can You Do Something About It?\n");
        
printf("1. Yes\n");
printf("2. No\n");

printf("Enter your choice (1 or 2): ");
scanf("%d", &choice);

if (choice == 1 || choice == 2) {
printf("Then Why Worry?\n");
            
} 

else {
printf("Invalid choice! Please enter 1 or 2.\n");

}

} else if (choice == 2) {
 
printf("You chose: No\n");
printf("Then Why Worry?\n");
        
}

else {
printf("Invalid choice! Please enter 1 or 2.\n");

}

return 0;

}
