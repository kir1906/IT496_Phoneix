# IT496_Phoneix
- This repository is about diamond dataset. This data set is collected from kaggle. The dataset is intended for use in Data visulization through EDA, data preprocessing, transformation, corelation, data split, hyperparameter, modal selection.The dataset file in CSV(Comma Separated Value) format containing the diamond data.

- The dataset include varios attributes such as 'cut', 'color', 'clarity', 'carat_weight', 'cut_quality','lab', 'symmetry', 'polish', 'eye_clean', 'culet_size','culet_condition', 'depth_percent', 'table_percent', 'meas_length','meas_width', 'meas_depth', 'girdle_min', 'girdle_max', 'fluor_color',    'fluor_intensity', 'fancy_color_dominant_color','fancy_color_secondary_color', 'fancy_color_overtone','fancy_color_intensity', 'total_sales_price', 'cut_pre', 'color_pre','clarity_pre', 'cut_quality_pre', 'lab_pre', 'symmetry_pre','polish_pre', 'eye_clean_pre', 'culet_size_pre','fancy_color_intensity_pre', 'fancy_color_overtone_pre',  'fancy_color_secondary_color_pre', 'fancy_color_dominant_color_pre','girdle_max_pre'. 

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
