# Decision Tree implementation for IRIS dataset


A decision tree is a flowchart kind of structure in which each node is test_case on some attribute, each branch tells the outcome of that test, and each leaf node is a class label. 
The paths from root to leaf represent classification rules.

A Decision tree is a supervised machine learning tool used in classification problems to predict the class of an instance.
This project represents about how this decision tree is formed using gain ratio as a objective matric


# About IRIS dataset
Here, inbuilt IRIS dataset is being used which is available in scikit_learn datatsets.
IRIS dataset consists of continuous values therfore to reduce the complexity of Decision_Tree I have calssified the dataset into four class named 'a','b','c', and 'd' with help of three boundaries which are:
			
			First_boundary is at ((mean of the column + minimun of the column)/2) 
			
			Second boundary is at mean of that particular column and,
			
			Third boundary is at ((mean of the column + maximum of the column)/2).

Using these three boundaries the dataset is been classified in four class.

