# Case Study: Hacker Statistics

This chapter is the last in Intermediate Python for Data science. It blends together everything i've learned up to now. I will use hacker statistics to calculate your chances of winning a bet. Use random number generators, loops and matplotlib to get the competitive edge!

## Context
> * Imagine this situation. You are walking up the empire state building and you're playing a game with a friend. For 100 times you throw a dice, if it's 1 or 2 you go one step down. If it's 3, 4 or 5 you go one step up. Finally, if you throw a 6 you throw the dice again and will walk the resulting number of eyes up. 
> * You cannot go lower than step zero.
> * You admit that you are a bit clumsy and have a chnace of 0.1 % of falling down the stairs when you make a move. Falling down means that you have to start again from step 0. 

With all of that in mind you bet with your friend that's you will reach **60 steps high**.

## Question
**_What is the chance that you will win this bet?_**

## How to solve?
The process will be simulated thousands of times and determine in what fraction of the simulations that you will reach 60 steps (This is a form of hacker statistics).
To do this we will go through the following steps:
* Step 1: _**Random Generators to simulate the dice**_
* Step 2 : _**Determine your next move**_
* Step 3: _**Simulate a Random Walk**_
* Step 4: _**Visualize the walk**_
* Step 5: _**The distribution of random walks**_
* Step 6: _**Implement clumsiness**_
* Step 7: _**Plot the distribution**_
* Step 8: _**Calculate the odds**_