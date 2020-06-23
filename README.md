# Machine-Learning-in-Python-Performing-Principal-Component-Analysis-PCA-on-Breast-Cancer-Wisconsin

## Table of Contents:
1. Load Breast Cancer Wisconsin Diagnostic data set
2. Assigning Input (X) and Output (Y) variables
3. Data scaling
4. Perform PCA analysis
5. Explained variance for each PC
6. Making the scree plot
7. Scores Plot
8. 3D Scatter Plot

## Load Breast Cancer Wisconsin Diagnostic data set:

From Sklearn import the dataset using load_breast_cancer()


## Assigning Input (X) and Output (Y) variables:

- Let's assign the 30 input variables to X and the output variable (class label) to Y

## Data scaling:
-  It is necessary to normalize data before performing PCA. The PCA calculates a new projection of your data set. And the new axis are based on the standard deviation of your variables. So a variable with a high standard deviation will have a higher weight for the calculation of axis than a variable with a low standard deviation. If you normalize your data, all variables have the same standard deviation, thus all variables have the same weight and your PCA calculates relevant axis.

## Perform PCA analysis:
- define the number of PC to be 3.
- Compute and retrieve the scores values
![](https://github.com/Subramaniam-dot/Machine-Learning-in-Python-Performing-Principal-Component-Analysis-PCA-on-Breast-Cancer-Wisconsin/raw/master/imag2.1.JPG)

- Retrieve the loadings values
[]()

## Explained variance for each PC:

- The fraction of variance explained by a principal component is the ratio between the variance of that principal component and the total variance.
- The Cumulative variance  gives the explained variance accounted for by the first n components. For example, the cumulative  for the second component is the sum of the explained variance for the first and second components.
- Prepare the explained variance and cumulative variance
- Combining the dataframe of PC, explained variance and cumulative variance.
[]()

## Scree Plot:

### Bar Plot of Explained Variance Vs PC:
[]()

### Combined Plot of Explained Variance, Cumulative Variance Vs PC:
[]()

### Seperate Scatter plot for Cumulative Variance Vs PC and Explained Variance Vs PC:
[]()

### 3D Scatter Plot:
[]()

### Loadings Plot:
[]()

#### Reference:
1. https://www.researchgate.net/post/Is_it_necessary_to_normalize_data_before_performing_principle_component_analysis
2. https://ro-che.info/articles/2017-12-11-pca-explained-variance#:~:text=The%20fraction%20of%20variance%20explained,divide%20by%20the%20total%20variance.
3. https://www.ibm.com/support/knowledgecenter/SSLVMB_23.0.0/spss/tutorials/fac_cars_tve.html



