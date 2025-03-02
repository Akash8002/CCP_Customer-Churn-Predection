# CCP_Customer-Churn-Prediction

## Introduction
In the current competitive business environment, retaining customers is a critical strategy for companies aiming to maintain profitability and sustainability. Customer churn, where clients end their relationship with a company, can result in significant financial setbacks. This project focuses on analyzing and predicting customer churn utilizing a detailed dataset.

## Dataset
The dataset used in this analysis comprises the following features:
- **Age**: The customer's age.
- **Tenure**: The number of years the customer has been associated with the company.
- **Nationality**: The customer's country of origin.
- **Balance**: The current balance in the customer’s account.
- **Salary**: The customer's annual income.
- **Score**: The customer’s credit rating.
- **Card**: The type of credit card the customer holds.
- **Gender**: The customer's gender.
- **Active**: Indicates whether the customer is currently active or not.
- **Products**: The number of products the customer holds with the company.
- **Age Bins**: A feature created through feature engineering that categorizes customers into specific age groups.

## Data Exploration and Visualization
An extensive data exploration and visualization process was carried out to better understand the dataset. This included analyzing distributions, correlations, and patterns within the data. Key insights include:
- **Age Distribution**: Most customers are middle-aged, with notable groups of younger and older customers.
- **Tenure vs Churn Rate**: Customers with longer tenures tend to have a lower likelihood of churn.
- **Balance vs Churn**: Customers with higher account balances tend to be less likely to churn.
- **Gender vs Churn**: A minor variation in churn rates between male and female customers was observed.
- **Active vs Inactive Customers**: Inactive customers have a significantly higher churn rate, highlighting the importance of customer engagement.

## Data Preprocessing and Resampling
Prior to training machine learning models, thorough data preprocessing was conducted, including:
- Handling missing data.
- Encoding categorical variables.
- Normalizing numerical features.
- Addressing class imbalance using **Synthetic Minority Over-sampling Technique (SMOTE)** to ensure a balanced distribution of the target variable (churn).

## Machine Learning Models
A variety of machine learning algorithms were employed to predict customer churn:
1. **Logistic Regression**
2. **K Nearest Neighbors (KNN)**
3. **Random Forest**
4. **Gradient Boosting Classifier**

Each model was evaluated using **accuracy, precision, recall, and F1-score** to determine the most efficient model for churn prediction.

## Results and Insights
- The **Random Forest model** outperformed the others, achieving the highest accuracy and F1-score in predicting churn.
- Key factors influencing churn include **tenure, account balance, and customer activity level**.
- Insights from the model can help businesses develop better customer retention strategies.

## Installation & Usage
To use this project, follow these steps:
1. Clone the repository:
   ```sh
   git clone https://github.com/Akash8002/CCP_Customer-Churn-Predection.git
   ```
2. Navigate to the project directory:
   ```sh
   cd CCP_Customer-Churn-Predection
   ```
3. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python script to analyze and predict churn.

## License
This project is licensed under the **Apache-2.0 License**.

## Contributing
Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.

## Contact
For any queries or suggestions, feel free to reach out or open an issue in the repository.
