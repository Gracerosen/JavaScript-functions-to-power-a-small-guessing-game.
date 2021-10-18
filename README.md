# JavaScript-functions-to-power-a-small-guessing-game.

Here is a completed version of what i will code as an example to get a sense of what i’ll be building: https://content.codecademy.com/PRO/independent-practice-projects/number-guesser/example/index.html

**I have written the steps, 
I have written the examples of code statements that achieve objectives
I have written/explained the logical overview/context, aims, data flow & how i will gain the most out of this project educationally, 
I have written the purpose of the application and how the logic/methods function within the syntax & how to get the Number Guesser game fully operational, 
I have written how to host it and share it with others,  and how my JavaScript functions are incorporated into a website that also uses HTML/CSS.
I have written how to test that your code is working properly by invoking your newly written functions within script.js with sample inputs and how this will surface any syntax errors that may have cropped up
I have written how to extend this project and how to add functionality to check whether the user guess is between 0 and 9 and alert() the user that their number is out of range. 
I have written my journey through the entire process and any relevant research will be added to this ReadMe such as links i find helpful**

nstead of a step-by-step tutorial, this project contains a series of open-ended requirements which describe the project

i will write JavaScript functions to power a small guessing game.

code will run in the browser instead of just the terminal,& have an output section to help me test my functions and show me if I have syntax errors.

I can open and work in script.js in a text editor and open index.html in a browser to test my code.

I have completed the first 3 sections of Introduction to JavaScript (through Learn JavaScript: Functions) with CodeCademy

’ll write four functions in script.js and some additional JavaScript code in game.js will call my functions based on user interactions, 

I will need to make sure that all of my functions are named exactly as specified so that they can be called correctly when the game is played.

Instead of just seeing text output from your program, my JavaScript functions are incorporated into a website that also uses HTML/CSS.

I will learn more about how to do this from scratch as I continue on my JavaScript journey.

Create a generateTarget() function to be called at the start of each new round in order to generate the new secret target number. This function should return a random integer between 0 and 9.

Math.floor() and Math.random() should help to generate this number.

Create a compareGuesses() function. This function will be called each round to determine which guess is closest to the target number.

This has three parameters representing the user (human) guess, a computer guess, and the secret target number to be guessed.

Determines which player (human or computer) wins based on which guess is closest to the target.

It return true if the human player wins, and false if the computer player wins.

each guess could be greater or less than the target, and the only thing that matters is the distance between the two so i will  compare the absolute value of the difference between the target and each guess

The JavaScript Math.abs() method can help to find absolute values 


Create an updateScore() function. This function will be used to correctly increase the winner’s score after each round.

This function:

Has a single parameter. This parameter will be a string value representing the winner.
Increases the score variable (humanScore or computerScore) by 1 depending on the winner passed in to updateScore. The string passed in will be either 'human' or 'computer'.
Does not need to return any value.


Create an advanceRound() function. This function will be used to update the round number after each round.

advanceRound() should increase the value of currentRoundNumber by 1.

After completing advanceRound(), your Number Guesser game should be fully operational. You should be able to make guesses, see your or the computer score increase correctly, move to the next round, and see the correct round displayed.

Finally i will test that your code is working properly by invoking your newly written functions within script.js with sample inputs & delete this code once I am convinced that everything is working as it should.

For example, we added the following code to our script.js file:

**updateScore('human');
console.log(humanScore); // To confirm that this value increased by 1
updateScore('computer');
console.log(computerScore); // To confirm that this value increased by 1**

This will also surface any syntax errors that may have cropped up in our code.

Project Extensions & Solution:
to extend your project on your own, you could consider the following:

You probably calculated the distance from the computer guess to the target and from the human guess to the target. Move this into a separate **getAbsoluteDistance() ** function 

that takes two numbers and returns the distance, and then use that inside your compareGuesses() function.

Add functionality to check whether the user guess is between 0 and 9 and alert() the user that their number is out of range. It’s not possible to set a number outside this range with the + and = buttons, but users can do so by typing directly in the input field.


Finally I am able to visit forums to compare project to the sample solution code & learn how to host a solution on GitHub in order to share it with others 

There are multiple ways to solve a project like this and i am able to also learn more by seeing others’ code.


