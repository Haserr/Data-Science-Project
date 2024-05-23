For our project, we decided we were going to utilize a house price prediction dataset. 
This data set was chosen because it provided good values to develop a machine learning program. 
Our goal was to use a machine learning algorithm to be able to predict characteristics of a house based on information we learn about it.   


First, we conducted data preprocessing, which handles missing values and encoding categorical variables, ensuring the integrity of the dataset. 
Next, we separate the dataset into two parts: One for training, and another for testing. 
Then we set up a Random Forest Regressor model. Once the model is trained, the testing subset is used to check its accuracy. 
Additionally, we use evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to assess the model’s performance. 
Finally, we store the results along with the input data for transparency and reproducibility.
