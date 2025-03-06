# stock-price-using-nlp
This project focuses on predicting stock market movements based on news headlines using a Random Forest Classifier. The dataset contains historical stock market data and associated news headlines. The goal is to preprocess the text data, extract features using CountVectorizer with bigrams, and train a machine learning model to classify whether the stock market will go up or down.
Key Steps:

    Data Preprocessing:

        Remove special characters and numbers from headlines.

        Convert all text to lowercase.

        Combine multiple headlines into a single sentence for each row.

    Feature Extraction:

        Use CountVectorizer with bigrams to convert text into numerical features.

    Model Training:

        Train a Random Forest Classifier on the preprocessed training data.

    Evaluation:

        Test the model on unseen data and evaluate performance using:

            Confusion Matrix

            Accuracy Score

            Classification Report

Libraries Used:

    Pandas: For data manipulation and analysis.

    Scikit-learn: For feature extraction, model training, and evaluation.

Results:

The model's performance is evaluated using metrics like accuracy, precision, recall, and F1-score. The results are displayed in the form of a confusion matrix and classification report.

This project is a great example of how natural language processing (NLP) and machine learning can be applied to financial data for predictive analysis
