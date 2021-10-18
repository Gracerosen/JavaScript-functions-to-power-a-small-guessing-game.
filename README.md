# JavaScript-functions-to-power-a-small-guessing-game.

I have done this since 2010 following my CIW Certification and University project on my Music Technology first year in 2009. So i am not unfamiliar with hosting Interactive JavaScript Websites that combine HTML and CSS with JavaScript and use concepts to lay the foundation for adding interactivity to websites. and bridge the gap between learning JavaScript principles and applying JavaScript to real web development projects. i know all i need for front-end or back-end development using Javascript,HTML & CSS... it has not changed drastically in ten years since i first began learning and this project was a refresher.

Here is a completed version of what i will code as an example to get a sense of what i’ll be building: https://content.codecademy.com/PRO/independent-practice-projects/number-guesser/example/index.html

Before doing this project i have learned about:
CONDITIONALS: how to use if, else if, else, switch, and ternary syntax to control the flow of a program in JavaScript.
FUNCTIONS: function syntax, passing data to functions, the return keyword, ES6 arrow functions, and concise body syntax.
SCOPE: global and block level scope in JavaScript.
ARRAYS: a data structure in JavaScript used to store lists of data.
LOOPS: how to use for and while loops to execute blocks of code multiple times.
ITERATORS:  how to use iterator methods to simplify the process of looping over arrays.
OBJECTS: JavaScript ES6 object syntax to model real-world items.
and i can move on to this: https://www.codecademy.com/courses/introduction-to-javascript/informationals/learn-javascript-next-steps

Because i will want to continue learning JavaScript, i aim to check out more Intermediate JavaScript! for example topics like classes, modules, and asynchronous programming and how JavaScript operates under the hood to get a deeper understanding about the language.

Part of this touches on HTML and CSS for web development to create websites. Together with JavaScript, HTML and CSS are the three main tools I need to build a website. i can create web pages using HTML structurally/architecturally and then style them using CSS. 

HERE I HAVE OUTLINED VARIOUS THINGS TO ILLUSTRATE LEARNING AND APPLICATION OF SKILLS LEARNED FOR FUNCTIONAL OPERATIONAL OUTCOMES AND DEMONSTRATE MY ABILITY AS A SOFTWARE DEVELOPER.

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


