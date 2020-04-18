
Melbourne House Price Prediction
================================

This repo is the summary for the work of Melbourne house price prediction.

### Report

Under [`report`](https://github.com/Jiaying-Wu/Melbourne-House-Price-Prediction/tree/master/report) folder, contain source code for reporting.

-   [`report/README.Rmd`](https://github.com/Jiaying-Wu/Melbourne-House-Price-Prediction/blob/master/report/README.Rmd): R markdown to provide data insight of Melbourne house price data.

Further report detail under [report](https://github.com/Jiaying-Wu/Melbourne-House-Price-Prediction/tree/master/report) folder.

### Data Processing

Under [`process`](https://github.com/Jiaying-Wu/Melbourne-House-Price-Prediction/tree/master/process) folder, contain source code for data processing.

-   [`process/spilt_train_data.R`](https://github.com/Jiaying-Wu/Grocery-Sales-Forecasting/blob/master/process/spilt_train_data.R): R Script to split training data at local train set and local test set under 85/15 ratio.

Further processing detail under [process](https://github.com/Jiaying-Wu/Melbourne-House-Price-Prediction/tree/master/process) folder.

### Data Modeling

Under [`model`](https://github.com/Jiaying-Wu/Melbourne-House-Price-Prediction/tree/master/model) folder, contain source code of models to predict Melbourne house price:

-   [`model/model_decision_tree.R`](https://github.com/Jiaying-Wu/Melbourne-House-Price-Prediction/blob/master/model/model_decision_tree.R): R Script of Decision Tree Model.

-   [`model/model_random_forest.R`](https://github.com/Jiaying-Wu/Melbourne-House-Price-Prediction/blob/master/model/model_random_forest.R): R Script of Random Forest Model.

-   [`model/model_gbm.R`](https://github.com/Jiaying-Wu/Melbourne-House-Price-Prediction/blob/master/model/model_gbm.R): R Script of Gradient Boosting Model.

Further modeling detail under [model](https://github.com/Jiaying-Wu/Melbourne-House-Price-Prediction/tree/master/model) folder.

### Data Source

Data source from Monash University, access the data from this competition [vitticeps](https://www.kaggle.com/c/vitticeps/data) in Kaggle.

14 Features in this dataset:

1.  `id`: unique id for property.

2.  `suburb`: suburb location of property.

3.  `result`: `S` indicates property sold; `SP` - property sold prior; `PI` - property passed in; `PN` - sold prior not disclosed; `SN` - sold not disclosed; `NB` - no bid; `VB` - vendor bid; `o res` - other residential; `w` - withdrawn prior to auction.

4.  `rating`

5.  `nbeds`: number of bedrooms.

6.  `property_type`: `h` = house, `t` = townhouse, `u` = unit/apartment.

7.  `day`: day of the month of auction.

8.  `month`: month of auction.

9.  `year`: year of auction.

10. `nvisits`: How many people came to open houses.

11. `ncars`: Number of parking places.

12. `nbaths`: Number of bathrooms.

13. `land_size`: Size of the lot, in sq m, units will be 0.

14. `house_size`: Internal size of property in sq m.
