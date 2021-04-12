
# [Project 1: Data PreProcessing](https://github.com/saqibijaz/Data-Preprocessing-Pandas)
## Pandas
* Used Pandas for performing different task related to Data Preprocessing.
* Drop Columns who have more than 50 percent missing values.
* Replace missing values with Median/Mean.
* Replace missing address with a default address.
* Replace missing DataFrame with whatever.
* Select those who are Males and Survivors.
* select the percentage of Males/Females.
* Select those who are survivors and has siblings = 2.

# [Project 2: KNN & Linear Regression from Scratch](https://github.com/saqibijaz/KNN-LinearRegressionFrom-Scratch)
## K Nearest Neighbours
* Downloaded the Iris Dataset.
* Loading the Dataset into Pandas Dataframe.
* Dividing the data into Test & Train (70 30).
* Creating a class KNN
* Function Predict() predicts the output.
* Function Compute Distance() compute the distance between sample and all other data and return the distance vector.
* Function Fit() starts training the Model.

## Linear Regression
* Loading the Dataset into Pandas Dataframe.
* Dividing the data into Test & Train (70 30).
* def hyp(X,theta) performs mx in y = mx
* def cost_function(theta,X,Y) returns the error in the prediction. 
* def derivative_cost_function(theta,X,Y,alpha) finds the derivative.
* def GradientDescent(X,Y,thetas,cost_function,derivative_cost_function,maxniter=20000) it's the learning algorithm, which keeps on running until 20000 iterations.
 
![](/images/LR.png)

# [Project 3: Deciscion Tree of Continous Variable from Scratch](https://github.com/saqibijaz/Deciscion-Tree-Continous-Variable)
## Deciscion Tree Continous Variable
* A decision Tree for continous Variables.
* It can have n number of features and it can predict a continous value.
* Continous Value means that it won't predict a yes or a no, rather it can predict the value, say 0.5
* It works on the principle of entropy (impurity).
* Selects the node which gives the most information, related to the class.
