# Toxic Comments Classifier

This project focuses on building machine learning models to classify whether a comment is toxic or not. The goal is to apply natural language processing (NLP) techniques to clean, process, and classify text data using machine learning algorithms.

## Steps Followed:

### 1. **Data Cleaning**
- Applied tokenization and removed special characters to prepare the text for modeling.
- Performed **lemmatization** to reduce words to their root forms (e.g., "running" becomes "run"), improving model generalization.

### 2. **Feature Extraction**
- Generated word embeddings using various techniques such as **Word2Vec**, **TF-IDF**, and **CountVectorizer** to convert text into vector representations, which can be fed into machine learning models.

### 3. **Model Building**
- Split the dataset into **training** (70%) and **test** (30%) sets.
- Trained different machine learning models like **Random Forest Classifier** and **Decision Tree** to predict whether a comment is toxic.
- Used **cross-validation** to compare model performance based on metrics such as **F1-score** and **AUC** to select the best model.

### 4. **Model Evaluation**
- Evaluated the final model's performance on the test data using standard metrics such as F1-score and AUC.

## Experience and Key Learnings:

- Applied data manipulation and machine learning skills in the context of **Natural Language Processing** (NLP).
- Discovered new techniques to enhance the performance of **tree-based algorithms**.
- Gained experience using **PySpark pipelines** for both data manipulation and machine learning, which are essential for scaling machine learning workflows on large datasets.
- Realized the importance of further exploring the content of comments to identify more toxic-related words and improve the classifier’s accuracy.
