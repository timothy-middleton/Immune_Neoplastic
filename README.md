# Immune_Neoplastic
Use the auto-sklearn machine learning toolkit to classify Cells Immune vs Neoplastic from Glioblastomas using the database
gbm_Immune_Neoplastic.csv and evaluate the performance, discuss the results. 

1. Algorithm Explanation:
As our project was related to statistical machine learning model building. So fr building the machine learning model, we have used the python language as tools, Jupyternotebook as IDE and python libraries like Pandas, Numpy, Matplotlib, Seaborn, scikit learn and warning. Below I attached the screenshot of the modules used.

Uses of Libraries:
Pandas’ library is used for the data framing of our dataset as well as data manipulations in the vector form. While Matplotlib and seaborn libraries are used for the data visualizations in the graph format. Scikit learns library is used for algorithms implementations. It contains a list of machine learning libraries. As our project was related to the machine learning building model so we have used the classification model for our dataset. We have called the auto classifier from our Scikit-learn library and then implement it on our training dataset. This classifier is used and does work like automatics once the dataset is in the form of a group. As our dataset looks like in the clustering from so auto classifier work well properly.

Algorithms working mechanism:
As we have used the Random forest classifier used for the good classifications model. let us discuss how random forest classifier works and how they can be used.
> Randomforest Algorithm: As its name shows that it is the collections of a large number of an individual decision tree that operates as and assemble. Every individual tree of random forest classifier algorithm is split out in a class prediction and the greatest number of votes class will become our prediction model. It works like the correlation matrix and concurrent matrix as mathematically inside the algorithm.  It is the best-optimized algorithm, and its accuracy level is always high among all type of algorithms. This algorithm is able to handle the big data with multiple features of the dataset and trained it at the best level.
> AutoClassifier Algorithm: it is a type of inbuilt classifier that is optimized at a universal level or mixing of all types of classifier and make it robust. It is automatically based upon the intelligence of algorithms; accordingly, it classifies. just like if dataset pattern will binary then it binary classify while if the dataset pattern will be clustering then it will automatically be clustering the model. 
So, these two algorithms have used in our whole project scenario.  

2. Result and conclusions:
After using these algorithms, we have got the best accuracy of our model. Below I attached the screenshot output.
As we can see that the accuracy level of our model is showing nearly 95%. So, it was a very nice and robust model. because in the training model 95% and testing accuracy was also 92%. So really random forest algorithm has the best accuracy and robust model generated. The main conclusion we want to say that the random forest classifier has the best accuracy as compared to other models because it works as the decision trees and multiple layer pattern. 
The auto-classifier shows perfect performance, correctly classifying every instance in the testing subset. It achieved this with every short training time of only 60 seconds. It has to be noted, however, that the data is “easy” as the classes are very clearly separated, so we could have expected similar performance from much simpler classifiers like Logistic Regression or Naïve Bayes.
