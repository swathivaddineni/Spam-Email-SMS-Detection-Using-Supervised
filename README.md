📩 Spam Email/sms Detection using Supervised Learning

## Project Overview

This project focuses on detecting spam emails using supervised machine learning techniques. The model classifies emails as 'spam' or 'ham' (non-spam) based on the textual content of the emails.

## Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

## Dataset.

The dataset used is the SMS/Email Spam Collection dataset. It contains labeled examples of messages categorized as spam or ham.

## Methodology

1. **Data Preprocessing**: Cleaned and prepared the email text data.
2. **Feature Extraction**: Used TF-IDF vectorizer to convert text into numerical features.
3. **Model Training**: Multinomial Naive Bayes classifier.
4. **Model Evaluation**: Accuracy, Precision, Recall, and F1-score metrics.

## Model Performance

You can view below images that directly come from the notebook:

### performance Matrix
<img width="880" height="642" alt="image" src="https://github.com/user-attachments/assets/ec3fff25-c815-4001-901c-2f75d75341f7" />

### Confusion Matrix
<img width="777" height="665" alt="image" src="https://github.com/user-attachments/assets/c8ac4b23-a2cc-4cc2-9373-e753568ae49e" />

### Accuracy Chart
<img width="640" height="287" alt="image" src="https://github.com/user-attachments/assets/566a6941-6fc3-4c23-ae6c-e7d187560dd1" />

## Sample Predictions

| Email Message                                      | Predicted Label |
|----------------------------------------------------|-----------------|
| "Congratulations! You've won a $1000 gift card."  | Spam            |
| "Meeting scheduled for tomorrow at 10 AM."        | Ham             |
| "Get cheap loans instantly with no credit check!" | Spam            |

## How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone <your-repo-link>
2. **Install dependencies:**
    ```bash
   pip install -r requirements.txt
3. **Run the Jupyter Notebook or Python script:**
    ```bash
    jupyter notebook code/spam_classifier.ipynb
4. **View results and images in the images/ folder.**
--------------
Conclusion

The Email Spam Detection system effectively classifies emails with high accuracy using Naive Bayes and TF-IDF. Future work can explore deep learning models for better performance and real-time email filtering..



