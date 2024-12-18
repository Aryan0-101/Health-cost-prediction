# Healthcare Cost Prediction 
This project focuses on predicting healthcare costs using a regression model. The model is trained to estimate healthcare expenses based on various features such as age, sex, BMI, number of children, smoking habits, and region.

This project was completed as part of the Machine Learning with Python program by Free Code Camp. 
 https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/linear-regression-health-costs-calculator

### **Overview**

The goal of this project is to:
- Build a regression model that predicts healthcare costs.
- Achieve a Mean Absolute Error (MAE) of under $3500 when evaluating the model on unseen test data.

The project uses a dataset that includes demographic and health-related attributes for individuals and their respective healthcare costs.

## **Steps to Solve**

### **Data Preprocessing:**

- Handle categorical data using LabelEncoder for columns like sex, smoker, and region.
- Normalize numerical features using StandardScaler to improve model performance.

### **Data Splitting:**

- Extract the target variable expenses as train_labels and test_labels.
- Split the data into training (80%) and testing (20%) datasets.

### **Model Design:**

- Build a neural network regression model using TensorFlow and Keras.
- Use a sequential model with three dense hidden layers and ReLU activations.
- Use Mean Absolute Error (MSE) as the loss function and Mean Absolute Error (MAE) and Mean Squared Error (MSE) as the evaluation metrics.

### **Training:**

- Train the model with the training dataset for multiple epochs.
- Use 20% of the training data for validation during training.

### **Evaluation:**
 (Code provided in the Boiler-plate by FreeCodeCamp) 
- Evaluate the model on the test dataset.
- Visualize the predictions vs actual healthcare costs to check model performance.
