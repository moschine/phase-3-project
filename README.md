# phase-3-project
# Customer Churn Prediction for SyriaTel

## Overview

### Problem Statement
SyriaTel, a telecommunications company, is facing challenges in retaining its customer base. Customer churn, which refers to customers terminating their subscriptions or switching to other service providers, has become a significant issue. This problem not only results in revenue loss but also increases acquisition costs for new customers.

### Project Objectives
The objective of this project is to develop a binary classification model that can accurately predict whether a customer is likely to churn (stop doing business with SyriaTel) in the near future. By identifying potential churners in advance, SyriaTel can proactively implement targeted retention strategies and personalized offers to prevent customer attrition.

### Key Challenges
The key challenges in this project include:
- Data Quality: Ensuring the availability and quality of relevant customer data, handling missing values, and dealing with potential data inconsistencies or outliers.
- Feature Engineering: Identifying and engineering informative features from the available data that can effectively capture patterns and characteristics associated with customer churn.
- Model Selection and Optimization: Choosing an appropriate binary classification algorithm and optimizing its hyperparameters to achieve high predictive performance.
- Interpretability and Actionability: Interpreting the model's predictions and feature importances to gain insights into the factors contributing to customer churn, enabling the development of effective retention strategies.
- Ethical Considerations: Ensuring that the model does not exhibit biases or discriminate against customers based on protected characteristics, and addressing potential privacy concerns related to customer data.

## Business Understanding

### Stakeholders
- SyriaTel: A telecommunications company facing customer churn challenges.

## Data Understanding and Analysis

### Source of Data
The dataset used in this analysis contains information about SyriaTel's customers, including demographic details, service usage patterns, billing records, customer tenure, and customer interactions (e.g., complaints, service requests).

### Description of Data
The dataset includes the following variables:

**Dependent Variable:**
- Churn: A binary indicator representing whether a customer has churned or not.

**Independent Variables:**
- Demographic information: State, account length, area code, phone number.
- Service usage patterns: International plan, voice mail plan, number of voicemail messages, total day/evening/night minutes, total day/evening/night calls.
- Billing records: Charges for various types of calls (daytime, evening, night, international).
- Customer interactions: Number of customer service calls.

### Visualizations

1. Churn Distribution
<img width="407" alt="image" src="https://github.com/moschine/phase-3-project/assets/144592615/524cfa74-3d4f-467d-a373-8039a4c82341">



2. Area Code Analysis
<img width="472" alt="image" src="https://github.com/moschine/phase-3-project/assets/144592615/38eb29cd-d2d1-47fa-907d-0229c661947b">



3. Correlation Heatmap
<img width="377" alt="image" src="https://github.com/moschine/phase-3-project/assets/144592615/b6291e2f-96d9-406b-82d8-00061eab8416">


## Summary
The comprehensive analysis conducted by the project team serves as a guide for SyriaTel to address customer churn challenges. The developed models not only identify key variables influencing customer churn but also provide a robust framework for predictive modeling.

The Random Forest Classifier model emerged as the best-performing model, achieving an accuracy of 0.96, a precision of 0.93, a recall of 0.76, an F1 score of 0.84, and a ROC AUC score of 0.87. This model empowers SyriaTel to navigate the customer retention landscape with a data-driven approach, enabling targeted retention efforts and personalized offers to prevent customer attrition.

By delving into the relationships between various features and customer churn, the models provide insights into the factors contributing to churn, such as customer service call frequency, international plan subscriptions, and usage patterns. Statistical significance achieved through hypothesis testing adds credibility to the insights derived, ensuring that SyriaTel can make informed decisions based on a solid foundation of analysis.

Furthermore, the models facilitate effective communication of complex insights, allowing the project team to convey the significance of variables and market trends to SyriaTel in a clear and actionable manner. In essence, these analytical tools serve as strategic enablers, guiding SyriaTel towards well-informed and strategic decisions in the realm of customer retention and loyalty.

## Conclusion
The analytical tools developed by the project team transcend mere prediction, serving as strategic enablers for SyriaTel. The models facilitate effective communication of complex insights, allowing for a clear understanding of variables and customer behavior patterns. In essence, these tools guide SyriaTel toward well-informed decisions in the dynamic realm of customer retention, ensuring a solid foundation of analysis and strategic navigation to mitigate customer churn and enhance customer loyalty.
