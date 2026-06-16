# Intro-to-Machine-Learning
Kaggle Machine Learning
Step 1 :
1. Environment PreparationImported Pandas: You loaded the essential Python library used for data manipulation and analysis.
2. Data IngestionDefined File Path: You specified the exact directory location of your raw housing dataset.Loaded Dataset: You used Python to read the CSV file and store it as a DataFrame object in your environment.
3. Data InspectionInitiated Exploration: You called the descriptive statistics function to automatically calculate summary metrics like mean, count, and standard deviation for your dataset features.
   
Step 2:

1. Loaded and Cleaned the DataYou imported the pandas library.You read the raw Iowa housing CSV file into a DataFrame named home_data.You inspected the data patterns and counts using the .describe() function.
2.  Isolated Target and FeaturesDefined the Target (y): You selected the SalePrice column as the exact value you want your model to predict.Defined the Features (X): You selected a specific list of relevant columns (like LotArea, YearBuilt, and room counts) to serve as the inputs for your model.
3.   Built and Trained the ModelYou imported the DecisionTreeRegressor algorithm from the scikit-learn library.You initialized the model and set a random_state=1 to guarantee your results stay consistent.You called .fit(X, y) to let the model study your data and learn the mathematical relationships between the features and house prices.
4.  Generated PredictionsYou isolated the data for the first five houses using X.head().You passed those five houses into iowa_model.predict().The model successfully outputted its very first 5 price predictions based on what it learned.
