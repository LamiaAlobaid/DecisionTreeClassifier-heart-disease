# DecisionTreeClassifier-heart-disease
## Heart Disease Prediction Project

This project aims to predict the presence of heart disease based on various medical attributes using machine learning techniques. The dataset used in this project contains information about patients, including their age, sex, cholesterol levels, and other relevant factors. The main steps involved in this project are:

### 1. Data Preparation
- Load the dataset using `pandas`, explore its structure, and split it into features and target variables.

### 2. Model Building
- Train a decision tree classifier using `scikit-learn` based on the provided data.

### 3. Model Evaluation
- Evaluate the performance of the trained model using metrics such as accuracy, precision, recall, and F1-score. Visualize the results using confusion matrices.

### 4. Overfitting Handling
- Apply cost-complexity pruning to address overfitting by identifying and selecting the optimal alpha value.

### 5. Visualization
- Visualize the decision tree before and after pruning to observe the changes and understand the model's decision-making process.

#### Usage

To use this project:

1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file using `pip install -r requirements.txt`.
3. Run the Jupyter notebook or Python script to execute the project code.
4. Follow the instructions and comments within the code to understand each step of the project.

#### Dataset

The dataset used in this project (`heart.csv`) contains information about patients and whether they have heart disease. It includes various medical attributes that are used as features for prediction.

#### Libraries Used

- `pandas`: For data manipulation and analysis.
- `scikit-learn`: For building and evaluating machine learning models.
- `matplotlib`: For data visualization.

