# Statistical-Learning-and-Modeling 
## Files in the Repository
### Examining_Bird_Diversity 
- The goal of this project is to familierize with EDA, and explore the Bird Diversity data
- I focused on heterozygosity, to uncover patterns that shape our understanding of bird populations and their resilience
- **Data Cleaning** includes checking missing values, detecting outliers of different columns by various kind of plots, eliminating outliers by IQR
- **Data Exoloratory** includes finding correlation between Heterozygosity and other variable. (Heterozygosity vs. categorical, Heterozygosity vs. numerical), and some more interesting findings

### Flight_Delay 
- The goal of this project is to use **_linear regression_** to model fight delays as a function of other variables 
- **Data Preprocessing** includes eliminating uninformative columns, discarding rows with NaNs, applying log transformation to columns according to skewness, and removing outliers using z-score.
- **Data Training** includes splitting the dataset into test and train sets, conducting linear regression, generating predictions for the test set, and calculating the MSE between the test and train data.
- **Data Analysis** for column selection involves:
  1. Observing multicollinearity through **_Variance-Inflation Factors (VIF)_**
  2. Utilizing **_Best-Subset Selection Analysis (BSS)_** for identifying informative predictors
  3. Applying **_Principal Component Analysis (PCA)_** to determine the optimal number of PCs to retain
  4. Comparing the resulting MSEs from the aforementioned methods
     
### Classify_Kepler 
- The goal of this project is to do prediction on **Classification**
- **Data Training** model usage:
  1. **_Logistic Regression_**: Computed the **_Confusion Matrix_** to check the model performance
  2. **_Random Forest_**: Plotted a Random Forest Variable Important Plot (VIP) to find out the ranking of the variable importance
  3. _**Gradient Boosting** **(xgboost)**_: Created a bar graph representing Gradiant boosting VIP
  4. **_K-Nearest Neighbour (KNN)_**: Plotted a MCR vs. k in KNN Classification to find the optimal number of nearest neighbor
- **Model Comparison**:
  1.  Compare the **_Misclassification Rate (MCR)_**, and Accuracy between models
  2.  Plotted a **_Receiver Operating Characteristic curve (ROC)_** of the above models and compare the **_Area Under the Curve (AUC)_**:
<img width="702" alt="Screen Shot 2024-02-21 at 8 35 39 PM" src="https://github.com/anzowu527/Statistical-Learning-and-Modeling/assets/77874807/960b1842-ba0e-457d-8a8c-dec3e4447bf4">

### Diamond_Price_Prediction 
- Our Poster of the Project is available at: https://www.stat.cmu.edu/capstoneresearch/
- The goal of the project is to predict diamond price by diamond's properties
<img src="https://github.com/anzowu527/Statistical-Learning-and-Modeling/assets/77874807/1b0f65aa-9366-4255-8631-b56d2fcedeb5" width="900">


