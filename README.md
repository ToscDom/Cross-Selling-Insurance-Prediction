# Cross-Selling-Insurance-Prediction

📈 Project Overview

AssurePredict is a leading insurance company specializing in innovative risk management solutions. This project aims to develop a predictive model to identify potential cross-selling opportunities by detecting existing customers who may be interested in purchasing an additional vehicle insurance policy.

🌐 Project Objective

The goal is to build a machine learning model that predicts whether customers, who currently have a health insurance policy, might be interested in subscribing to a vehicle insurance policy. The model will help AssurePredict improve the efficiency of its cross-selling strategies and increase market penetration.

🔄 Value Proposition for AssurePredict:

Increased conversion rate for vehicle insurance policy sales.

Optimized marketing campaigns by targeting customers more likely to purchase.

Reduced marketing costs by minimizing ineffective campaign spending through precise customer targeting.

📂 Dataset

The dataset (downloadable here: Insurance Cross-Sell Dataset) contains detailed customer information and their insurance behavior.

Key Features:

id: Unique customer identifier.

Gender: Customer's gender.

Age: Customer's age.

Driving_License: 1 if the customer holds a driving license, 0 otherwise.

Region_Code: Unique region code of the customer's residence.

Previously_Insured: 1 if the customer already has vehicle insurance, 0 otherwise.

Vehicle_Age: Age of the customer's vehicle.

Vehicle_Damage: 1 if the customer has had vehicle accidents or damage in the past, 0 otherwise.

Annual_Premium: Annual premium amount paid by the customer.

PolicySalesChannel: Channel used to sell the policy (e.g., email, phone, in-person).

Vintage: Number of days the customer has been insured with AssurePredict.

Response: 1 if the customer accepted the cross-sell offer, 0 otherwise.

🎯 Key Activities

1️⃣ Exploratory Data Analysis (EDA)

Preliminary data exploration is crucial to understanding feature distributions and target variable behavior. The analysis includes:

Examining the distribution of the Response variable to identify any class imbalances.

Analyzing key feature relationships, such as Annual Premium, Vehicle Age, Previously Insured, and customer response.

✅ Added Value: Thorough data exploration reveals hidden patterns and critical points that impact the model's predictive success.

2️⃣ Handling Class Imbalance

The target variable (Response) might be imbalanced, meaning there are significantly more customers who decline the offer than those who accept it. To address this issue, the following techniques will be applied:

Class Weights: Adjusting for imbalanced classes by penalizing the majority class.

Oversampling or Undersampling: Modifying the dataset distribution to enhance model generalization.

✅ Added Value: Proper handling of class imbalance prevents high false negative rates, leading to more precise cross-selling predictions.

3️⃣ Building the Predictive Model

A machine learning model will be developed to predict the probability of a customer responding positively to the cross-sell offer.

✅ Added Value: The predictive model will enable AssurePredict to accurately identify customers most likely to purchase an additional policy, improving the return on investment (ROI) of marketing campaigns.

📊 Conclusion

This project will empower AssurePredict to leverage machine learning for efficient and targeted cross-selling opportunities. By adopting a data-driven approach to customer response prediction, the company can increase sales while improving customer satisfaction through more relevant and personalized offers.

⚠ Key Considerations

Pay attention to class distribution. If the dataset is imbalanced, consider:

Penalizing the majority class using class_weight adjustments.

Applying oversampling or undersampling techniques to balance the dataset.

📦 Project Delivery

Final submission: Link to Google Colab Notebook
