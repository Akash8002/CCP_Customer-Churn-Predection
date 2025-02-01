# CCP_Customer-Churn-Predection

### Introduction  
In the current competitive business environment, retaining customers is a critical strategy for companies aiming to maintain profitability and sustainability. Customer churn, where clients end their relationship with a company, can result in significant financial setbacks. This project focuses on analyzing and predicting customer churn utilizing a detailed dataset.

### Dataset  
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

### Data Exploration and Visualization  
An extensive data exploration and visualization process was carried out to better understand the dataset. This included analyzing the distributions, correlations, and patterns within the data. Key insights from the visualizations are:

- **Age Distribution**: The age distribution shows that most customers are middle-aged, with a notable presence of both younger and older customers.
  
- **Tenure vs Churn Rate**: A direct correlation between customer tenure and churn rate was observed, where customers with longer tenures have a lower likelihood of churn.
  
- **Balance vs Churn**: The analysis reveals that customers with higher account balances tend to be less likely to churn, underscoring the significance of financial stability in customer retention.
  
- **Gender vs Churn**: There is a minor variation in churn rates between male and female customers, which could play a role in shaping retention strategies.
  
- **Active vs Inactive Customers**: The comparison between active and inactive customers highlights a stark difference in churn rates, emphasizing the importance of maintaining an engaged customer base.

These visualizations and insights helped answer key business questions and provided a deeper understanding of the factors contributing to customer churn.

### Data Preprocessing and Resampling  
Prior to training machine learning models, thorough data preprocessing was conducted, which involved handling missing data, encoding categorical variables, and normalizing numerical features. Given the class imbalance in the dataset, the Synthetic Minority Over-sampling Technique (SMOTE) was employed to ensure a balanced distribution of the target variable (churn).

### Machine Learning Models  
A variety of machine learning algorithms were employed to predict customer churn, including:

- Logistic Regression
- K Nearest Neighbors
- Random Forest
- Gradient Boosting Classifier

Each model was evaluated using metrics such as accuracy, precision, recall, and F1-score to determine the most efficient model for churn prediction.

### Results and Insights  
The machine learning models revealed valuable insights into the factors influencing customer churn. The performance metrics indicated that the Random Forest model outperformed others, achieving the highest accuracy and F1-score in predicting churn.
