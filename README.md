# Music Genre Prediction

This project aims to improve the recommendation system of the music streaming platform "MiFaSol" by predicting the genre of a track based on its features using supervised machine learning techniques.

## Tech Stack

- **Programming Languages**: Python
- **Data Analysis and Visualization**: Pandas, NumPy, Matplotlib, Seaborn, Sweetviz
- **Correlation Analysis**: Phik
- **Model Optimization**: Optuna
- **Machine Learning Models**: CatBoost, RandomForest, LogisticRegression, KNeighbors
- **Data Preprocessing**: Scikit-learn (IterativeImputer, OneHotEncoder, PowerTransformer, StandardScaler)
- **Model Evaluation**: Scikit-learn (cross_val_score, StratifiedKFold, f1_score, confusion_matrix, ConfusionMatrixDisplay)

## Summary

- **Preprocessing**: Handled missing values, outliers, and duplicates. Data includes 11 numerical, 3 categorical, and 1 text feature.
- **EDA**: Identified correlations and key features impacting genre classification.
- **Model Training**: Four models were trained with the CatBoostClassifier performing the best (F1 micro = 0.51).
- **Evaluation**: Best model evaluated using cross-validation, showing high accuracy in identifying classical music but struggling with rare genres like Hip-hop.

## Conclusion

The developed model enhances the recommendation system by providing accurate genre predictions, leading to improved user satisfaction and engagement with the "MiFaSol" platform.
