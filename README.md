# Statistical-Learning-and-Modeling 
## Files in the Repository
### Examining_Bird_Diversity 
- The goal of this project is to familierize with EDA, and explore the Bird Diversity data
- I focused on heterozygosity, to uncover patterns that shape our understanding of bird populations and their resilience
- **_Data Cleaning_** includes checking missing values, detecting outliers of different columns by various kind of plots, eliminating outliers by IQR
- **_Data Exoloratory_** includes finding correlation between Heterozygosity and other variable. (Heterozygosity vs. categorical, Heterozygosity vs. numerical), and some more interesting findings

### Flight_Delay - The goal of this project is to use linear regression to model fight delays as a function of other variables 
- **_Data Preprocessing_** includes eliminating uninformative columns, discarding rows with NaNs, applying log transformation to columns according to skewness, and removing outliers using z-score.
- _**Data Training**_ includes splitting the dataset into test and train sets, conducting linear regression, generating predictions for the test set, and calculating the MSE between the test and train data.
- **_Data Analysis_** for column selection involves:
  1. Observing multicollinearity through **_Variance-Inflation Factors (VIF)_**
  2. Utilizing **_Best-Subset Selection Analysis (BSS)_** for identifying informative predictors
  3. Applying **_Principal Component Analysis (PCA)_** to determine the optimal number of PCs to retain
  4. Comparing the resulting MSEs from the aforementioned methods
     
### Classify_Kepler 
### Diamond_Price_Prediction - Our Poster of the Project is available at: https://www.stat.cmu.edu/capstoneresearch/

