# IT496_Phoneix
- This repository is about diamond dataset. This data set is collected from kaggle. The dataset is intended for use in Data visulization through EDA, data preprocessing, transformation, corelation, data split, hyperparameter, modal selection.The dataset file is in CSV(Comma Separated Value) format containing the diamond data.

**Data Description**
- cut : Quality of the Diamond's cut.
- color : Colour of the diamond.
- clarity : Level of clarity or purity of the diamond.
- carat_weight : Weight of the diamond in carats.
- lab : Laboratory that has graded or certified the diamond's.
- symmetry : Reflects the symmetry of the gemstone's facets.
- polish : Quality of the diamond's surface.
- eye_clean : Indicates whether the diamond appears clean to the naked eye.
- culet_size : Size of the culet.
- culet_condition : Condition of the culet
- depth_percent : Depth of the gemstone in percentage.
- table_percent : Size of the flat facet on the top of the diamond in percentage.
- meas_length : Length of the diamond.
- meas_width : Width of the diamond.
- meas_depth : Depth of the diamond.
- girdle_min and girdle_max : Minimum and Maximum thickness of the girdle.
- fluor_color and fluor_intensity : Any fluorescence observed in the gemstone under UV light, including the color and intensity of the fluorescence.
- fancy_color_dominant_color and fancy_color_secondary_color : If the diaond is a fancy colored, indicating the primary and secondary colors present.
- fancy_color_overtone : Describes the colored inclusions.
- fancy_color_intensity : Intensity or saturation of the fancy color
- total_sales_price : Total price of the diamond.

**EDA**
- Exploratory Data Analysis (EDA) to gain insights into diamond characteristics.
- In EDA we provide data visualisation in different graph method like pair plot, cat plot, subplot, data distribution plot, pie chart, scatter plot. EDA summarize the main behaviour, features, and patterns in a dataset. Pair plot contains scatter plot of meas_length, meas_width, total_sales_price, meas_depth, table_percent, depth_percent. Distribution plot of carat_weight is shown. And pie chart of color, clarity, cut, lab. And scatter plot of carat_weight with respect with total_sales_price. 

**Data Preprocessing and Transformation**
- Data preprocessing and transformation involve cleaning, organizing, and structuring raw data to make it suitable for analysis or model training.
- Data preprocessing is the initial step in data preparation, where the raw data is cleaned and prepared for further analysis. This step involves several tasks:
- Data transformation involves converting data into a different format or structure to meet the requirements of specific analysis techniques or machine learning algorithms

 **Regression model building, Hyperparameter Tuning and Model evaluation**
- Building a regression model involves several key steps, such as model selection, hyperparameter tuning and model evaluation.
- There are many regression model available to use, they can selected based on the nature of the problem.
- Such models are, Linear Regression, Polynomial Regression, Ridge Regression, Lasso Regression, Decision Tree, Random Forest, etc.
- Hyperparameters are configuration settings for the regression algorithm
- Yechniques like grid search or randomized search can be used find the best combination of hyperparameters that optimize the model's performance.
- Cross-validation assess how well the model generalizes to unseen data at each combination of hyperparameters.
- Model evaluation is a process to find the prediction of the trained model on the testing dataset or new, unseen data.
- The model's performance can be evaluated by evaluation metrices such as Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, etc.

**T2 Identified list regression problems :**
- total sales price prediction 
Predicting the total_sales_price of a diamond is valuable beacuse it is depended on cut quality, color, clarity, Symmetry and Polish. Simply it relies on every attribute

- carat_weight prediction
carat weight is function of length, width and depth of the diamond.

- table percent 
table percent is function of table width and diameter of diamond. So it can be predicted easily.




Which one does seem the most interesting to you and why?
- Predicting the total_sales_price of a diamond is valuable beacuse it is depended on cut quality, color, clarity, Symmetry and Polish. Comparatively total_sales_price relies on every attribute. Total sales price seems most interesting because it allows buyers to make informed purchasing decisions based on price expectations. Sellers can use it to set competitive prices, and investors can assess the potential return on investment in diamonds. Prediction of total sales price helps assess risk in diamond transactions. It can be used to evaluate whether a seller is offering a fair price for a diamond based on its characteristics. If you are in the business of buying or selling diamonds, regression models can help you optimize pricing strategies. Utilizing regression analysis to predict total sales price can give your business a competitive advantage by offering pricing that reflects market dynamics and the value of individual diamonds accurately.
