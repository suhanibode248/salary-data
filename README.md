# Salary Data Prediction System

**Author(s):** Suhani Bode
**Affiliation:** Rashtrasant Tukadoji Maharaj Nagpur University
**Date:** June 2026

## Abstract

The Salary Data Prediction System is a machine learning-based application designed to estimate employee salaries based on various factors such as experience, education level, job role, age, and other professional attributes. Salary prediction helps organizations make informed compensation decisions and enables job seekers to understand expected salary ranges. In this project, historical salary data was collected and preprocessed to remove inconsistencies and missing values. Feature engineering and scaling techniques were applied to improve model performance. Various machine learning algorithms were trained and evaluated to identify the most accurate model. The final model was integrated into a web application that allows users to enter employee details and receive salary predictions instantly. The project demonstrates the practical use of machine learning in predictive analytics and human resource management.

## Introduction

Salary prediction is an important application of machine learning in the field of human resource analytics. Organizations often need to determine fair compensation based on employee qualifications, skills, and experience. Traditional salary estimation methods may be subjective and time-consuming. A machine learning-based salary prediction system can automate this process and provide data-driven insights. The objective of this project is to develop a predictive model that accurately estimates salaries using employee-related features. Such systems can assist recruiters, companies, and job seekers in making informed decisions regarding compensation.

## Literature Review

Salary prediction has been widely studied using statistical and machine learning techniques. Traditional regression methods such as Linear Regression have been commonly used to model salary trends. More advanced algorithms, including Random Forest, Decision Tree, and Gradient Boosting, have shown improved prediction accuracy by capturing complex relationships between features. Recent research has also explored deep learning approaches for salary forecasting. Studies indicate that feature selection, data preprocessing, and model optimization play crucial roles in improving salary prediction performance.

## Methodology

The project follows a systematic machine learning workflow. First, the salary dataset is collected and inspected for missing values and inconsistencies. Data preprocessing techniques such as encoding categorical variables, handling missing data, and feature scaling are applied. The cleaned dataset is then divided into training and testing sets. A regression model is trained using historical salary records and evaluated using performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score. After selecting the best-performing model, it is saved and integrated into a web application where users can input employee information and receive salary predictions in real time.

## Implementation

### Programming Languages

* Python

### Frameworks/Libraries

* Pandas
* NumPy
* Scikit-learn
* Joblib
* Matplotlib
* Seaborn
* Streamlit

### Tools Used

* Google Colab
* Jupyter Notebook
* GitHub
* Streamlit Cloud
* VS Code

## Results and Discussion

The developed model successfully predicts salaries based on employee attributes. Data preprocessing and feature scaling improved model performance and prediction accuracy. The selected regression algorithm demonstrated strong predictive capability on unseen data. Performance metrics such as MAE, RMSE, and R² Score were used to evaluate the model. The Streamlit-based web application provides an interactive interface where users can enter employee details and instantly obtain predicted salary values. The results indicate that machine learning can effectively support salary estimation and workforce analytics.

## Limitation

* Prediction accuracy depends on the quality and size of the dataset.
* The model may not generalize well to industries or regions not represented in the training data.
* Sudden market changes and economic conditions are not considered.
* Limited feature availability can affect prediction accuracy.

## Future Scope

* Integrate real-time labor market and industry salary trends.
* Use advanced machine learning and deep learning models.
* Add salary range estimation instead of a single predicted value.
* Develop personalized career and salary growth recommendations.
* Deploy the application on cloud platforms for large-scale use.

## Conclusion

The Salary Data Prediction System demonstrates how machine learning can be used to estimate employee salaries efficiently and accurately. By leveraging historical salary data and regression algorithms, the system provides reliable salary predictions that can support decision-making for employers and job seekers. The project highlights the importance of predictive analytics in human resource management and showcases the practical application of machine learning in real-world business scenarios.

## References

[1] James, G., Witten, D., Hastie, T., & Tibshirani, R., "An Introduction to Statistical Learning," Springer, 2021.

[2] Pedregosa, F. et al., "Scikit-learn: Machine Learning in Python," Journal of Machine Learning Research, 2011.

[3] Scikit-learn Documentation: https://scikit-learn.org/

[4] Pandas Documentation: https://pandas.pydata.org/

[5] Streamlit Documentation: https://streamlit.io/

[6] Joblib Documentation: https://joblib.readthedocs.io/
