# Project SVM for classification

## Problem
Apply SVM to identify if a cancer tumor is malignant or benign.

## Data Source
The [Breast Cancer](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29) datasets is available machine learning repository maintained by the University of California, Irvine. The dataset contains **569 samples of malignant and benign tumor cells**. 
* The first two columns in the dataset store the unique ID numbers of the samples and the corresponding diagnosis (M=malignant, B=benign), respectively. 
* The columns 3-32 contain 30 real-value features that have been computed from digitized images of the cell nuclei, which can be used to build a model to predict whether a tumor is benign or malignant.
  
1) ID number
2) Diagnosis (M = malignant, B = benign)
(3-32) The real-valued features are computed for each cell nucleus:
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
(1) Import libraries and load data <br />
(2) Exploratory Data Analysis <br />
(3) Data Visualization <br /> 
(4) Data Preprosessing and learn how to obtain the optimal number of clusters using the elbow method <br />
(5) Understand the theory and intuition behind Support Vector Machine algorithm <br />
(6) Model Evaluation <br />
(7) Optimizing the SVM Classifier <br />
(8) Automate the ML process using pipelines <br />

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

## Support Vector Machine Model
- It is a supervised machine learning problem where we try to find a hyperplane that best separates the two classes.
- SVM works best when the dataset is small and complex.
- Support Vectors: These are the points that are closest to the hyperplane.
- Margin: it is the distance between the hyperplane and the observations closest to the hyperplane.
- The best hyperplane is that plane that has the maximum distance from both the classes.
![plot](https://user-images.githubusercontent.com/81390746/284029389-fc91640e-2d26-4714-a3e6-1987ef1d71ca.png)

## Model Evaluation 
- Confusion Matrix
- Receiver Operating Characteristic curve (ROC), AUC

## Optimizing the SVM models
- Grid Search

## Create SVM Pipeline
