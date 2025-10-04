## Customer Churn Prediction

***Overview***

* This project predicts whether a customer will leave (churn) or stay with a company, using historical customer data.

* The goal is to help businesses identify at-risk customers and take proactive retention actions.

***Dataset***
* The dataset contains customer information including:

* Demographics: Age, gender, senior citizen status, partner and dependents

* Account info: Tenure, monthly charges, total charges

* Services: Phone, internet, subscriptions

* Target: Churn (Yes = churn, No = stay)

***Approach***

* Preprocessing converts categorical features into numeric form and encodes the target variable.

* Data is split into training and testing sets.

* A neural network model is trained to classify whether a customer will churn.

***Model Architecture***

* Sequential Neural Network with multiple hidden layers

* Output layer predicts the probability of customer churn

* Trained using binary classification and evaluated with accuracy metrics

***Key Takeaways***

* Predicting churn helps businesses retain customers and reduce revenue loss.

* Proper preprocessing and encoding of data is crucial for model accuracy.

* Neural networks can effectively handle tabular data for classification tasks.

***Technologies Used***

* Python 3 – Programming language for data processing and modeling

* Pandas – Data manipulation and preprocessing

* NumPy – Numerical computations

* Scikit-learn – Data splitting, encoding, and evaluation metrics

* TensorFlow & Keras – Building and training the neural network model

* Jupyter Notebook – Interactive development and visualization
