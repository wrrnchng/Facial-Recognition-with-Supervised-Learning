# Facial Recognition with Supervised Learning

### Disclaimer
*This project is based on files and datasets provided by DataCamp as part of their real-world projects. The dataset and structure align with educational content from DataCamp to help learners practice machine learning techniques in real-world scenarios.*

### Project Overview

This project leverages machine learning to enhance the security of influential figures by distinguishing Arnold Schwarzenegger from others. The goal is to build multiple classification models and determine the best-performing one based on cross-validation scores.

### How It Works

The code implements a machine learning pipeline to:

1. Load and preprocess the dataset.

2. Train four different classification models:

    - Random Forest Classifier

    - Support Vector Classifier (SVC)

    - Logistic Regression

    - K-Nearest Neighbors (KNN)

3. Optimize hyperparameters using GridSearchCV and KFold cross-validation.

4. Select the best-performing model based on accuracy scores.

5. Evaluate the selected model using accuracy, precision, recall, and F1-score on the test set.

6. Visualize the performance of the best model using a confusion matrix.

### Technologies Used

  - Python

  - Scikit-learn (for machine learning models and evaluation)

  - Pandas & NumPy (for data manipulation)

  - Matplotlib & Seaborn (for visualization)

### Key Features

  - Automated machine learning pipeline for preprocessing and model selection

  - Hyperparameter tuning with GridSearchCV and cross-validation

  - Performance evaluation using multiple classification metrics

  - Confusion matrix visualization for better result interpretation

### Installation & Usage

1. Clone the repository:

        git clone https://github.com/yourusername/arnold-classification.git

2. Navigate to the project directory:

        cd arnold-classification

3. Install required dependencies:

        pip install -r requirements.txt

4. Run the script:

        python main.py

### Contributions

Contributions are welcome! Feel free to fork the repository, open an issue, or submit a pull request with improvements.


