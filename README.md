# Test-the-Test-Forecasting-A-B-Test-Success-Using-Machine-Learning-and-Web-Analytics


To achieve the objectives of this project, a combination of data analysis, machine learning and visualization techniques were employed. The key techniques used are as follows:-


**Data Preprocessing:** Handled dataset input via CSV file uploads, Encoded categorical variables (e.g., converted) using one-hot encoding with pandas.get_dummies(), Checked for missing values and ensured the dataset was structured properly with required columns (test group and converted).


**Exploratory Data Analysis (EDA):** Generated descriptive statistics (mean, count, standard deviation) to understand the dataset, Created a Correlation Heatmap (using Seaborn) to identify relationships between numerical features.


**Train-Test Split:** Divided the dataset into training and testing subsets using an 80-20 ratio with train_test_split(), Ensured randomness with a fixed random_state for reproducibility.


**Machine Learning Model:** Implemented a Logistic Regression model using Scikit-learn to predict binary outcomes (Success/Failure), Trained the model on test/control variant data to classify conversion success.


**Model Evaluation**: Measured performance using:
▪ Accuracy Score to quantify prediction correctness.
▪ Confusion Matrix to visualize true positives, false positives, true negatives and false negatives.


**Interactive Web Application:**
Built a user-friendly interface using Streamlit, enabling:
▪ CSV dataset uploads.
▪ Automatic data preview and summary generation.
▪ Real-time prediction results with success/failure interpretation.
