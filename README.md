# Student_Exam_Score_Prediction
A linear regression model predicts student exam scores using hours studied, previous scores, and attendance. Feature engineering and EDA were applied. Insights help identify underperforming students early, enabling targeted academic support and intervention.

# Model Description
This project uses a Linear Regression model to predict a student’s exam score based on features including:
1. Hours Studied (simulated)
2. Previous Exam Score (engineered from existing scores)
3. Attendance Rate (simulated)
4. Exam Score (target: average of math, reading, and writing scores)

Since the original dataset lacked these features directly, feature engineering and synthetic generation were used for realism.

The model pipeline includes:
1. Data preprocessing and feature engineering
2. Exploratory Data Analysis (EDA) with heatmaps and visualizations
3. Training/testing split and model building
4. Performance evaluation using Mean Squared Error (MSE) and R² Score
5. Risk analysis and student profiling based on predictions
