Part of work undertaken with Prof. Dimitris Papiliopolus at UW Madison during Fall 2018. 

Various notions of fairness for constraining Machine Learning models to eliminate/mitigate the bias against sub population groups based on protected attributes in a supervised learning framework were surveyed.

Lot of research on algorithmic fairness has been devoted to the study of group fairness. These approaches constrain the classifier to equalize a defined fairness metric across all groups. 

Few popular fairness notions one can come across in the literature are as follows:

### Fairness through unawareness (*Naive approach*)

Algorithm ignores all protected attributes such as race, gender, income, disability etc... while designing the classifier. However, this approach fails most often because of the *redundant encodings*/ correlation among the features.

### Demographic parity 

It requires that the outcome of the predictor be indepenent of the protected attribute. 

