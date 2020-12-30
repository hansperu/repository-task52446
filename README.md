# repository-task52446

# Fundamentals of data analysis task

### Student: Hans Perez Rubin de Celis - G00387884

This work has been developed by searching for information in the GMIT library database and web pages.

A series of examples has been provided for each of the works that give a better understanding of the magnitude of each task.


![imagen 1](https://camo.githubusercontent.com/04dc041570cb6cf2dce07a19befc674720235239/68747470733a2f2f7777772e696f74776f726c64746f6461792e636f6d2f66696c65732f323031392f30352f4765747479496d616765732d313034393333353034302d312e6a7067)

**My final work on these tasks can be found in the Jupyter Notebook Python count.ipynb file.**

## Task 1
Write a Python function called count that takes a list as input and returns a dictionary of unique items in the list as keys and the number of times each item appears as values. So the input ``['A', 'A', 'B','C', 'A']`` should have the output ``{A: 3, B: 1, C: 1}.``Your code should not depend on any module from the standard library(1) or otherwise. You should research the task first and include a description with references of your algorithm in the
notebook.
> (1) By the standard library, we mean the modules and packages that come as standard with Python. Anything built-in that can be used without an ``import`` statement can be used.

## Task 2
Write a Python function called ``dicerolls`` that simulates rolling dice. Your function should take two parameters: the number of dice k and the number of times to roll the dice n. The function should simulate randomly rolling k dice n times, keeping track of each total face value. It should then return a dictionary with the number of times each possible total face value occurred. So, calling the function as ``diceroll(k=2, n=1000)`` should return a dictionary like: ``{2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}``
You can use any module from the Python standard library you wish and you should include a description with references of your algorithm in the notebook.

## Task 3
The ``numpy.random.binomial`` function can be used to simulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if a coin is flipped many times then the number of heads is well approximated by a bell-shaped curve. For instance, if we flip a coin 100 times in a row the chance of getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively low, and the chances of getting any other number of heads decreases as you move away from 50 in either direction towards 0 or 100. Write some python code that simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track of the number of heads in each of the 1,000 simulations. Select an appropriate plot to depict the resulting list of 1,000 numbers, showing that it roughly follows a bell-shaped curve. You should explain your work in a Markdown cell above the code.

## Task 4
Simpson’s paradox is a well-known statistical paradox where a trend evident in a number of groups reverses when the groups are combined into one big data set. Use numpy to create four data sets, each with an ``x`` array and a corresponding ``y`` array, to demonstrate Simpson’s paradox. You might create your ``x`` arrays using ``numpy.linspace`` and create the ``y`` array for each ``x`` using notation ``like y = a * x + b`` where you choose the ``a`` and ``b`` for each ``x`` , ``y`` pair to demonstrate the paradox. You might see the Wikipedia page for Simpson’s paradox for inspiration.

In numerical analysis, Simpson's rule or method (named in honor of Thomas Simpson) and sometimes called Kepler's rule is a method of numerical integration that is used to obtain the approximation of the integral:

![imagen algoritmo](https://wikimedia.org/api/rest_v1/media/math/render/svg/2c88a511d85fc5ad91c6ac0fc8d1869faf37db32)

![imagen metodo simpson ilustracion](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/Simpsons_method_illustration.svg/664px-Simpsons_method_illustration.svg.png)

# References
## Books

![Imagent](http://rps2images.ebscohost.com/rpsweb/othumb?id=NL$1084592$PDF&s=d)

### Learning IPython for Interactive Computing and Data Visualization - Second Edition
**Series:Community Experience Distilled**
**Authors:** Rossant, Cyrille
**Publication Information:** Ed.: Second edition. Birmingham, UK : Packt Publishing. 2015
**Resource Type:** eBook

![Imagent](http://rps2images.ebscohost.com/rpsweb/othumb?id=NL$1703793$PDF&s=d)

### IPython Interactive Computing and Visualization Cookbook : Over 100 Hands-on Recipes to Sharpen Your Skills in High-performance Numerical Computing and Data Science in the Jupyter Notebook, 2nd Edition
**Series:Community Experience Distilled**
**Authors:** Rossant, Cyrille
**Publication Information:** Ed.: Second edition. Birmingham : Packt Publishing. 2018
**Resource Type:** eBook


![Imagent](http://rps2images.ebscohost.com/rpsweb/othumb?id=NL$1841870$PDF&s=d)

### Hands-On Data Analysis con NumPy y pandas: Implementar Python Paquetes De Datos manipulación para procesamiento
**Authors:** Miller, Curtis
**Publication Information:** Birmingham: Packt Publishing. 2018
**Resource Type:** eBook

![Imagent](http://rps2images.ebscohost.com/rpsweb/othumb?id=NL$880858$PDF&s=d)

### Python Data Analysis
**Series:Community Experience Distilled**
**Authors:** Idris, Ivan
**Publication Information:** Birmingham, U.K. : Packt Publishing. 2014
**Resource Type:** eBook


![Imagent](http://rps2images.ebscohost.com/rpsweb/othumb?id=NL$1495814$PDF&s=d)

### Python Data Analysis - Second Edition
**Authors:** Fandango, Armando
**Publication Information:** Ed.: Second edition. Birmingham : Packt Publishing. 2017
**Resource Type:** eBook



## Web page references

[Gender Bias in Admission Statistics? The Simpson-Paradox.](https://towardsdatascience.com/gender-bias-in-admission-statistics-the-simpson-paradox-cd381d994b16)

[How To Code A Fair Coin Flip In Python — Regina Of Tech](https://towardsdatascience.com/how-to-code-a-fair-coin-flip-in-python-d54312f33da9)

[Use Python to build a Dice Roller App](https://towardsdatascience.com/use-python-to-build-a-dice-roller-app-2408e66bf009)

[How to Simulate a Dice Roll and Guess the Result in Python](https://medium.com/an-amygdala/how-to-simulate-a-dice-roll-and-guess-the-result-in-python-9785079af6f3)

[Counting the frequencies in a list using dictionary in Python](https://www.geeksforgeeks.org/counting-the-frequencies-in-a-list-using-dictionary-in-python/)

[Usar la Clase Counter para Calcular la Frecuencia de una Lista](https://www.youtube.com/watch?v=2iC8jDLkKwQ&feature=youtu.be)

[Is there a way to track the number of times a function is called?](https://stackoverflow.com/questions/21716940/is-there-a-way-to-track-the-number-of-times-a-function-is-called)


