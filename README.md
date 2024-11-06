# Portfolio of Healthcare Models & Dashboard

## Introduction
This repository features three machine learning models and two websites focused on healthcare analytics, predictions, and visualization. These models aim to address anomaly detection, billing prediction, and sales forecasting. Additionally, a **Power BI** dashboard and a billing prediction website provide valuable tools for stakeholders and patients.

## Comprehensive User Guide for the Healthcare Analytics Dashboard

Step 1 :**User Authentication & Account Creation:**
Log in with your username and password to establish a secure session using JWT (JSON Web Tokens) for token-based authentication. If you don’t have an account, you can register a new one by providing your personal details. Passwords are securely hashed and stored in MongoDB to ensure your information is protected.

![image](https://github.com/user-attachments/assets/8ae83b1f-7769-4471-bc53-d971e0ac9301)
![image](https://github.com/user-attachments/assets/e9c7a2ee-d670-4bbc-b1b9-10f361849a3e)


Step 2 **:Dashboard Access & Sidebar Navigation**:
Access the home page, serving as the hub for key metrics and insights, built using React.js for dynamic updates. Utilize the left navigation panel to transition seamlessly between various analytical tools, all styled with Tailwind CSS to ensure a responsive design that enhances user experience.

![WhatsApp Image 2024-10-24 at 12 44 11_cd89bf7b](https://github.com/user-attachments/assets/5e2e7074-d051-4eec-b4ce-c1464343ad5c)



Step 3 :**Anomaly Detection & Billing Prediction Analysis**:
Utilize the Anomaly Detection feature powered by the Isolation Forest algorithm to identify billing irregularities, and review outputs from the billing prediction model, which is created with a Random Forest Regressor to forecast hospital billing amounts. This combined analysis helps in maintaining financial accuracy and enhancing decision-making.

![WhatsApp Image 2024-10-24 at 12 44 13_31718cb0](https://github.com/user-attachments/assets/9787cd3c-25d7-4898-b670-9fed11ca812a)


![image](https://github.com/user-attachments/assets/c626de96-af48-494f-8df6-2c1996fbfbf7)




Step 4 :**Comprehensive Analysis & Power BI Visualization:**

Investigate predictions for billing amounts and admission lengths using advanced machine learning techniques to enhance operational efficiency. Additionally, interact with the Power BI dashboard for visual analytics on sales performance and market trends, employing DAX for effective data manipulation. This integration allows for informed decision-making and strategic insights.

![WhatsApp Image 2024-10-24 at 12 44 11_65f22e60](https://github.com/user-attachments/assets/da715b7e-3095-4504-8484-9f2dd9beffd1)

![WhatsApp Image 2024-10-24 at 12 44 12_ff5b4732](https://github.com/user-attachments/assets/f7305d1e-c720-4d4a-85f8-220d3650820f)

![WhatsApp Image 2024-10-24 at 12 44 13_b885a7a7](https://github.com/user-attachments/assets/9e1b6bc7-8025-4b7f-bba5-30f073dde88c)




Step 5 : **Patient Billing Prediction & Data Security Assurance**:

Enter personal and medical data to estimate hospital costs using machine learning models for real-time predictions. Rest assured that robust security measures, including HTTPS and secure API endpoints, protect your sensitive information and ensure compliance with regulations like GDPR and HIPAA, safeguarding your data throughout the process.

![WhatsApp Image 2024-10-24 at 12 44 12_5776b5c7](https://github.com/user-attachments/assets/ce237d7c-8ddc-4924-a234-6d1927c56cd1)

![WhatsApp Image 2024-10-24 at 12 44 12_4c97cfb7](https://github.com/user-attachments/assets/d408c1e4-645e-46ee-874f-06cd05c13f1b)




## Project Overview
### 1. **Anomaly Detection with Isolation Forest**
In this project, the Isolation Forest algorithm was employed to detect anomalies in hospital billing amounts, providing hospitals with a mechanism to identify unusual billing patterns.

### Key Steps:
- **Feature Selection**: Numeric features were selected, excluding non-relevant columns like names and dates.
- **Data Preprocessing**: The data was split into training and testing sets.
- **Anomaly Detection**: Trained the Isolation Forest algorithm to classify data as anomalous (-1) or normal (1).
- **Visualization**: Visualized the results, highlighting outliers in billing amounts that may indicate errors or fraud.

### Outcome:
- Identified significant billing anomalies for further investigation, improving financial oversight in hospital management.

### 2. **Hospital Billing Prediction & Future Sales Forecasting**
This model predicts billing amounts for hospitals and provides future sales forecasts for the top 10 hospitals.

### Key Steps:
- **Data Preparation**: 
    - Processed missing values and prepared both categorical and numeric data.
    - Split the data into features and the target variable (`Billing Amount`).
- **Model Building**: Built a Random Forest Regressor model to predict billing amounts.
- **Model Evaluation**: Achieved an MAE of 12,235.62, an MSE of over 205 million, and an accuracy of 52%.
- **Future Sales Prediction**: Linear regression was used to forecast hospital sales for the next 1, 2, and 5 years.

### Outcome:
- Provided valuable predictions for hospital billing amounts and projected future sales, helping hospitals with revenue planning and budgeting.

### 3. **Billing Amount and Admission Days Prediction**
This project focused on predicting both billing amounts and hospital admission days, providing deeper insight into hospital performance and cost-efficiency.

### Key Steps:
- **Data Preprocessing**: Managed missing values and encoded categorical features for modeling.
- **Feature Selection**: Chose relevant features like age, medical condition, etc., with billing amount as the target variable.
- **Model Training**: Trained Random Forest and Gradient Boosting Regressor models. Random Forest performed best, achieving an R² score of 0.91 with 90.68% accuracy.
- **Analysis**: Predicted average billing and identified hospitals with the shortest admission periods.

### Outcome:
- Delivered detailed insights on cost-efficiency and performance, helping to identify hospitals with the lowest costs and shortest stays.

## Websites and Power BI Dashboard

### 1. **Power BI Dashboard for Stakeholders**
A **Power BI** dashboard was created to visualize data insights, aimed at helping stakeholders make data-driven decisions regarding hospital performance and financial trends.

### Key Features:
- **Sales Performance Visualization**: Showcased trends and patterns in hospital billing over time.
- **Market Trend Analysis**: Identified shifts in healthcare market demands and pricing.
- **Predictive Analytics**: Visualized future sales projections and trends.
- **Anomaly Detection**: Highlighted billing anomalies for further scrutiny.

This interactive dashboard offers stakeholders an accessible platform for understanding critical business insights through intuitive visuals.

### 2. **Patient Billing Prediction Website**
The second website caters to patients, allowing them to input personal and medical details to predict their hospital billing amounts.

### Features:
- **Billing Prediction Tool**: Provides an estimated billing amount based on user inputs using machine learning models.
- **User-Friendly Design**: Offers an intuitive interface for patients of all backgrounds to easily access.
- **Secure Data Handling**: Ensures privacy and confidentiality while delivering accurate billing predictions.

This tool helps patients better understand and prepare for their healthcare costs.

## Conclusion
This portfolio presents a range of data science and web development projects aimed at enhancing healthcare efficiency. From anomaly detection to future billing predictions, these models and tools provide hospitals, stakeholders, and patients with actionable insights. The **Power BI** dashboard offers an engaging way for stakeholders to analyze trends, while the billing prediction website empowers patients with financial transparency. Together, these projects support informed decision-making and efficient resource management within the healthcare sector.
