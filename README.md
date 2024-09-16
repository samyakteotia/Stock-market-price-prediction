# Stock-market-price-prediction
# Overview
This project demonstrates the use of machine learning techniques to predict stock market prices. For training the model, we utilized Ethereum data due to its high volatility, which provides a more dynamic dataset compared to traditional stock market data.
# Model Architecture
XGBoost (Extreme Gradient Boosting) is an advanced boosting algorithm that builds an ensemble of decision trees in a sequential manner. Each tree improves upon the errors of the previous trees, resulting in a highly accurate model. XGBoost incorporates regularization to prevent overfitting and optimizes performance through techniques such as gradient boosting and tree pruning.
# Dataset
We have used the Ethereum coin data. The dataset typically includes features such as opening price, closing price, highest price, lowest price, trading volume, etc.
# Usage
- Data Preprocessing: Ensure that your dataset is properly preprocessed. This may involve handling missing values, scaling features, encoding categorical variables, etc.

- Training the Model: Run the training script (train.py or similar) to train the XG Boost model on the preprocessed dataset.

- Testing: After training, you can test the model's performance using a separate test dataset. This step helps evaluate the model's accuracy and generalization capability.

- Prediction: Once trained and tested, the model is ready to make predictions on new or unseen data. Provide relevant input features to the model, and it will output the predicted stock prices.
# Dependencies
Ensure you have the following dependencies installed:

- Python (version >= 3.0)
- scikit-learn
- pandas
- numpy
- matplotlib (for visualization)
- XGBoost Regressor
# Graph- predected vs actual
<img width="741" alt="{E6707581-91CF-41BD-BEB7-93D432B7C3B0}" src="https://github.com/user-attachments/assets/75e9daa1-7b01-4581-85ce-fbb3419c8946">

# Feature Importance Graph
<img width="514" alt="{34A815FB-A951-497C-BFF5-6F06AB41D643}" src="https://github.com/user-attachments/assets/caef4b41-d943-44be-be22-ee2370447536">


# Results: 
<img width="306" alt="{D1F663DA-F867-4953-A20E-A5983E4C016C}" src="https://github.com/user-attachments/assets/e536d283-e588-40a3-8ec3-08282809ed71">



