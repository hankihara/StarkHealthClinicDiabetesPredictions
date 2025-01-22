# StarkHealthClinicDiabetesPredictions


![image](https://github.com/user-attachments/assets/7f4e8f36-ab3d-4f2d-8561-7ca9e879ce02)



# OBJECTIVE OF THE PROJECT

Stark Health Clinic aims to develop a robust diabetes prediction model to accurately identify individuals at risk of developing diabetes. You have been approached as a Data
Scientist to lead this project, utilizing advanced machine learning techniques on patient data. The goal is to predict the likelihood of diabetes onset, allowing for timely and targeted preventive measures. This initiative will empower Stark Health to enhance patient outcomes, reduce the burden on healthcare resources, and play a proactive role in combating diabetes.
# DATA SOURCE

The dataset used on this project was provided by 10Alytics. The dataset contains patients features including gender, age, hypertension, heart disease, bmi and other relevant information.

# PROBLEM STATEMENT

Diabetes poses significant health risks to Stark Health’s patients, and also financial challenges. Current methods for early detection at Stark Health Clinic lack precision, leading to
missed opportunities for timely interventions.

# BUSINESS INTRODUCTION

Stark Health Clinic is a leading healthcare provider that leverages technology and predictive modeling to enhance its operations. By integrating machine learning into its systems, the clinic identifies diseases early, improving patient outcomes and resource allocation.

Problem: The company needs an effective way to identify individuals at risk of diabetes early to provide timely interventions, minimize complications, and reduce healthcare costs. Currently, there is no automated solution to analyze data and predict diabetes risk efficiently.

# THE COMPANY BENEFITS:
Proactive Risk Management: The model will help identify individuals at risk of diabetes early, reducing the likelihood of long-term complications and lowering associated healthcare costs.

Improved Patient Outcomes: Early detection enables patients to manage their condition more effectively, leading to a better quality of life and fewer hospitalizations.

Increased Efficiency: Automating the diabetes prediction process allows healthcare providers to focus on high-priority cases, ensuring optimal use of resources.

Cost Savings: Preventing complications and avoiding unnecessary care expenses will significantly reduce the hospital’s budget, freeing up funds to address other health challenges.

Stronger Reputation: Implementing innovative, data-driven solutions positions the hospital as a leader in healthcare innovation and fosters greater trust among patients. 

This is a classification problem focused on developing a machine learning model to determine whether a patient has diabetes based on the given data. The main priority is to identify all diabetic patients, reducing the risk of missing any cases, while ensuring the predictions are both accurate and practical for real-world use.

# Data Preprocessing and Feature Engineering:

1. Cleaned the data by checking missing and duplicate values. 

2. Performed normalization.

4. Performed Encoding by converting categorical variables into numerical form by using OneHotEncoder.

5. Prepared the dataset by splitting the data into training and test sets.

# Model: Decision Tree Classifier

The trained models achieved the following results:
Recall for diabetic was 0.73, indicating the model captures 73% of diabetic cases.

Accuracy: 95%, ensuring high reliability overall.

Precision: The model has a precision of 72% for identifying diabetic cases, meaning that when it predicts someone has diabetes, it is correct 72% of the time. This helps minimize unnecessary false alarms while focusing on cases that genuinely require attention.

The confusion matrix shows that this model makes far fewer mistakes when it comes to missing positive cases (false negatives) compared to other models. This aligns well with the company’s priority of focusing on early detection.





