# js-guessing-game
My attempt to a guessing game coded in js

We got an asignment from our teacher to create our own guessing game.

The assignment was to have the program:
- Generate a random number between 1-10 and have the user guess on the right number
- A function to let the user decide if they want to play again
- To store all the users guesses and write them out at the end of the game 

In this version the program will generate a random number between 1-10
The program will then let the user pick a number and also loop the code until the user chooses the right number.
When the user types in the right number I have used document.write to write out a comment on the screen saying that you guessed rigth, and how many attempts you tried.

What I need to figure out next is how to let the user decide if they want to play again or stop.
I also need to figure out how to let the program store data on how many rounds the user have played and what their win precentege looks like.

I'm not entierly sure on how to execute this, I figure that I need to use some kind of a loop where I put the existing code. I will want the user to answer a question if the want to continue.
If the choose "yes" the existin code in the loop will have to run again. If they choose "no" the loop will break and give all the statistics from their game.

I'm thinking about using a "do-loop" saying:</br>
(ask if the user wants to play on more time)
do { 
  the guessing part of the game
while users answer is yes;
  have variable that count how many time you answer yes
else {
show user stats;
}
}





