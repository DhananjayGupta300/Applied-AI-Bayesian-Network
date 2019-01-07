# Applied-AI-Bayesian-Network

Designed using NETICA, Loan Repayment Decision system is a Bayesian Network wherein information of different type of loan applicants and types of loan is asserted by the user of the Bank, and finally concludes whether the applicant will be able to repay loan or not, accurately predicting whether a loan will be repaid (“credit" scoring) is an important task for any bank. High accuracy benefits both the banks and the loan applicants.


# FEATURES:

1.	The created project is designed for a generic credit scoring scenario using 20 nodes.

2.	Nodes within the net are based upon the intuition.

3.	The resultant network had 12 evidence variables which do not depend on any external nodes and have their prior probabilities feed, feeding into 6 inner nodes, which, in turn, feed into the outcome node, Loan Repaid.

4.	The inner nodes serve two purposes: they group data into qualitative conceptual categories, making interpretation of the Bayesian Network easier, and they reduce the size of the CPTs in the network (via “divorcing”). However, even when using these inner nodes, the CPT was still too large to fill in manually.

5.	CPT i.e. conditional probability table for each independent variable were used by Netica to generate the CPTs for dependent variables.

6.	The node, IndividualCreditworthiness, used a weighted average of its parents.

7.	Note: While some of the probabilities are as close to reality as possible, many have been formulated with hypothesizing and following the general trend defined by banks.

8.	Most important variables like IndividualCreditWorthiness and FinancialStability decides the posterior probabilities of every other factors.
 

# USAGE MANUAL:


•	Download and place the “Shaktiman.dne” file in any directory and open it through NETICA application. Compile the project and after the network is initialized, modify and set the values accordingly and see how the network adapts to the change.

