<h1>Laptop Price Prediction</h1>

This project aims to predict Laptop Price Prediction based on data and various influencing factors such as Name, Brand, Processor gen, Core per processor, Price, Rating, Processor brand, Energy efficient. The goal is to developed machine learning model that can accurately forecast Laptop price to help purchase make informed decisions.

 <h1>Project Overview:</h1>

Laptop prices fluctuate based on several variables, including Brand, RAM GB, RAM type, Storage capacity GB and other factors. This project explores various machine learning algorithms to predict Laptop prices and provides insights into which features are most important in influencing prices.

 <h1>Key Analysis Performed:</h1>
 
Data Collection and Pre processing:<br>
•	Data Collection: The first step is gathering data related to laptops. This data could come from online sources such as:<br>
o	Scraping e-commerce websites (Amazon, Flipkart, etc.)<br>
o	Open datasets (Kaggle, etc.)<br>
•	Data cleaning: clean Laptop price prediction processor gen, Core per processor, RAM type, Graphics brand and additional info.<br>
•	Identify key features affecting price fluctuations.<br>
•	Build and evaluate multiple machine learning models to predict flight prices.<br>
•	Compare model performance to select the best approach for price prediction.<br>

 <h1>Data Set:</h1>
 
The dataset use for this project contains information such as:<br>
•	Name: Laptop name.<br>                   
•	Brand: Laptop brand name.<br>                   
•	Price: Laptop price.<br>                  
•	 Rating: Laptop rating.<br>             
•	 Processor brand: Laptop processor brand name.<br>          
•	 Processor generation: Laptop processor generation name.<br>         
•	 Core per processor: Laptop core per processor name.<br>      
•	 Energy Efficient Units: Laptop energy efficient.<br> 
•	 RAM GB: Laptop RAM GB.<br>                  
•	 RAM type: Laptop RAM type.<br>            
•	 Storage capacity GB: Laptop storage capacity GB.<br>    
•	 Storage type: Laptop storage type.<br>        
•	 Graphics brand: Laptop graphics brand.<br>        
•	 Display size inches: Laptop display size inches.<br>   
•	 Horizontal pixel: Laptop horizontal pixel.<br>       
•	 Vertical pixel: Laptop vertical pixel.<br>         
•	 Touch screen: Laptop touch screen.<br>        
•	 Operating system: Laptop operating system.<br>      
	
<h1>Technologies used:</h1>

•	Pandas and NumPy: For data manipulating and processing.<br>
•	Matplotlib and Seabone for data visualization and analysis.<br>
•	Machine Learning: Evaluate multiple machine learning models.<br>
•	Python used for data analysis and model building.<br>

 <h1>Model Evaluation Metrics:</h1>
 
1)  Handling Categorical Features: Categorical data (such as name, brand, processor brand, ram type, etc) needs to be converted into numerical data using methods like:<br>
	One-Hot Encoding<br>
	Label Encoding<br>
2)	Feature Scaling: Standardize features such as price and RAM type for better model performance.<br>
3)	Feature Selection: Use statistical methods or model-based techniques (like Linear regression, Random forest, etc) to select important features and eliminate irrelevant ones.<br>
4)	Splitting data: Split the dataset into training and testing sets (typically 70-80% for training and 20-30% for testing) using train_test_split().<br>
5)	Mean squared error(RMSE): To measure prediction error.<br>
6)	Mean Absolute Error(MEA): To assume prediction accuracy.<br>
7)	R2_Score: To measure that provides information about the goodness of fit of a model.<br>

<h1>Insights and Findings:</h1>

1)	Project Conclusion: The Laptop price prediction project using RANDOM FOREST REGRESSOR has achieved impressive results.<br>
2)	Mean Absolute Error(MAE): 750.09822 indicating that the model’s predictions are on average within 750 units of the actual price.<br>
3)	Mean Squared Error(MSE): 1055960.6861 indicating that the model’s predictions have a moderate amount of variance.<br>
4)	R2 Score: 0.9995 indicating that the model explains approximately 99.95% of the variance in the target variable of laptop price.<br>
5)	Training Set: The model has achieved an R2 score of 0.9997 on the training set indicating excellent fit.<br>
6)	Testing Set: The model has achieved an R2 score of 0.9848 on the testing set indicating good generalization.<br>

<h1>Conclusion:</h1>

The Random Forest Regressor model has demonstrated exceptional performance in prediction in predicting laptop price.<br>
The model’s high R2 score and low MAE indicate prices based on the provided feature.<br>
