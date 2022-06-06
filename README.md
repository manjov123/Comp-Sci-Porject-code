# EoYCompSciProject
In this game, the player will choose the number of sides to a die that they will then try to guess the number of a roll. 

There are 2 aspects to the game, the guessing, and statistics of it. Guessing is relatively simple we would ask for an integer of a die, and randomly find a number comparing it to what the player guessed. If he guesses correctly he wins, if not, he loses. 

All of this information for each player is tracked along the way and at any time, they are able to find their statistics. This means that they will know their predicted chance of guessing compared to what they actually guessed correctly. The higher the actual versus predicted is the higher score for each player. Ultimately, each player becomes a key and the score is a value. 

We will use hashmaps for assigning each person to a key and their score to a value, so once a user asks for their score it will constantly be updated. We will use a try catch in case users input a string not integer. Use a switch statement to understand what the user wants to do: play, statistics, quit. All of this is in a loop so that the player can keep guessing and it would only break once a quit statement is executed. 

We will have String and Integers to hold the guesses, actual values, usernames, and scores. We will use scanners to find the users input and guesses, and randint to compare their guess. 

I don't think we will create our own methods, but once the time comes we will and add it to this list. 

Authors: Max Richardson, Manish Nadendla, and Ryan Choudhury

Changelog:
5/12: Created
5/18: Changed game description
5/19: HashMap and switch command implementation (stat system)
5/20: Implementation of try/catch 
5/23: Validating user input with no error messages
6/2: Increased ease of use with new startup instructions & better-looking leaderboard
