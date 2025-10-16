# fraud-detection-logistic-regression-streamlit
This project delivers an end-to-end machine learning pipeline for credit card fraud detection with a Streamlit web application.

Quick Setup & Execution1. 
Get the Data (CRITICAL!)The AIML Dataset (1).csv file ($\approx 470 \text{ MB}$) is not in this repository due to size limits.Download: Get the dataset from the original Kaggle 
source:Kaggle Fraud Detection DatasetPlace: Put the downloaded AIML Dataset (1).csv file in the root project directory (where this README.md is).

Install and RunClone:Bashgit clone https://github.com/sunidhier/fraud-detection-logistic-regression-streamlit.git
cd fraud-detection-logistic-regression-streamlit
Install: (Ensure your virtual environment is active)Bashpip install -r requirements.txt
Run Application:Bashstreamlit run your_main_script_name.py
(Replace your_main_script_name.py with your Streamlit file name).

Technical DetailsModel: Logistic Regression, tuned with class_weight='balanced' to handle extreme class imbalance.
Deployment: Uses Streamlit, The app includes a check to guide the user if the dataset is missing.
Artifact: The trained model is saved as fraud_detection_pipeline.pkl.
Credit: Built following the tutorial by Data Science with Onur , https://youtu.be/4Od5_z28iIE?si=HhL07vyR7ndetxIF
