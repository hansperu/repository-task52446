# repository-task52446

# Fundamentals of data analysis task

### Student: Hans Perez Rubin de Celis - G00387884

This work has been developed by searching for information in the GMIT library database and web pages.

A series of examples has been provided for each of the works that give a better understanding of the magnitude of each task.
![imagen 1](https://camo.githubusercontent.com/04dc041570cb6cf2dce07a19befc674720235239/68747470733a2f2f7777772e696f74776f726c64746f6461792e636f6d2f66696c65732f323031392f30352f4765747479496d616765732d313034393333353034302d312e6a7067)

## Task 1
Write a Python function called count that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values. So the input ['A', 'A', 'B','C', 'A'] should have the output {A: 3, B: 1, C: 1}.

## Task 2
Write a Python function called dicerolls that simulates rolling dice. Your function should take two parameters: the number of dice k and the number of times to roll the dice n. The function should simulate randomly rolling k dice n times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. So, calling the function as diceroll(k=2, n=1000) should return a dictionary like: {2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}

## Task 3
The numpy.random.binomial function can be used to simulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if a coin is flipped many times then the number of heads is well approximated by a bell-shaped curve. For instance, if we flip a coin 100 times in a row the chance of getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively low, and the chances of getting any other number of heads decreases as you move away from 50 in either direction towards 0 or 100. Write some python code that simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve. You should explain your work in a Markdown cell above the code.

## Task 4
Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined into one big data set. Use numpy to create four data sets, each with an x array and a corresponding y array, to demonstrate Simpson’s paradox. You might create your x arrays using numpy.linspace and create the y array for each x using notation like y = a * x + b where you choose the a and b for each x , y pair to demonstrate the paradox. You might see the Wikipedia page for Simpson’s paradox for inspiration.

## References

![Gender Bias in Admission Statistics? The Simpson-Paradox.](https://towardsdatascience.com/gender-bias-in-admission-statistics-the-simpson-paradox-cd381d994b16)

How To Code A Fair Coin Flip In Python — Regina Of Tech

Use Python to build a Dice Roller App

How to Simulate a Dice Roll and Guess the Result in Python

Counting the frequencies in a list using dictionary in Python

Usar la Clase Counter para Calcular la Frecuencia de una Lista

Is there a way to track the number of times a function is called?


