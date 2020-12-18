# Assessment solution.

This repository contains my solutions to the assessment Tasks 2020 for the module Machine Learning and Statistics at GMIT.

[See here for the instructions](https://learnonline.gmit.ie/mod/url/view.php?id=102004)

## Assessment instructions.

I created a Jupyter notebook, where I completed all tasks. The tasks were listed in the assessment instructions at different times during the semester. There are four tasks in this assessment:

1. *October 5th, 2020*: Write a Python function called sqrt2 that calculates and
prints to the screen the square root of 2 to 100 decimal places. Your code should
not depend on any module from the standard library or otherwise. You should
research the task first and include references and a description of your algorithm.

By the standard library, we mean the modules and packages that come as standard with Python.
Anything built-in that can be used without an import statement can be used.

2. *November 2nd, 2020*: The Chi-squared test for independence is a statistical
hypothesis test like a t-test. It is used to analyse whether two categorical variables
are independent. The Wikipedia article gives the table below as an example,
stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats
to verify this value and calculate the associated p value. You should include a short
note with references justifying your analysis in a markdown cell.

![table](https://github.com/amacuga/mls-tasks-2020/blob/main/img/img1.PNG)

3. *November 16th, 2020*: The standard deviation of an array of numbers x is
calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) .
However, Microsoft Excel has two different versions of the standard deviation
calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above
calculation but in the STDEV.S calculation the division is by len(x)-1 rather
than len(x) . Research these Excel functions, writing a note in a Markdown cell
about the difference between them. Then use numpy to perform a simulation
demonstrating that the STDEV.S calculation is a better estimate for the standard
deviation of a population when performed on a sample. Note that part of this task
is to figure out the terminology in the previous sentence.

4. *November 30th, 2020*: Use scikit-learn to apply k-means clustering to
Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might
be, and then explain how your model could be used to make predictions of species
of iris.

## How to run my jupyter notebook.

1. My repository is located [here](https://github.com/amacuga/mls-tasks-2020.git). 
2. Make sure you have Python installed- I would recommend installing the free version of Anaconda.
3. Follow the steps on how to clone the repository [here](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
4. Run "jupyter notebook" in cmder or similar tool in the cloned repository.
5. Select "Assessment.ipynb".

## References.

**Files:**

* *Assessment.ipynb:*


* *iris.csv* available at: https://archive.ics.uci.edu/ml/machine-learning-databases/iris/

**Img folder:**

* *img1* available at: https://en.wikipedia.org/wiki/Square_root_of_2

* *img2* available at: https://learnonline.gmit.ie/mod/url/view.php?id=102004

* *img3* available at: https://www.datacamp.com/community/tutorials/machine-learning-in-r