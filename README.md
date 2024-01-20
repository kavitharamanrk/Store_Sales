# Stores Sales prediction
* From the requirement doct Department wise sales and weekly sales has to be predicted
* For Department wise sales, Sales data has taken which has department other two datasets are not relevant to this prediction
    * From the date feature week and year column created
    * added all sales amount based on grouped dept,week,year and is holiday feature
    * Has done all EDA process (null check, mapping/encoding, duplicates)
    * department, Is_holiday, week and year has selected for the model
    * model has created and pickle file also created
* For weekly sales, sales and feature datasets has taken for prediction
    * In sales dataset from the date feature week and year column created
    * added all sales amount based on grouped store,week,year and is holiday feature
    * In feature dataset from the date feature week and year column created
    * both feature and sales have merged for training the model
    * Has done all EDA process (null check, mapping/encoding, duplicates,finding outliers)
    * All the column have taken for prediction
    * model has created and pickle file also created
* Steamlit app created for prediction
* Based on selected prediction user should give the input then predict the sales
