Climate Change Analysis & Prediction System
Project Overview

This project presents a comprehensive end-to-end machine learning and time-series forecasting framework developed to analyze historical global temperature variations and predict future climate trends up to the year 2100. The system processes large-scale climate datasets, performs advanced feature engineering—including CO₂ proxies and rolling statistical measures—and evaluates multiple predictive models to identify the most accurate forecasting approach.

Datasets Utilized

The analytical pipeline integrates data from globally recognized environmental repositories, ensuring both diversity and historical depth:

FAOSTAT Environmental Temperature Change Dataset
Global Land Temperature Records (Country/City/State-level)
Global Weather Repository
Project Pipeline (Core Phases)

The system is developed through a structured six-phase workflow:

1. Data Acquisition:
Automated ingestion of multiple climate datasets in CSV format from heterogeneous sources.

2. Data Cleaning and Transformation:
Standardization of data structures through reshaping (wide-to-long format), interpolation of missing values using trend-based methods, and alignment of temporal indices.

3. Exploratory Data Analysis (EDA):
Comprehensive visualization of historical climate trends, application of seasonal decomposition techniques, and correlation analysis between engineered features.

4. Model Training:
Implementation of multiple predictive models using an 80/20 chronological split to preserve temporal consistency:

SARIMA (classical statistical time-series model)
Random Forest Regressor (ensemble-based learning)
XGBoost Regressor (gradient boosting framework)
LSTM Neural Network (deep learning for sequential data)

5. Model Evaluation:
Comparative performance analysis using standardized evaluation metrics:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Mean Absolute Percentage Error (MAPE)
R² Score (coefficient of determination)

6. Future Forecasting:
Deployment of the best-performing model to generate long-term projections of global temperature anomalies up to 2100. Forecast outputs include decade-wise estimates along with 95% confidence intervals to quantify uncertainty.

Key Outcomes
Developed a unified global timeline illustrating temperature anomaly trends
Benchmarked traditional statistical models against advanced machine learning and deep learning approaches
Generated long-range climate forecasts with key milestone projections for 2030, 2050, 2075, and 2100
Automated the generation and storage of all visual outputs within the outputs/plots/ directory
Project Context

This system was developed as a Final Year Project in Data Science and Machine Learning, demonstrating the integration of data engineering, statistical modeling, and AI-driven forecasting to address real-world climate challenges.