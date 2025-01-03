 -SyriaTel-customers-churn-rate
This project aims to predict customer churn for a telecommunications company using machine learning models. By identifying at-risk customers, the company can take proactive steps to retain valuable clients and reduce churn. The project uses a dataset containing customer information, including demographic details, service usage patterns, and historical interactions with customer support.
Churn is when customers stop using a service, which can have a significant impact on a telecom company's revenue: 
Churn is a problem for telecom companies because revenue depends on recurring subscriptions. Churn can lead to lost income and higher expenses. 
he dataset used for this analysis comes from a telecommunications company in Syria and includes customer information such as account details, service usage (e.g., call minutes, number of customer service calls), . The target variable is the binary `churn` indicator, which signifies whether a customer has left the company. This dataset is well-suited for predicting customer churn, as it contains key features that likely correlate with customer retention.The dataset includes various features related to a customer's account and usage. These features include 'account length', 'area code', 'international plan', and 'voice mail plan', which provide essential information about the customer's account type and services subscribed to. The 'number of voicemail messages' tracks how many voicemail messages the customer has received.
In terms of call usage, the dataset captures details about the customer's calling patterns throughout the day, evening, and night. 'Total day minutes', 'total day calls', and 'total day charge' represent the duration of calls, the number of calls, and the charges incurred during daytime hours. Similarly, 'total evening minutes', 'total evening calls', and 'total evening charge' capture this information for evening usage.
The dataset also includes 'total night minutes', 'total night calls', and 'total night charge', which record the customer's call activity during the night. 'Total international minutes', 'total international calls', and 'total international charge' focus on international call usage, detailing the duration, frequency, and costs associated with these calls.
Lastly, 'customer service calls' measures the number of calls a customer has made to the customer service department. This feature could provide insights into customer satisfaction or potential issues related to the service.
Two machine learning models were tested for predicting customer churn, including Logistic Regression and Random Forest Classifier. Logistic Regression was chosen as a baseline model due to its simplicity and interpretability. The Random Forest Classifier was selected because it can handle complex relationships between features and is more robust to in an imbalanced data compared to simpler models. The models were trained and evaluated using a 80-20 train-test split.
Companies can use machine learning models to identify customers who are likely to leave and the reasons why. 
This data can help companies improve their services and reduce churn. 
Two models i.e logistics Regression model and Random forest classifier models were used and their performances were evaluated using the accurancy report, classification report, confusion matrix and ROC-AUC curve metrics. 
The models were evaluated using the ROC-AUC score, as it provides a good indication of the model's ability to distinguish between churned and non-churned customers across different classification thresholds. The Random Forest Classifier achieved an ROC-AUC score of 0.9125, which indicates excellent model performance, while the Logistic Regression model had a slightly lower ROC-AUC of 0.8228. These results suggest that the Random Forest model is better suited for the task, though both models performed reasonably well.
 In conclusion, the Random Forest Classifier outperforms Logistic Regression in predicting customer churn, with a higher ROC-AUC score. This suggests that the Random Forest model should be deployed in a production setting to identify high-risk customers. For future work, additional feature engineering and the incorporation of more data sources (e.g., customer feedback or social media sentiment) could further improve the model's predictive power. Additionally, a deeper analysis of customer segmentation could provide more tailored retention strategies.
