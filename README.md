# BankNote_Authentication_Using_Decision_Tree
Whenever you go to the bank to deposit some cash money, the cashier places banknotes in a machine that tells whether a banknote is real or not. This is a classification problem where we are given some input data and we have to classify the input into one of the several predefined categories. Rule-based as well as statistical techniques are commonly used for solving classification problems. Machine learning algorithms fall in the category of statistical techniques
![image](https://user-images.githubusercontent.com/85330521/210282293-3faede62-2782-4709-acb7-959aaf7f9f50.png)

# Authenticating whether a banknote is real or not is one of the most common tasks in the banking industry.
In this article, we explain the process of building a banknote authentication system using machine learning algorithms. After reading this article, you will be able to understand how classification systems are built using machine learning algorithms.
•

# BankNote Dataset Description
We will be working with the “Banknote” standard binary classification dataset.

The banknote dataset involves predicting whether a given banknote is authentic given a number of measures taken from a photograph.

The dataset contains 1,372 rows with 5 numeric variables. It is a classification problem with two classes (binary classification).

Below provides a list of the five variables in the dataset.

    •   variance of Wavelet Transformed image (continuous).

    •   skewness of Wavelet Transformed image (continuous).

    •   kurtosis of Wavelet Transformed image (continuous).

    •   entropy of image (continuous).

    •   class (integer).
![image](https://user-images.githubusercontent.com/85330521/210282645-cddf3277-ab69-4a74-a994-57796056ba40.png)

A histogram plot is then created for each variable.

We can see that perhaps the first two variables have a Gaussian-like distribution and the next two input variables may have a skewed Gaussian distribution or an exponential distribution.
![image](https://user-images.githubusercontent.com/85330521/210282769-95d6a733-53b0-4456-8838-78e8ecee788c.png)


# Process of building a banknote authentication system
1. Experiment with a fixed train_test split ratio:Use 25% of the samples for
training and the rest for testing.

   A.	Rerun this experiment five times and notice the impact of different random splits of the data into training and test sets.
   
   B.	Report the sizes and accuracies of these trees in each experiment.


2. Experiment with a range of train_test split ratio: Measure the impact of
training set size on the accuracy and the size of the learned tree.
Consider training set sizes in the range [ 30% - 70%] (Start with training
data size 30% , 40% .... Until you reach 70%) and for each training
set_size :

    A. run the experiment with five different random seeds.

    B. calculate mean, maximum and minimum accuracy at each training set_size.

    C. measure the mean, max and min tree size.

    D. store your statistics in a report.

    E. Draw two plots: 

        1) Shows accuracy against training set size.
        2) The number of nodes in the final tree against training set size.
