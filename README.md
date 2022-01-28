##  Ames Housing Data and Kaggle Challenge

The goal of this project is to predict the price of homes at sale for the Ames Iowa Housing dataset, which was provided by Kaggle in this [site](https://www.kaggle.com/c/dsi-us-11-project-2-regression-challenge/overview)

By exploring the dataset with 80 attributes related to the sale of the property, we will gain insight of which variables drives the Sale Price and create several regression models by selecting set of fields through iterative process, and choose the best one that can closely estimate the sale price.

To better understand the dataset, refer to this [data description](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt).



#  Directory Structure

```
project-2
|__ code
|   |__ 01_EDA_and_Cleaning-final.ipynb   
|   |__ 02_Preprocessing_and_Feature_Engineering-final.ipynb   
|   |__ 03_Model_Benchmarks_TUning-final.ipynb
|__ data
|   |__ train.csv
|   |__ test.csv
|   |__ train_preproc_final.csv
|   |__ test_preproc_final.csv
|   |__ train_wfeatures.csv
|   |__ test_wfeatures.csv
|   |__ submit_lreg.csv
|   |__ submit_ridgeregreg.csv
|   |__ submit_lassoreg.csv
|   |__ submit_enetreg.csv
|__ README.md
