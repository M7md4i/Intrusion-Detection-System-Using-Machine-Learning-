# Intrusion Detection System and Machine Learning TII-SSRC-23 Dataset

## Overview
The **TII-SSRC-23** dataset is a comprehensive collection of network traffic data designed to support cybersecurity and network analysis research. This dataset includes both benign and malicious traffic types, addressing challenges like class imbalance and large size. The dataset has been preprocessed and balanced for effective use in machine learning projects.

## Project Phases

### Phase 1: Data Preparation and Reduction
- **Data Cleaning:** Removed irrelevant columns, handled missing data, and reduced the size from 30 GB to 1 GB.
- **Balancing:** Used downsampling and upsampling techniques to handle class imbalance, ensuring fairness for machine learning models.
- **Normalization:** Applied Min-Max scaling to standardize continuous features.
- **Final Output:** A balanced and normalized dataset saved for further analysis.

### Phase 2: Data Analysis and Model Training
- **Exploratory Data Analysis (EDA):** Visualized data distribution and performed correlation analysis.
- **Machine Learning:** Trained several machine learning models such as Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, KNN, SVM, and XGBoost.
- **Performance:** Models were evaluated based on accuracy, precision, recall, and F1-score. The results show promising performance, with accuracy ranging from 94% to 100%.

## Libraries Used
- **Pandas:** Data manipulation and analysis.
- **Scikit-learn:** Preprocessing tools and machine learning algorithms.
- **TensorFlow/Keras:** Neural network modeling.
- **XGBoost:** Gradient Boosting implementation.

## Dataset Information
- **Size:** 8+ million rows, 86 columns.
- **Features:** Includes various network traffic characteristics such as packet lengths, flow duration, protocol types, and more.
- **Classes:** The dataset is labeled with both benign and malicious traffic, with multiple subtypes like DoS attacks, Mirai DDoS, and information gathering.
