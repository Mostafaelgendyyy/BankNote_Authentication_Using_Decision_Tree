# BankNote_Authentication_Using_Decision_Tree
Whenever you go to the bank to deposit some cash, the cashier places banknotes in a machine that tells whether a banknote is genuine or counterfeit. The machine uses some classification techniques to do it.






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
