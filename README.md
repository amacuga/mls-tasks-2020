# Assessment solution.

This repository contains my solutions to the assessment Tasks 2020 for the module Machine Learning and Statistics at GMIT.

[See here for the instructions](https://learnonline.gmit.ie/mod/url/view.php?id=102004)

## Assessment instructions.

I created a Jupyter notebook, where I completed all tasks. The tasks were listed in the assessment instructions at different times during the semester. There are four tasks in this assessment:

1. *October 5th, 2020*: Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library or otherwise. You should research the task first and include references and a description of your algorithm.

By the standard library, we mean the modules and packages that come as standard with Python. Anything built-in that can be used without an import statement can be used.

2. *November 2nd, 2020*: The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example, stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.

    ![table](https://github.com/amacuga/mls-tasks-2020/blob/main/img/img1.PNG)

3. *November 16th, 2020*: The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))**2)/len(x)) .However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence.

4. *November 30th, 2020:* NB – when I first posted this task, I accidentally wrote “k-means” where I meant to write “kNN” for k Nearest Neighbours. Because of this, I will allow either algorithm to be used and have extended the deadline by two weeks. 

Use scikit-learn to apply k Nearest Neighbours clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.

## How to run my jupyter notebook.

1. My repository is located [here](https://github.com/amacuga/mls-tasks-2020.git). 
2. Make sure you have Python installed- I would recommend installing the free version of Anaconda.
3. Follow the steps on how to clone the repository [here](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
4. In cmder or similar tool run "jupyter notebook"  in the cloned repository.
5. Select "Assessment.ipynb".

## References.

**Files:**

* *Assessment.ipynb:*
[1] Wikipedia contributors; "Square root"; [Online]. Available from: https://en.wikipedia.org/wiki/Square_root

[2] Wikipedia contributors; "Square root of 2"; [Online]. Available from: https://en.wikipedia.org/wiki/Square_root_of_2

[3] A Tour of Go; "Exercise: Loops and Functions"; [Online]. Available from: https://tour.golang.org/flowcontrol/8

[4] Wikipedia contributors; "Newton's method"; [Online]. Available from: https://en.wikipedia.org/wiki/Newton%27s_method

[5] The Python Tutorial; "Floating Point Arithmetic: Issues and Limitations"; [Online]. Available from: https://docs.python.org/3/tutorial/floatingpoint.html

[6] Wikipedia contributors, “Chi-squared test — Wikipedia, the free encyclopedia,” [Online]. Available from: https://en.wikipedia.org/w/index.php?title=Chi-squared_test&oldid=983024096

[7] Wikipedia contributors; "Pearson's chi-squared test"; [Online]. Available from: https://en.wikipedia.org/wiki/Pearson%27s_chi-squared_test

[8] Statistics How To; "Chi-Square Statistic: How to Calculate It / Distribution"; [Online]. Available from: https://www.statisticshowto.com/probability-and-statistics/chi-square/

[9] Jason Brownlee; "A Gentle Introduction to the Chi-Squared Test for Machine Learning"; [Online]. Available from: https://machinelearningmastery.com/chi-squared-test-for-machine-learning/

[10] The SciPy community; "scipy.stats.chi2_contingency"; [Online]. Available from: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.chi2_contingency.html

[11] Office Support; "STDEV.P function"; [Online]. Available from: https://support.microsoft.com/en-us/office/stdev-p-function-6e917c05-31a0-496f-ade7-4f4e7462f285

[12] Office Support; "STDEV.S function"; [Online]. Available from: https://support.microsoft.com/en-us/office/stdev-s-function-7d69cf97-0c1f-4acf-be27-f3e83904cc23

[13] StackOverflow; "Is there any difference between numpy.std and excel STDEV function?"; [Online]. Available from: https://stackoverflow.com/a/34134033

[14] Wikipedia contributors; "Iris flower data set"; [Online]. Available from: https://en.wikipedia.org/wiki/Iris_flower_data_set

[15] Wikipedia contributors; "k-nearest neighbors algorithm"; [Online]. Available from: https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm

[16] Towards data science; "MachineLearning — KNN using scikit-learn"; [Online]. Available from: https://towardsdatascience.com/knn-using-scikit-learn-c6bed765be75

*Codes adapted from:*

[17] https://stackoverflow.com/q/64295245

[18] https://stackoverflow.com/a/4733196

[19] https://machinelearningmastery.com/chi-squared-test-for-machine-learning/

[20] https://docs.scipy.org/doc/numpy-1.15.1/reference/generated/numpy.random.normal.html

[21] https://www.kaggle.com/nautna/iris-knn-python-classification

* [22] *iris.csv* available at: https://archive.ics.uci.edu/ml/machine-learning-databases/iris/

**Img folder:**

* [23] *img1* available at: https://en.wikipedia.org/wiki/Square_root_of_2

* [24] *img2* available at: https://learnonline.gmit.ie/mod/url/view.php?id=102004

* [25] *img3* available at: https://www.datacamp.com/community/tutorials/machine-learning-in-r