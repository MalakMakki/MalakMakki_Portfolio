# Cyber Attack Detection using Machine Learning:
## Objective: Build an efficient neural network model to predict any cyber attack based on some features.
## Description:
This project utilizes the CICIDS 2017 dataset, which is divided into multiple sub-datasets that we combine to form a larger dataset on which we proceed with our work.
The first step was deep data preprocessing. After concatenating the datasets, we handled all missing values and performed all necessary rearrangements to ensure a high-quality dataset for optimal results.
The second step involved dimensionality reduction. We conducted a correlation analysis to study the relationships between all features. If two features were strongly correlated, we excluded one of them to make the data more flexible for modeling without losing any essential information. A detailed explanation with code is available in the notebook attached in the drive link below.
After that, I proceeded with model building. I built a neural network model with initial parameters, then analyzed the results to fine-tune certain parameters based on my desired accuracy. I found that there was some imbalance in the dataset, so I applied the SMOTE technique, which enhanced performance. I also adjusted parameters such as the number of epochs to achieve the best model accuracy.
## Results:
After conducting the necessary analysis, I obtained excellent results, with an accuracy reaching 0.999 and an F1-score of 0.9, which is an outstanding outcome.
You can check the code in this zipped file: https://drive.google.com/drive/folders/1XU4M7QzGODSjK5FUJlrKo0rlRTCy-ZE_?usp=sharing

