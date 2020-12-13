## **Yalini Brhanavan - GMIT - H.Dip Data Analytics**

<img src="https://image.ibb.co/gw4Gen/Index_GMIT.png" alt="Index GMIT" border="0" />

* Tasks assessment for Fundamentals of Data Analysis 
* Sep 2020

----------------------------------------------------------------------------------------------------------------------------------------

**TASKS QUESTIONS:**

The assessment is worth 50% of the marks for the module. Four tasks were assigned and all were completed in a single jupyter notebook.

1.  Write a Python function called counts that takes a list as
input and returns a dictionary of unique items in the list as keys and the number of
times each item appears as values. So, the input ['A', 'A', 'B', 'C', 'A']
should have output {'A': 3, 'B': 1, 'C': 1} . Your code should not depend
on any module from the standard library1 or otherwise. You should research
the task first and include a description with references of your algorithm in the
notebook.

2. Write a Python function called dicerolls that simulates
rolling dice. Your function should take two parameters: the number of dice k and
the number of times to roll the dice n. The function should simulate randomly
rolling k dice n times, keeping track of each total face value. It should then return
a dictionary with the number of times each possible total face value occurred. So,
calling the function as diceroll(k=2, n=1000) should return a dictionary like:
{2:19,3:50,4:82,5:112,6:135,7:174,8:133,9:114,10:75,11:70,12:36}
You can use any module from the Python standard library you wish and you should
include a description with references of your algorithm in the notebook.

3. The numpy.random.binomial function can be used to
simulate flipping a coin with a 50/50 chance of heads or tails. Interestingly, if a
coin is flipped many times then the number of heads is well approximated by a
bell-shaped curve. For instance, if we flip a coin 100 times in a row the chance of
getting 50 heads is relatively high, the chances of getting 0 or 100 heads is relatively
low, and the chances of getting any other number of heads decreases as you move
away from 50 in either direction towards 0 or 100. Write some python code that
simulates flipping a coin 100 times. Then run this code 1,000 times, keeping track
of the number of heads in each of the 1,000 simulations. Select an appropriate
plot to depict the resulting list of 1,000 numbers, showing that it roughly follows
a bell-shaped curve. You should explain your work in a Markdown cell above the
code.
4.  Simpson’s paradox is a well-known statistical paradox
where a trend evident in a number of groups reverses when the groups are combined
into one big data set. Use numpy to create four data sets, each with an x array
and a corresponding y array, to demonstrate Simpson’s paradox. You might
create your x arrays using numpy.linspace and create the y array for each
x using notation like y = a * x + b where you choose the a and b for each
x , y pair to demonstrate the paradox. You might see the Wikipedia page for
Simpson’s paradox for inspiration.

----------------------------------------------------------------------------------------------------------------------------------------
**How to run the file:**
1.  Open Task 2020.ipynb in Jupyterlab or Jupyter notebook .
2. click the Kernel button and select Restart & Run All. 
3. when the pop window appear select Restart and Run All Cells. 

**REFERENCES:** 

[Q1]: 
https://www.coursera.org/lecture/python-data/9-2-counting-with-dictionaries-HLgKK
https://www.geeksforgeeks.org/python-count-number-of-items-in-a-dictionary-value-that-is-a-list/
https://www.geeksforgeeks.org/counting-the-frequencies-in-a-list-using-dictionary-in-python/
https://docs.python.org/3.1/library/collections.html
https://www.geeksforgeeks.org/python-counter-objects-elements/
https://medium.com/khaliat/the-counter-class-in-python-b8be31d5e4f6

[Q2]: 
https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.integers.html#numpy.random.Generator.integers
https://medium.com/@soumen.atta/simulating-randomness-using-pythons-numpy-random-module-ad96023daee7
https://stackoverflow.com/questions/9001509/how-can-i-sort-a-dictionary-by-key
https://pythonbasics.org/matplotlib-bar-chart/
https://matplotlib.org/3.3.3/api/_as_gen/matplotlib.pyplot.bar.html
https://numpy.org/doc/stable/reference/generated/numpy.sum.html
https://stackoverflow.com/questions/13567345/how-to-calculate-the-sum-of-all-columns-of-a-2d-numpy-array-efficiently
https://www.geeksforgeeks.org/numpy-sum-in-python/

[Q3]:
https://cmdlinetips.com/2018/12/simulating-coin-toss-experiment-with-binomial-random-numbers-using-numpy/
https://numpy.org/doc/stable/reference/random/generated/numpy.random.Generator.random.html#numpy.random.Generator.random
https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.hist.html

[Q4]:
https://en.wikipedia.org/wiki/Simpson%27s_paradox
https://numpy.org/doc/stable/reference/generated/numpy.linspace.html
https://matplotlib.org/3.3.3/api/_as_gen/matplotlib.pyplot.subplots.html
