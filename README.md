# Predicting Student Scores Based on Study Hours - Machine Learning Project

## Background Problem

The goal of this project is to predict a student's exam score based on the number of hours studied using machine learning models. This is a classic regression task that helps in understanding the relationship between study time and academic performance. The project leverages the **Student Scores dataset**, which is commonly used to evaluate machine learning algorithms in educational prediction tasks.

The dataset consists of two features: **Study Hours** and **Scores**. The objective is to predict the **Score** (target variable) from the **Hours** studied (feature).

## Libraries & Version

This project uses the following Python libraries:

- **pandas** – for data manipulation and analysis.
- **numpy** – for numerical operations.
- **matplotlib** and **seaborn** – for data visualization.
- **scikit-learn** – for building and evaluating machine learning models.

## Dataset

The dataset used in this project contains two columns:

- **Hours**: The number of hours a student has studied.
- **Scores**: The exam score obtained by the student.

The goal is to predict the **Scores** based on **Hours** using machine learning models.

## Project Steps

1. **Import Libraries and Load Dataset**: Import necessary libraries and load the dataset into a DataFrame.
2. **Exploratory Data Analysis (EDA)**: Perform data exploration to visualize the distribution of features and inspect for anomalies such as missing values or outliers.
3. **Data Preparation**: Split the data into training and testing sets, and apply feature scaling for better model performance.
4. **Model Training**: Train several machine learning models, including **Linear Regression**, **Decision Tree**, and **Random Forest**.
5. **Model Evaluation**: Evaluate the models using **Mean Squared Error (MSE)**, **Mean Absolute Error (MAE)**, and **R-squared (R²)** to compare their performance.
6. **Model Comparison**: Visualize and compare the performance of different models.

## Insights

Key findings from this project include:

1. **Model Comparison**: After training and evaluating three models, **Random Forest** performed the best with the lowest **Mean Squared Error (MSE)** of **18.6880**, and the highest **R-squared (R²)** of **0.9682**. 
2. **Alternative Models**: Although **Random Forest** performed the best, **Linear Regression** also showed a good fit for the data and is a simpler alternative when interpretability is important.

## Advice

This project can be further improved by:

1. **Hyperparameter Tuning**: Improving the models' performance by fine-tuning their parameters.
2. **Additional Features**: Exploring additional features or engineering new ones might enhance model accuracy.
3. **Model Experimentation**: Trying other regression models like **Support Vector Machines (SVM)** or **Gradient Boosting** could also improve the results.

## Conclusion

This project demonstrates how to predict student exam scores based on the number of study hours using various machine learning models. Among the models evaluated, **Random Forest** performed the best in terms of accuracy. The project also emphasizes the importance of **Exploratory Data Analysis (EDA)** and data preparation in building successful machine learning models.

## Tools and Libraries

- **pandas**: `1.3.0`
- **numpy**: `1.21.0`
- **matplotlib**: `3.4.2`
- **seaborn**: `0.11.1`
- **scikit-learn**: `0.24`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
