# Pokemon_Game

Pseudocode:
First ask the user if he would like to play the demo to Pokémon
Scan his response as an int and use an if to commence a battle
While the health of the cpu and the health of the player are over 0 then it will run still
It is the players move first and it is allowed to do attack item or leave
//this is for attack
If attack it will choose between two
If fire Pokémon, then it will choose between 2 attacks
If fire then the attack will go and the cpu will fight back
If water Pokémon it will choose between 2 attacks
If water then the cpu will fight back
If tackle then tackle will subtract the health from cpu
Both will subtract health form each other so there is a winner
If leave then it will go back to menu
//attack is over
//start of Item Selection
If it chooses item then it will choose power up or heal or back
If heal it will randomize to 5 and make you lose a turn
If power boost then it will boost power but lose a turn
If go back then you will be attacked because you were caught of guard
//end of item selection
If leave the it will ask are you sure
If your sure then the game will end
If not then it will make you return to the battle
//end of leave choice
Once you die you have the choice to leave or play again
Leave ends program don’t leave restart
If you will have the chance to fight a stronger opponent if not they the game ends

Analysis:
I realize that this is going to need one big while loop and a lot of if statements for it to work. The while loop will only be used when it is time for battle but when the battle is over you have the chance to leave the game. The if statements were hard to keep track of because I kept using the same variable but I realized that it would make it a lot more confusing so I changed it and made more variables so I can keep up with where I was at. I put comments everywhere so I could remember what I was doing because I lose track easily and then I must go back through my code to see what was wrong with it. I had a few problems with my health and realized that I was calling the address of the player and cpu health. There was so much more I could have added like an add name to code and what type of enemy it was, but I did not want to mess up what I had. The while loop was extremely helpful and made it easier to redo everything I made.
![image](https://github.com/user-attachments/assets/5c1b1980-257a-4e55-9882-fc4666c54b20)
