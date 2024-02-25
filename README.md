# ML_Kaggle_BookReview_Prediction

The project involves solving a multi-class classification problem in Natural Language Processing (NLP) where the goal is to predict ratings (0 to 5) for book reviews based on their textual content. The dataset is explored, and initial data analysis is conducted to understand its structure, check for missing values, and analyze the distribution of ratings.

Text preprocessing steps include cleaning, tokenization, stemming/lemmatization, and the removal of stopwords and punctuations. Features are engineered using TF-IDF vectorization with a combination of unigrams and bigrams. Exploratory Data Analysis (EDA) examines the class distribution of ratings.

Various machine learning models are implemented, including Logistic Regression, KMeans Clustering, Naive Bayes Multinomial Classifier, Support Vector Machine (SVM), Random Forest Classifier, Neural Network, and a Voting Classifier. Hyperparameter tuning is performed for Logistic Regression, and class imbalance is addressed using techniques like SMOTE and class_weight=balanced.

The chosen model for submission is Logistic Regression, which achieved a weighted F1 score of 0.542 on the validation test dataset. Multiple submissions are made to Kaggle to experiment with different approaches. The project faced challenges with large datasets, and efforts were made to optimize preprocessing steps and model training. The conclusion highlights the continuous learning and improvement throughout the project, with the final submission showcasing the best predictions and the team's effort.
