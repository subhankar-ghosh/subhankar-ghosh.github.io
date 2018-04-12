# Tree Based Methods

**What is a tree?**

At every node we have to make a decision based on a particular feature's value. Or we have to divide our feature space based on the feature's value.
For example at the first node we make a decision that "okay, if the value of $X_1$ is less than $t_1$ we would go to the left else to the right."
Similarly at every node we do the same and when we have taken these decisions recursively we have our feature space divided into certain regions. Now we associate a particular class to the regions if it is a classification problem we are trying to solve OR a continuous value based on the mean/median/max/min etc depending on the problem statement if we are trying to solve a regression problem.

**Introduction to CART**
