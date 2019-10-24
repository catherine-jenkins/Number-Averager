# Number-Averager (Java)

This is a Java program that determines the smallest, largest, and average value from 10 given integers. The user is prompted to enter ten integers between 1 and 100, and then the results are given. The program runs as follows:


Step 1: Prompt the user to input ten integers between 1 and 100, and initilaize a for-loop with 10 iterations.


Step 2: As the user enters each new integer, compare it to smallestValue (initialized at 100) and the largestValue (initialized at 0). If the value is smaller than smallestValue, replace smallestValue with the value. If the value is larger than largestValue, replace largestValue with the value. 


Step 3: At the end of each iteration, add the user's input to runningTotal.

Step 4: Once all ten integers have been entered and correctly assigned, exit the for-loop and divide the runningTotal by 10.0 to compute the average. 

Step 5: Display the smallest value, largest value, and the average.
