# Model-ComparisonML
Comparison of these models ; Support Vector Machine (SVM) , Random Forest, KNN, Decision Tree ,  Naïve Bayes and Logistic Regression.


The provided code performs classification tasks using different machine learning algorithms (Logistic Regression, Random Forest, Support Vector Machine, Decision Tree, Naive Bayes, and K-Nearest Neighbors) on a heart disease dataset. Here's a brief overview of what each part of the code does:

    Data Loading and Preprocessing: The code imports required libraries, loads the heart disease dataset, and splits it into the feature matrix (X) and the target vector (y). It then further divides the data into training and testing sets.

    Logistic Regression Model: The code creates a Logistic Regression model, fits it on the training data, and makes predictions on the test data. It also calculates performance metrics (accuracy, precision, recall, and F1 score) on both the training and testing data.

    Confusion Matrix Visualization: The code creates and displays confusion matrices for each model to visualize the performance of the classifiers.

    Pairplot Visualization: The code uses Seaborn to create a pairplot, which allows visualizing the relationships between pairs of variables (age, cholesterol, maximum heart rate, and resting blood pressure) colored by the target class (heart disease presence or absence).

Note: The provided code may not run successfully if the heart_disease_data.csv file is not present in the specified path. Ensure that you have the dataset available before running the code. Additionally, make sure you have the required libraries (pandas, numpy, seaborn, scikit-learn) installed.

Keep in mind that this code is written in sections and can be further improved and optimized for readability and maintenance. Also, if you have any specific questions or tasks related to the code, feel free to ask!
