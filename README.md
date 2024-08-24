Import Libraries: Necessary libraries for data analysis, visualization, preprocessing, and modeling are imported.
Load and Explore Data: The Big Mart Sales dataset is loaded and its structure is examined.
Handle Missing Values: Missing values in 'Item_Weight' and 'Outlet_Size' are filled using mean and mode respectively.
Visualize Data: Distributions of numerical features and counts of categorical features are visualized.
Preprocess Data: Inconsistent values in 'Item_Fat_Content' are corrected, and categorical features are encoded into numerical labels.
Split Data: The dataset is split into training and testing sets for model training and evaluation.
Train Model: An XGBoost regression model is trained on the training data to predict item outlet sales.
Evaluate Model: The model's performance is assessed using the R-squared metric on both training and testing sets.
File link: **https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data**
