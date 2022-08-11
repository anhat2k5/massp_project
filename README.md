                                                                  MASSP_PROJECT
  
    I. TOPIC
- Hi everyone, I'm Nhật, a mentee of MASSP 2022. In this project, I would like to do research about House Price Prediction Model.
- _House prices are increasing every year, so it is essential to have a system to predict house prices in the future. Being able to predict house price can help developer and customer to arrange a suitable time to purchase a house. This project aims to predict house prices in Ames, Iowa based on some basic regression analysis._

  II. Dataset
- The data used in this project is provided on Kaggle at: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
- The training set has 81 columns and 1460 rows.
- The test set has 80 columns (without the SalePrice column that we have to predict) and 1459 rows.

  III. Orientation
- First, we have a large number of features. We need to identify several key factors that affect most the SalePrice. These factors should be considered with more attention than others. GrLivArea,TotalBsmtSF,OverallQual , GarageCars etc. seems to have high correlation with SalePrice.
- Secondly, we need to deal with missing values. If more than 50% rows of a specific column are null, that column should be deleted (drop that column). If a column has a few null row, we should fill those null data with the means of that column (basically replace the missing values with the means of the same column).
- Finally, I intend to use Random Forest algorithm in this project. Random Forest is based on the bagging algorithm and uses Ensemble Learning technique, which can reduce overfitting problem in decision trees and also reduce the variance and therefore improves the accuracy.
