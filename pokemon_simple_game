/* Name: Yabsra Alemu
*/
 
 
#include<stdio.h> 
#include <stdlib.h>
 
 
 
 
//first create variables for use  
 
int main(void) {
 
//these are all the instance variables ill be using for the //program
int attackTackle;
int attackerChoice;
int attackChoice;
int heal;
int attack;
int cpuAttack;
int cpuEscape;
int battle; 
int choice;
int choiceEscape;
int continu;
int continu1;
char name[25];
int itemChoice;
printf("Welcome to the Demo Pokemon Game!\npress 1 to continue press 2 too leave:\n");
scanf("%d", &continu1);
 
if(continu1 == 1){
 
  printf("What is your name traveler: 25 character limit:\n");
  scanf("%s", &name);
 
  
  }
 
  printf("Hello %s! welcome to poke world!\n press 1 to continue:\n", name);
  scanf("%d", &continu);
  
  if(continu == 1){
 
printf("Oh no an Enemy has appeared %s!\npress 1 to continue:\n", &name);
scanf("%d", &continu);
 
printf("Comense for Battle %s?\npress 1 to continue, press 2 to skip: \n", name);
scanf("%d", &continu);
 
if(continu == 2){
 
  printf("you skiped\n");
  printf("end of Pokemon Game\n");
}
  }
//This is where the battle Begins while player and cpu's health is over 0
if(continu == 1){
 
  int player1 = 30;
    int cpu = 50;
  //these are the health of the figheters
  
  //This is where the battle Begins while player and cpu's health is over 0
  while(player1 >= 0 || cpu >= 0){
    //when player 1 and cpu have over 0 health
          printf("*************************************");
          printf("\nbattle comense:\n");
         
    printf("cpu health %d %s health %d\n", cpu, name, player1);
    //this will check the health of opp and player
    printf("1. attack 2. item 3. escape\n");
      scanf("%d", &choice);
    //choices of what you can do attack item escape
      
      if(choice == 3){
        //if they pick escape then it will make sure if they want to and they will lose their progress
        
        printf("are you sure %s? 1 yes, 2 no:\n", name);
        scanf("%d", &choiceEscape);
          //this will prompt the user to see if they are sure
        
        if(choiceEscape == 1){
        //if they escape then they will lose progress
        printf("successfully escaped!\n");
        break;
       }//end of the if
        
        if(choiceEscape == 2){
          //f no then ot will go back and do the exact same program to fight the program
          printf("\nbattle comense:\n");
          printf("cpu health %d\n %s health %d", cpu, name, player1);
          
          printf("1. attack 2. item 3. escape\n");
      scanf("%d", &choice);
            //this will prompt the user what he would like to do
           }//end of choice escape
        
        else{
          
        printf("ERROR: are you sure %s ? 1 yes, 2 no:\n", name);
        scanf("%d", &choiceEscape);
        //any other key will lead to an error and make it ask again
      }//end of else
        }//end of choice 3
 
       else if(choice == 1){
          attackTackle = rand() % 15;
          cpuAttack = rand() % 30;
          attack = rand() % 30;
          //these are the random attack rangeing from 1 - 30
          printf("choose an attacker %s:\n", name);
        
           printf("1. fire attack pokemon 2. water attack pokemon 3. back\n");
          scanf("%d", &attackerChoice);
          //chooses what pokemon would you like to fight for you or would you like to go back.
          if(attackerChoice == 1){
 
            printf("choose attack:\n 1. Tackle 2. Water Attack 3. Back\n");
            scanf("%d", &attackChoice);
 
            if(attackChoice == 1){
              
              printf("tackle attack for %d:\n", attackTackle);
            cpu = cpu - attackTackle;
              }
            else if(attackChoice == 2){
            printf("fire attack for %d:\n", attack);
            cpu = cpu - attack;
            //if fire attack then it will subtract the health of the cpu
              }
            else if(attackChoice == 3){
 
              
            }
            else{
 
              
            }
              
              }//end of attack 1
         
          else if(attackerChoice == 2){
            printf("choose attack:\n 1. Tackle 2. Water Attack 3. Back\n");
            scanf("%d", &attackChoice);
 
            if(attackChoice == 1){
              
              printf("tackle attack for %d:\n", attackTackle);
            cpu = cpu - attackTackle;
              }
            else if(attackChoice == 2){
            printf("water attack for %d:\n", attack);
            cpu = cpu - attack;
            //if water attack then it will subtract the health of the cpu
            
              } 
            else if(attackChoice == 3){
 
              
            }
            else{
 
              printf("ERROR:\n");
            }
              }//end of else 2
         
          else if(attackerChoice == 3){
            //if attack choice is 3 then it will go back but you will lose health because turn is skipped
            }//end of attack choice 3
          
          if(attack || attackTackle){
 
            printf("cpu attack %d\n", cpuAttack);
            player1 = player1 - cpuAttack;
              //this is right after player has attacked
              //cpu's attack will subtract health
            }//end of cpu attack
          
          }//end of attack
         
           else if(choice == 2){
 
            printf("Items you have:\n1. heal 2. power Up 3. Back:\n");
            scanf("%d" , &itemChoice);
            //prompt the user to see if he wants to heal or power up
              if(itemChoice == 1){
              int heal = rand() % 5;
              printf("healed %d\n", heal);
              player1 = player1 + heal;
              //heal a random number to the player
              }//end of item choice 1
 
              else if(itemChoice == 2){
                int powerUp = rand() % 2;
                printf("attack boost by %d^\n", powerUp);
                attack = powerUp + attack;
                //attack boost will
              
              }
            
          }
    
    if(player1 <= 0){
    //end program
    
    
      printf("Oh No %s! you Died!\npress 1 to restart press 2 to end program:\n", name);
    scanf("%d",&continu);
        //prompt the user if he wants to restart or end
      if(continu == 2){
          //if end the game. the game will be over
        printf("end Game...\n");
        break;
        //break the program
        }//end of choice 2
      if(choice == 1){
      
        player1 = 30;
        cpu = 50;
        //this reverts the health of the cpu and player 1
        
        }//if choice 1 ends
      }//end if player is dead
 
    if(cpu <= 0){
    //if cpu is dead it congragulates the player and sees if he wants a challenge
      printf("\nCongragulations %s!\nyou have killed your first pokemon!\n", name);
        printf("Do you want to look for more?\n1 for yes 2 for no:\n");
          scanf("%d", &choice);
          //asks for what he wants
        if(choice == 1){
           
          printf("Another Pokemon has appeared %s! comense for battle!\n", name);
          cpu = 50 + 20;
          cpuAttack = cpuAttack + 4;
          player1 = 30;
          //if he chooses to play again then he will have the same health but cpu is stronger
          }//end of choice 1
        else if(choice == 2){
 
          printf("THANKS FOR PLAYING %s!!!", name);
          break;
          //this will end the program if they choose 2
          }//end of choice 2
      
      }//end of cpu death
    }//end of while loop
    
  
  
  }//end of compense battle
    
  
  
  
 
    
 
return 0; 
 
 
  
 
}//end of main
