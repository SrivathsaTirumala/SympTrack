# Predicting Heart Disease and Diabetes Using Machine Learning

## Overview
This project demonstrates the application of machine learning (ML) to predict heart disease and diabetes, two of the most significant global health challenges. By leveraging shared risk factors such as glucose levels, cholesterol, BMI, and age, the system provides a unified predictive model that offers superior accuracy, scalability, and real-time adaptability. The system employs advanced ML algorithms like Random Forest and Neural Networks, combined with feature engineering, data preprocessing, and hyperparameter tuning, to deliver actionable insights for healthcare providers.

## Key Features
- **Unified Risk Prediction**: Simultaneously predicts the likelihood of heart disease and diabetes by analyzing shared risk factors.
- **Real-Time Data Integration**: Incorporates inputs from wearable devices, such as glucose monitors and fitness trackers, to provide up-to-date predictions.
- **Explainability**: Uses techniques like SHAP to provide interpretable predictions for clinical decision-making.
- **User-Friendly Interface**: Deployed as a web-based application using Streamlit, making it accessible to healthcare professionals and patients.

## Methodology
### Data Collection
- Historical patient data, including medical histories, lab results, and demographics.
- Real-time metrics from wearable devices for continuous monitoring.

### Data Preprocessing
- Handled missing values, outliers, and inconsistencies.
- Normalized features for uniformity.

### Feature Engineering
- Derived meaningful variables like BMI and risk scores.
- Selected relevant predictors through correlation analysis.

### Model Training
- Implemented Random Forest for its robustness and feature importance insights.
- Complemented with Neural Networks to capture non-linear relationships.

### Evaluation and Optimization
- Metrics: Accuracy, Precision, Recall, F1-Score.
- Techniques: Cross-validation and hyperparameter tuning.

### Deployment
- Deployed using Streamlit as an intuitive web application.

## Results
- Achieved high accuracy and reliability in predicting heart disease and diabetes.
- The Random Forest model emerged as the most effective for high-dimensional data.
- Neural Networks further improved prediction performance by addressing complex data patterns.

## Future Work
- **Explainability**: Enhance interpretability using advanced XAI techniques like SHAP.
- **Multi-Disease Prediction**: Expand the system to include conditions like hypertension, kidney disease, and cancer.
- **Advanced Time-Series Analysis**: Integrate LSTM networks for tracking disease progression.
- **IoT Integration**: Utilize wearable devices for real-time monitoring and dynamic updates.
- **Mobile App**: Develop a mobile application to increase accessibility for patients and providers.
- **Federated Learning**: Implement privacy-preserving AI methods to ensure data security.
- **Clinical Trials**: Validate the system in real-world healthcare settings to measure its impact on patient outcomes.

## Technologies Used
- **Programming Languages**: Python
- **Libraries**: Streamlit, NumPy, Pandas, Scikit-learn, SHAP
- **Models**: Random Forest, Logistic Regression
- **Tools**: Visual Studio Code, GitHub

## References
1. Katarya, R., & Srinivas, P. (2020). Predicting heart disease at early stages using machine learning: A survey. *2020 International Conference on Electronics and Sustainable Communication Systems (ICESC)*, pp. 302–305.
2. Parashar, A., Gupta, A., & Gupta, A. (2014). Machine learning techniques for diabetes prediction. *International Journal of Emerging Technologies and Advanced Engineering*, 4(3), 672–675.
3. Breiman, L. (2001). Random forests. *Machine Learning*, 45(1), 5–32.
4. Lundberg, S. M., & Lee, S. I. (2017). A Unified Approach to Interpreting Model Predictions. *Advances in Neural Information Processing Systems*, 30, 4765–4774.
5. Rajkomar, A., Dean, J., & Kohane, I. (2019). Machine Learning in Medicine. *New England Journal of Medicine*, 380(14), 1347–1358.

## Step by Step procedure to run this project
  # Install the requirements
## 1. pip install -r requirements.txt
  # Run the project using jupyter notebook
## 2. Run each cell by using Shift+Enter
  # To run the streamlit file,  Use
## 3. python3 -m streamlit run main.py
   
## You may need to install additional libraries for running the jupyter notebooks.

## 
