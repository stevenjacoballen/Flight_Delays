# Flight_Delays

## Research Question

How accurately (via recall) can flight delays be predicted using airline performance and weather data?



## Project Outline
1. **Import and Clean Data:** Two datasets consisting of airline performance, and weather data.
2. **PostgreSQL Database:** Create database from the cleaned datasets above, and then query database for finalized project dataset.
3. **Exploratory Data Analysis.**
4. **Machine Learning:** Scale data and train the two following models for binary classification (delayed flight or not delayed) to establish baseline performance. Both models will also undergo hyperparameter tuning and will have run-times and performance tracked.
    * Logistic Regression
    * Gradient Boosting Classifier
5. **Principal Component Analysis:** Conduct PCA on data set to reduce dimensionality and ideally, increase model performance/efficiency.
6. **Retrain Models:** Retrain both models after PCA using the optimally tuned hyperparameters. 
7. **Results, Observations, Conclusion:** Evaluate baseline, tuned, and post-PCA performance for both ML models.
