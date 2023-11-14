# Project---SVM-for-classification
# Project: Unsupervised Machine Learning for Customer Market Segmentation

## Problem
Apply SVM to classify Cancer tumor

The [Breast Cancer](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29) datasets is available machine learning repository maintained by the University of California, Irvine. The dataset contains **569 samples of malignant and benign tumor cells**. 
* The first two columns in the dataset store the unique ID numbers of the samples and the corresponding diagnosis (M=malignant, B=benign), respectively. 
* The columns 3-32 contain 30 real-value features that have been computed from digitized images of the cell nuclei, which can be used to build a model to predict whether a tumor is benign or malignant.
* 

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

	a) radius (mean of distances from center to points on the perimeter)
	b) texture (standard deviation of gray-scale values)
	c) perimeter
	d) area
	e) smoothness (local variation in radius lengths)
	f) compactness (perimeter^2 / area - 1.0)
	g) concavity (severity of concave portions of the contour)
	h) concave points (number of concave portions of the contour)
	i) symmetry 
	j) fractal dimension ("coastline approximation" - 1)

 
## Data Columns
| Column | Description |
| --- | --- |
| CUSTID | Identification of Credit Card holder |
| BALANCE | Balance amount left in customer's account to make purchases |
| BALANCE_FREQUENCY | How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated) |
| PURCHASES | Amount of purchases made from account |
| ONEOFFPURCHASES | Maximum purchase amount done in one-go |
| INSTALLMENTS_PURCHASES | Amount of purchase done in installment |
| CASH_ADVANCE | Cash in advance given by the user |
| PURCHASES_FREQUENCY | How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased) |
| ONEOFF_PURCHASES_FREQUENCY | How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased) |
| PURCHASES_INSTALLMENTS_FREQUENCY | How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done) |
| CASH_ADVANCE_FREQUENCY | How frequently the cash in advance being paid |
| CASH_ADVANCE_TRX | Number of Transactions made with "Cash in Advance" |
| PURCHASES_TRX | Number of purchase transactions made |
| CREDIT_LIMIT | Limit of Credit Card for user |
| PAYMENTS | Amount of Payment done by user |
| MINIMUM_PAYMENTS | Minimum amount of payments made by user |
| PRC_FULL_PAYMENT | Percent of full payment paid by user |
| TENURE | Tenure of credit card service for user |


## Tasks:
(1) Understand the problem statement and business case <br />
(2) Import libraries and datasets <br />
(3) Visualize and explore datasets <br /> 
(4) Understand the theory and intuition behind k-means clustering machine learning algorithm <br />
(5) Learn how to obtain the optimal number of clusters using the elbow method <br />
(6) Use Scikit-Learn library to find the optimal number of clusters using elbow method <br />
(7) Apply k-means using Scikit-Learn to perform customer segmentation <br />
(8) Apply Principal Component Analysis (PCA) technique to perform dimensionality reduction and data visualization. <br />



# Takeaways
## Identifying and Dealing with Missing Values
- 313 Missisng Values in 'MINIMUM_PAYMENT' <br />
- Replace missing values in 'MINIMUM_PAYMENT' with mean of the 'MINIMUM_PAYMENT' 

## Visualizing the data
- distplot combines the matplotlib.hist function with seaborn kdeplot() <br />
  * KDE Plot represents the Kernel Density Estimate. 
  * KDE is used for visualizing the Probability Density of a continuous variable.
  * KDE demonstrates the probability density at different values in a continuous variable.

## Scaling the data

## Model used
- K-Means and Elbow method to determine K (7)

## Combine original df to K-means label

## Visualizing results using Principal Component Analysis (2 Components)

![plot](https://user-images.githubusercontent.com/81390746/282326280-583d093c-3691-4591-ba18-8b9d04c49dfa.png)





