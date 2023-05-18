# Bac369
# Loan Approval Decisions

## Motivation
- Loans are hard to determine
- Loan approval can be a key factor in financial success (or ruin)
- Personally interested in starting a business some day, looking for insight
- Seems like an interesting way to use ML models we have learned
- Uses categorical and numerical data to reach decisions
- Large Data Set, but not too cumbersome for training
- Involves a bit of feature engineering


## Goals
Using historical data about whether loans were fully paid off or charged off, find a model to most accurately predict whether or not a loan should be approved and disbursed or not.  
Analyzed why the a particular models perform better for the problem above.
Postulate on how improvements to the models or my thought processes could improve.
Achieve better performance than dataset implies   
Target value MIS_Status with PIF and CHGOFF if loan was paid off or defaulted
P I F     361524 :  CHGOFF     98583  =  460107 total 
Aim for higher than  79% accuracy for classification


## Models
- Stochastic Gradient Descent: Elasticnet, L1, L2
- Logistic Regression: L1, L2
- Decision Tree: Gini Depth 3 and 10, Entropy Depth 3, Adaboost
- Multi-layer Perceptron
- Gradient Descent
- Tensorflow: Binary CrossEntropy
