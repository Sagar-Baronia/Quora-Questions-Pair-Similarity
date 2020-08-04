# ***Quora-Questions-Pair-Similarity***
## *Classifying given pair of questions in Quora are Similar or not.*

*Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world. Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.*

## *Problem Statement :*
*Identify which questions asked on Quora are duplicates of questions that have already been asked.
This could be useful to instantly provide answers to questions that have already been answered.
We are tasked with predicting whether a pair of questions are duplicates or not.*

## *As a Machine Learning Challenge*

*It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not. Below is the Data Overview :*
1.   *Number of rows in the data set = 404,290*
2.   *Each row has 5 columns : qid1, qid2, question1, question2,is_duplicate* 

*Performance Metric : Log Loss and Binary Confusion Matrix*

*Train and Test Construction : We build train and test data set by randomly splitting in the ratio of 70:30*

***Conclusion :***
>*Implementing Logistic Regression on Feature Engineered Data Set, after appropriatly tuning the Hyper-Parameters, we are able to get log loss on Test Data as* ***0.4315***

>*Implementing Linear SVM on Feature Engineered Data Set, after appropriatly tuning the Hyper-Parameters, we are able to get log loss on Test Data as* ***0.4381***

>*Implementing XGboost for classification on Feature Engineered Data Set, after appropriatly tuning the Hyper-Parameters, we are able to get log loss on Test Data as* ***0.3554***
