# Handwritten-Digit-Recognition-using-Artificial-Neural-Networks

#The workflow covers data loading, exploratory data analysis (EDA), preprocessing, model building, training, evaluation, and visualization using Python, scikit-learn, and TensorFlow/Keras.

🎯 Objective
To build and evaluate an ANN model that accurately predicts handwritten digits from grayscale image data.

#Dataset
Source: sklearn.datasets.load_digits
Total Samples: 1,797
Image Size: 8 × 8 (64 pixels)
Classes: 10 (digits 0–9)
Type: Grayscale images

🔁 Project Workflow
Load handwritten digits dataset
Perform Exploratory Data Analysis (EDA)
Visualize sample digit images
Split data into training and testing sets
Apply feature scaling (StandardScaler)
One-hot encode class labels
Build ANN architecture using Keras
Compile and train the model
Evaluate performance on test data
Visualize accuracy, loss curves, and confusion matrix

#Results
Test Accuracy: ~96–98%
High classification performance across all digits
Most misclassifications occur between visually similar digits
Evaluation Visualizations
Training vs Validation Accuracy Curve
Training vs Validation Loss Curve
Confusion Matrix
Classification Report (Precision, Recall, F1-Score)
