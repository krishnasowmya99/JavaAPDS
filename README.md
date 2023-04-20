# JavaAPDS
----Rock Paper Scissors----
This Java code defines a game of rock-paper-scissors and plays ten rounds of it. The user is prompted to choose rock, paper, or scissors, and the computer selects one at random. The outcome of each round is displayed, as well as a summary of the ten rounds.

The code begins by importing the Scanner and Random classes and creating static instances of them. The number of rounds is defined as a constant, and the possible choices (rock, paper, scissors) and outcomes (computer win, player win, tie) are defined as constants as well.

The main method begins by displaying a sign-on message and greeting the player. It then initializes arrays to store the player's and computer's choices and the results of each round. It also initializes integer variables to count the number of player wins, computer wins, and ties.

The game then enters a loop that executes ten times. In each iteration, it prompts the player to choose rock, paper, or scissors, generates a random choice for the computer, determines the outcome of the round, and stores the choices and outcome in the appropriate arrays. It also increments the appropriate win/tie count.

After the loop has executed ten times, the code calls the showGameResults method, which displays a summary of the ten rounds. It then displays a final summary of the game, including the number of player wins, computer wins, and ties, and declares a winner.

The code defines several helper methods: 

- getPlayerChoice prompts the player to choose rock, paper, or scissors and returns their choice as an integer.
- getRoundResult takes the player's and computer's choices as arguments and determines the outcome of the round based on the game rules (rock beats scissors, scissors beats paper, paper beats rock).
- showRoundResult takes the player's and computer's choices and the outcome of the round as arguments and displays a message indicating who won and what the choices were.
- showGameResults takes the arrays of player and computer choices and round results and displays a summary of the ten rounds.
