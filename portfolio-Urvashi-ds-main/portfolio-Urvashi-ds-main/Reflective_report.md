# Reflective report

### Introduction
Through the reflective report, I am describing insights for my learning, analyzing, and research processes from this unit. I also describe portfolio4.

### Process of solving problems and learning notebook:
For solving any problem given, I start with understanding the problem given in the question. I check the features in a data file (CSV, Xls), understand the concepts of the model and/or method to implement, and then execute it. For understanding concepts, I usually go through lecture notes, videos, and if necessary and then search directly on Google-YouTube. Lastly, I analyze the task and try to do it with different approaches and finally select the best one. 

Basically, for every data problem, I followed the CRISP-DM model explained in the unit. According to it, I first understand the business question; then explore the data frame by descriptive statistics to see distributions, outliers if any i.e. Data understanding; followed by cleaning, encoding, etc i.e. Data preparation; then training and testing data by analyzing which model gives the best accuracy i.e. Data Modeling; Evaluation, and Deployment. The stages are followed in sequence but all are not necessary during solving problems.

Jupyter notebook is used here as it is easy to execute. It is also good for testing code quickly. If we want to run codes for machine learning and others, we might need extra effort in downloading some of the libraries on our system which is a bit time-consuming.  Most of the libraries are installed e.g. sci-kit learn. I learned how to execute commands, use kernel, and markdown in the notebook during the practical workshops. We can format files with different file formats when necessary.

### Unit learning insights:
At the beginning of the unit, I learned basic python syntax, library, and execution in notebooks; thereafter, the unit elaborated from theoretical data science concepts such as Fermi estimation which taught me to think about any problem more critically with the famous piano tunners example; CRISP-DM is a theoretical model which explains the process of solving any business problem or implement to decide any business logic; various models and methods such as various regression and classifiers.

CRISP-DM model helps me evaluate data problems. It covered topics like data exploration, data preparation, data cleaning, data training, model prediction, and evaluation.

It covered my knowledge of descriptive statistics and data privacy. Also, improve my knowledge of machine learning concepts like supervised and unsupervised learning; covered deep learning topics like neural networks and decision tree models. I learned the use of clustering and classification algorithms.

In a guest lecture, I found insights into using software engineering with data science explained. This makes me interested more in understanding the connection between statistical analysis and the engineering point of view for any business logic.

This unit gave me insights into how to understand and solve the problem of the data science field. I got hands-on experience in real-time datasets and graph understanding. In the future, I would like to learn more about data analysis with machine learning as it interested me more.

### About Portfolio4:
The data analysis and prediction in portfolio4 are about Airline Passenger Satisfaction. Going through several aspects like Class, Delays, Time convenience, Onboard services, etc. The calculations are for how much the experience is satisfactory to every passenger.

#### How I found this problem -
As going through different areas, I found this interesting because of my interest and curiosity. When I first travel to Australia, I was excited about the experience on the flight. I got curious about airplane companies' popularity with the experience of passengers like how they are reviewing each small aspect to see which thing to improve. This enlightened me for my topic on portfolio4 which covers the experience of airplane passengers is satisfiable or not.

#### Why I select this dataset and which models I used -
I select Kaggle for taking datasets as it is a free and open platform where I get any kind of different-sized data. I selected this dataset as lots of features were included in many features were included in it translations, I used various methods for accuracy testing, graphs, regression, and classification models. Linear regression helps to see the relationship between various features. We want to be our result as yes or no, i.e. Passenger is satisfiable or not; this will give 0 and 1 results which we can also see in the graph. As our problem is a classification problem, I used various classification models such as Logistic regression, k-nearest neighbors, Naive Bayes, and Support Vector Classifiers.

#### Why I used that model -
First, I mentioned logistic regression which measures the relationship between the categorical dependent variable (feature) and one/more independent variables by estimating probabilities. I also used the Recursive Feature Estimation method for better performance of logistic regression as it removes features one by one, evaluating the model each time and selecting the best model for a target number of features.

#### What else I mentioned calculating with and why -
Accuracy score which measures model performance in terms of a sum of true positive and true negative out of predictions made. The confusion matrix visualizes and summarizes the performance, F1-score which is used to compare two classifiers, AUC-ROC Curve for seeing how well a logistic regression model classifies positive and negative outcomes.

#### Describing models -
As logistic regression with the RFE method, I have used the KNN model and compared it by hyper-tuning it with the GridSearchCV function which gives the K value number which has the best accuracy score. Naive Bayes classifier, which is highly scalable; and SVC which maps data points to a high-dimensional space and then finds the optimal hyperplane that divides the data into two classes.

#### Final results -
Giving final insights, the use of all these classification models is to show the efficiency and accuracy of the model with the type of problem. In my task, it is more likely to fall on 0 and 1 results; making the logistic regression model best suited. Also, a supervised learning algorithm will be used so the Naive Bayes Classifier, which assumes each input variable is independent is also best suited for this problem. The accuracy score of both models is almost similar in the evaluation.
