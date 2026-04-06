 Career Prediction using Artificial Neural Network (ANN)

 Overview

This project uses an Artificial Neural Network (ANN) to predict a student's career path based on academic performance and creativity score. The model takes input features and classifies them into career options such as Engineering, Medical, or Arts.

---

Objective

The main objectives of this project are:

* To build a machine learning model using ANN
* To predict career paths based on student data
* To evaluate model performance using accuracy and confusion matrix

---

 Dataset

The dataset consists of the following features:

* Maths Marks
* Biology Marks
* Creativity Score
* Career (Target Variable)

The dataset is uploaded manually into the environment and processed using pandas.

---

Technologies Used

* Python
* NumPy
* Pandas
* TensorFlow / Keras
* Matplotlib
* Scikit-learn

---

 Methodology

1. Data Collection
   The dataset is uploaded and loaded into a pandas DataFrame.

2. Data Preprocessing

   * Input features (X) and output labels (y) are separated
   * Output labels are converted into categorical format using one-hot encoding

3. Model Building

   * A Sequential ANN model is created
   * Two hidden layers with ReLU activation
   * Output layer uses Softmax activation

4. Model Training

   * The model is trained for multiple epochs
   * Accuracy is recorded during training

5. Model Evaluation

   * Model performance is evaluated using accuracy
   * Confusion matrix is used to analyze prediction results

6. Prediction

   * User input values are taken
   * The model predicts the most suitable career

---

 Results

* The model achieves a reasonable accuracy on the dataset
* Accuracy graph shows improvement over training epochs
* Confusion matrix provides insight into prediction performance

---

 Output Example

Input:
Maths = 85
Biology = 60
Creativity = 70

Output:
Recommended Career: Engineering

---

 Advantages

* Simple and easy to implement
* Demonstrates practical use of Artificial Neural Networks
* Provides quick predictions

---

 Limitations

* Uses a small dataset
* No train-test split, which may lead to overfitting
* Limited input features

---

 Future Scope

* Use a larger and more diverse dataset
* Implement train-test split for better evaluation
* Improve model accuracy with hyperparameter tuning
* Add more features for better prediction

---

 Conclusion

This project demonstrates how an Artificial Neural Network can be used to predict career paths based on student performance. It highlights the importance of machine learning in decision-making systems and provides a foundation for further improvements.
