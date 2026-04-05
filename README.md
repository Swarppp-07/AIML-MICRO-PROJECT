# AIML-MICRO-PROJECT
This project uses an Artificial Neural Network (ANN) to predict a student's suitable career path based on their academic and creative performance.
Career Prediction using Artificial Neural Network (ANN)
Overview:
This project uses an Artificial Neural Network (ANN) to predict a student's suitable career path based on their academic and creative performance.

The model takes Maths, Biology, and Creativity scores as input and predicts one of the following careers:
Engineering 
Medical 
Arts 

Features:
Simple and beginner-friendly ANN model
Uses real dataset (dataset.csv)
Performs one-hot encoding for classification
Predicts career based on user input
Built using TensorFlow & Keras

Technologies Used: 
Python 
NumPy
Pandas
TensorFlow / Keras
 Project Structure
├── dataset.csv        # Input dataset
├── ann_model.py       # Main Python code
├── README.md          # Project documentation
Dataset Details

The dataset contains the following columns:
Feature	Description
Maths	Maths marks
Biology	Biology marks
Creativity	Creativity score
Career	Output label (0/1/2)
Model Architecture:
Input Layer: 3 neurons
Hidden Layer 1: 6 neurons (ReLU)
Hidden Layer 2: 6 neurons (ReLU)
Output Layer: 3 neurons (Softmax)

How It Works:
Load dataset using Pandas
Split into input (X) and output (y)
Convert output into categorical format
Train ANN model
Take user input
Predict career using trained model

How to Run:
Install required libraries:
pip install numpy pandas tensorflow

Run the script:
python ann_model.py
Enter student details:
Maths Marks: 85
Biology Marks: 60
Creativity Score: 70
 Sample Output
Model Accuracy: 0.95

Recommended Career: Engineering
  Future Improvements
Use larger dataset for better accuracy
Add more features (e.g., Physics, Communication skills)
Build a web app using Flask or Streamlit
Save model using .h5 file
