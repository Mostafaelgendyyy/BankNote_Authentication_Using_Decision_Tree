# BankNote_Authentication_Using_Decision_Tree
Whenever you go to the bank to deposit some cash money, the cashier places banknotes in a machine that tells whether a banknote is real or not. This is a classification problem where we are given some input data and we have to classify the input into one of the several predefined categories. Rule-based as well as statistical techniques are commonly used for solving classification problems. Machine learning algorithms fall in the category of statistical techniques.
# Authenticating whether a banknote is real or not is one of the most common tasks in the banking industry.
In this article, we explain the process of building a banknote authentication system using machine learning algorithms. After reading this article, you will be able to understand how classification systems are built using machine learning algorithms.




# process of building a banknote authentication system
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

        1) shows accuracy against training set size and 
        2) the number of nodes in the final tree against training set size.
