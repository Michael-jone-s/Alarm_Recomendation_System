# Smart Alarm Recomendation System

## Summary

Our Smart Alarm Recommendation System uses Python, Pandas, Scikit-learn, regex, and Matplotlib to optimize alarm settings. Python's versatility aids data handling and machine learning. Pandas ensures clean data management, while regex extracts crucial information from logs. Scikit-learn trains models for optimal alarm predictions, and Matplotlib visualizes insights. This system aims to enhance user experience by improving alarm functionality seamlessly.

## Technologies Used

- Python : The programming language that will be used to write the application code.
- Pandas : Acting as our data manager, Pandas efficiently cleans, manipulates, and analyzes data, streamlining our workflow like an organized assistant.
- Regular Expressions (regex) : A powerful tool for deciphering patterns in text, essential for extracting specific information like timestamps or alarm events from log files.
- Scikit-learn : Our go-to for machine learning tasks, offering a range of algorithms to train models for predicting optimal alarm times based on historical data.
- Matplotlib : Enabling us to create captivating visualizations, Matplotlib brings our data to life by showcasing trends over time, event distributions, and more.

## Approach

1. **Data Extraction:** Utilize regex patterns to extract relevant information from clock log files, such as timestamps, alarm events, and actions.
   
2. **Data Preprocessing:** Clean and preprocess the extracted data, including converting timestamps to datetime format, handling missing values, and feature engineering.
   
3. **Exploratory Data Analysis (EDA):** Analyze the extracted data through visualizations and statistical methods to identify trends, anomalies, and key insights.
   
4. **Model Building:** Train machine learning models, such as Random Forest Regressor and Gradient Boosting Regressor, to predict optimal alarm times based on input parameters. The system achieves a high accuracy level, with a GBM Mean Squared Error of 25271.66 and an R^2 Score of 0.9998.
   
5. **Recommendation System:** Develop a recommendation system where users can input preferences like day of the week, time of day, and current alarm time to receive optimal alarm time recommendations.

## Conclusion

The Clock Data Extraction project leverages Python, regex, pandas, machine learning, and data visualization techniques to extract, analyze, and optimize alarm settings based on historical alarm data. The developed recommendation system provides users with personalized alarm time suggestions for enhanced user experience.
