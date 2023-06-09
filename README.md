# Parameter Optimization of Support Vector Machines

This project aims to explore the effectiveness of Support Vector Machines (SVM) in solving classification problems, with a focus on parameter optimization. In this project, we have taken a dataset and created 10 random samples to train and test our SVM model. Our goal was to identify the best SVM parameters that can yield the highest accuracy for each of the 10 samples.

We used the Scikit-learn library in Python to implement our SVM model and optimize its parameters. The dataset we used for this project was 
Chess (King-Rook vs. King) Data Set. After splitting the dataset into 10 random samples, we trained and tested our SVM model using various parameter combinations.

The final result of our project is a table that shows the accuracy of each of the 10 samples, along with the best SVM parameters that yielded the highest accuracy. This table can be used as a reference for future classification problems that require SVM parameter optimization.

## Dataset Description
This research aimed at the case of customers default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

### Attribute Information:

This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:
X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
X2: Gender (1 = male; 2 = female).
X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
X4: Marital status (1 = married; 2 = single; 3 = others).
X5: Age (year).
X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.
X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23

### Source
 UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients 
 
### Comparitive performance of Optimized-SVM with 10 samples
| Sample | Accuracy | Kernel | Nu   | C    |
| ------ | -------- | ------ | ---- | ---- |
| 1      | 0.80    | linear | 2.31  | 2.50   |
| 2      | 0.24    | linear | 6.44 | 1.71  |
| 3      | 0.78    | rbf    | 5.10 | 6.22  |
| 4      | 0.79    | rbf    | 3.30  | 9.50 |
| 5      | 0.77    | sigmoid| 7.48 | 2.50  |
| 6      | 0.70    | linear | 9.10  | 3.63   |
| 7      | 0.77    | sigmoid| 5.96 | 1.30    |
| 8      | 0.78    | rbf    | 4.07  | 2.15    |
| 9      | 0.27    | linear | 3.74 | 4.32   |
| 10     | 0.30    | poly   | 8.45  | 4.22  |


### Convergence Graph 

![image](https://user-images.githubusercontent.com/109303947/233127234-21d707dc-8ce7-452b-8817-0d7accee0c71.png)

