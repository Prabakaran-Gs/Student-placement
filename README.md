
  <h1>KNN Classification for Student Placement</h1>

  <p>This repository contains Python code for building a K-Nearest Neighbors (KNN) classification model to predict student placement based on certain features. The dataset used is stored in an Excel file named "student.xlsx". The code utilizes the pandas library for data manipulation, numpy for numerical operations, matplotlib for data visualization, and scikit-learn for machine learning tasks.</p>

  <h2>Code Overview</h2>

  <p>The code is organized into the following sections:</p>

  <ol>
      <li>Importing Libraries</li>
      <li>Loading and Preprocessing Data</li>
      <li>Exploratory Data Analysis (EDA)</li>
      <li>Splitting Data into Train, Validation, and Test Sets</li>
      <li>Scaling Data and Oversampling (optional)</li>
      <li>Building and Training the KNN Model</li>
      <li>Evaluating Model Performance</li>
  </ol>

  <h2>Usage</h2>

  <p>1. Make sure you have Python installed on your system.</p>
  <p>2. Install the required libraries using:</p>

  ```bash
  pip install pandas numpy matplotlib scikit-learn imbalanced-learn
  ```

  <p>3. Run the provided Python script:</p>

  ```bash
  python placement_prediction.ipynb
  ```

  <h2>Results</h2>

  <p>The script will output the classification report, providing metrics such as precision, recall, and F1-score for model evaluation.</p>

  <h2>Note</h2>

  <p>The oversampling technique (RandomOverSampler) is applied to handle class imbalance in the training data. You can toggle the oversampling option as needed.</p>

  <h2>Author</h2>

  <p>Prabakaran GS</p>
