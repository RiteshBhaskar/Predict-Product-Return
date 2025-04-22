# 📦 Predict Product Return – AI MSE Project

📝 Project Overview  
This project aims to build a machine learning model that can predict whether a purchased product will be returned based on customer behavior and order details. The dataset includes features like purchase amount, review score, and delivery time. By analyzing this data, we attempt to classify transactions as likely to be returned or not, helping e-commerce platforms proactively manage return-related costs.

📊 Methodology  
The approach begins with loading the dataset using Pandas and checking for null values. The target column 'returned' (values: "yes"/"no") is label-encoded into 1 and 0, respectively. Features and target variables are separated, followed by a train-test split (80:20). A RandomForestClassifier is trained using scikit-learn. Model performance is evaluated using metrics such as accuracy and classification report. Visualizations like feature importance plots may also be used to interpret model behavior.

🧰 Tools and Technologies  
- Python  
- Google Colab  
- pandas, numpy  
- scikit-learn (for model training and evaluation)  
- matplotlib & seaborn (for optional visualization)

🔍 Conclusion  
The Random Forest model provided promising results in predicting whether a product would be returned, showing good accuracy and class-wise precision. This kind of model can help businesses detect potentially returnable orders and take preventive steps. The project demonstrates how machine learning can be applied to real-world business problems with minimal preprocessing and robust model selection.

