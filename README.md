<h3>Aim Of The Project</h3>

This project uses different machine learning techniques to predict the price of laptops based on various features such as company, OS, Ram etc. By analyzing the relationship between these features and the price, the model provides accurate estimations that can help users make informed purchasing decisions.



<h3>Technologies Used:</h3>

Python: Core programming language for data analysis and modeling.

Pandas: Data cleaning and preprocessing.

Matplotlib & Seaborn: Visualization of data and insights.

Scikit-learn: Implementation of machine learning algorithms.



<h4>Algorithm Used:</h4>

<h2>Linear Regression</h2>


Linear Regression is a supervised learning algorithm used for regression tasks, where the goal is to predict a continuous target variable based on input features. It assumes a linear relationship between the dependent variable (target) and one or more independent variables (features).

**Regression Line:**
The algorithm fits a line (or hyperplane in higher dimensions) to the dataset. The line minimizes the difference between the actual and predicted values using the Least Squares Method.

**Cost Function:**
Linear Regression uses a cost function, such as Mean Squared Error (MSE), to measure the accuracy of predictions. The algorithm optimizes the coefficients to minimize this error.
                                 
​

<h2>Decision Tree:</h2>

A decision tree (DT) is a supervised learning technique that is mostly used for classification tasks and is also helpful in discovering relevant features and patterns in large databases, thus serving as a powerful means of discrimination and predictive modeling [19]. Each node in a Decision tree, or Decision node and Leaf node, consists of a test for an attribute, which creates one of the two branches in the tree that descends from that node.

Algorithm-

• Construct tree with nodes as input feature.

• Select feature to predict the output from input feature whose information gain is highest.

• The highest information gain is calculated for each attribute in each node of tree.

• Repeat step 2 to form a subtree using the feature which is not used in above node.


<h2>Random Forest Classifier:</h2>

It is an ensemble learning method that uses multiple decision trees, It is type of ensemble learning method and also used for classification and regression tasks. The accuracy it gives is grater then compared to other models. This method can easily handle large datasets. Random Forest is developed by Leo Bremen. It is popular ensemble Learning Method. Random Forest Improve Performance of Decision Tree by reducing variance. It operates by constructing a multitude of decision trees at training time and outputs the class that is the mode of the classes or classification or mean prediction (regression) of the individual trees.

Algorithm-

• The first step is to select the “R” features from the total features “m” where R<<M.
• Among the “R” features, the node using the best split point.
• Split the node into sub nodes using the best split.
• Repeat a to c steps until ”l” number of nodes has been reached.
• Built forest by repeating steps a to d for “a” number of times to create “n” number of trees.
