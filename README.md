🚀 Perceptron from Scratch (NumPy)
📌 Overview

This project implements a binary classification Perceptron model from scratch using NumPy, without relying on high-level ML libraries. It demonstrates the fundamental mechanics behind linear classifiers, including weight updates, activation functions, and training loops.

The model is evaluated on the Iris dataset, achieving perfect classification performance (100% accuracy) on a binary task.

⚙️ Key Features
Custom implementation of the Perceptron algorithm
Built from scratch (no sklearn model used for training)
Gradient-free learning via iterative weight updates
Binary classification using a step activation function
Evaluation with precision, recall, and F1-score
Data visualization of predictions using Matplotlib
🧠 Model Details
Learning Rate: 0.1
Epochs: 10
Activation Function: Step Function
Input Features: Sepal length & width (Iris dataset)
📊 Results
✅ Accuracy: 100%
✅ Precision / Recall / F1-score: 1.00
Clean separation between classes visualized in 2D feature space
📁 Tech Stack
Python
NumPy
Pandas
Matplotlib
Scikit-learn (for dataset + evaluation only)
▶️ How to Run
pip install -r requirements.txt

Then open:

perceptron.ipynb

Run all cells to train and visualize results.

💡 What This Shows

This project demonstrates:

Strong understanding of core ML concepts
Ability to implement models from first principles
Clear grasp of training logic, evaluation, and visualization
📌 Future Improvements
Extend to multi-class classification
Add learning curve visualization
Compare with logistic regression
Implement vectorized training for efficiency
