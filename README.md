# DecisiO

Contributed with Java as an android developer to DecisiO, Hack-A-Bit which served as a daily life suggester based upon user’s past choices.

Aim: To provide a personal suggester in form of an android app. This app initially has capabilities of suggesting 5 things, namely Food, Cloth, Activity to do, Music and Place to visit.

Tech Stack: Python, Android, Machine Learning, Flask API, and Heroku (for deployment).

Work flow: 
1. The features for the above mentioned 5 queries were decided.
2. Features include Salary Range, Age, Per Month Expenses, Gender, etc.
3. A total of 102 features were written.
4. With the help of Data Generation techniques, dataset of 5000 units was made.
5. Various types of Machine Learning algorithms were used.

Following accuracies were obtained :-
1. Random Forest Classifier: 70.4 %
2. Decision Tree Analysis:  65.2 %
3. Logistic Regression: 40 %
4. Support Vector Machines (SVM): 44.5 %
5. K Nearest Neighbours: 71.4 %

Separate models were made for each query, i.e. 5 different models were trained for 5 queries. Each of them was hosted on Heroku. Then, using Post requests and Flask API, the model weights and data were updated continuously. The android app contains questions for the user. He/She will be asked for a frequency for questions to be asked regularly at the start of the app. After that, he will have 2 options either to ask a question or to answer a question.
