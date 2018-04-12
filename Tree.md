# Tree Based Methods

**What is a tree?**

At every node we have to make a decision based on a particular feature's value. Or we have to divide our feature space based on the feature's value.
For example at the first node we make a decision that "okay, if the value of X_1 is less than t_1 we would go to the left else to the right."

Similarly at every node we do the same and when we have taken these decisions *recursively* we have our feature space divided into certain regions. Now we associate a particular class to the regions if it is a classification problem we are trying to solve OR a continuous value based on the mean/median/max/min etc depending on the problem statement if we are trying to solve a regression problem.

*What do we mean by recursive partitioning?*

Basically what it means is that we always partition a subspace of the entire feature space and not the entire feature space at anytime( well except the first time). EXAMPLE: Let us take just two features X_1 and X_2 and we have the entire 2 dimentional feature space S. At first let us say we divide S into two sub spaces S_1 if X_1 <= t_1 and S2 otherwise. Then recursively we partition S_1 into S_11 and S_12 if X_2 <= t_2 and X_2 > t_2 respectively. And lets say we divide S_2 into S_21 and S_22 based on X_1 <= t_3 or not. This process continues
untill a *convergence criteria* is reached. So if I have to write a pseudo code then it would look like this:

    Partition(S, Features_Space)

      if(Convergence criteria met)

        Stop Process

      F = Select Feature from Feature_Space to divide S

      list(S_1, S_2, ... S_p) = Divide S into p sub-spaces based on F

      Partition(S_1, Features_Space)

      Partition(S_2, Features_Space)

      ...Partition(S_p, Features_Space)

**Introduction to CART**
