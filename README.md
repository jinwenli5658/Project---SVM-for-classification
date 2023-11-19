# Project-SVM-for-classification

## Problem
Apply SVM to identify if a cancer tumor is malignant or benign.

## Data Source
The [Breast Cancer](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29) datasets is available machine learning repository maintained by the University of California, Irvine. The dataset contains **569 samples of malignant and benign tumor cells**. 
* The first two columns in the dataset store the unique ID numbers of the samples and the corresponding diagnosis (M=malignant, B=benign), respectively. 
* The columns 3-32 contain 30 real-value features that have been computed from digitized images of the cell nuclei, which can be used to build a model to predict whether a tumor is benign or malignant.
  

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
## Exploratory Data Analysis and visualization
- Histogram
- Density 
- Box and Whisker Plot
- Correlation Matrix
- Scatter Plot

## Data Preprocessing
- Y: relabeling
- X: rescaling and dimension reduction (PCA)
- Elbow Method: keep first three PCA

## Support Vector Machine Mode
- It is a supervised machine learning problem where we try to find a hyperplane that best separates the two classes.
- SVM works best when the dataset is small and complex.
- Support Vectors: These are the points that are closest to the hyperplane.
- Margin: it is the distance between the hyperplane and the observations closest to the hyperplane.


![plot](https://user-images.githubusercontent.com/81390746/284029389-fc91640e-2d26-4714-a3e6-1987ef1d71ca.png)






## Scaling the data

## Model used
- K-Means and Elbow method to determine K (7)

## Combine original df to K-means label

## Visualizing results using Principal Component Analysis (2 Components)

![plot](https://user-images.githubusercontent.com/81390746/282326280-583d093c-3691-4591-ba18-8b9d04c49dfa.png)





