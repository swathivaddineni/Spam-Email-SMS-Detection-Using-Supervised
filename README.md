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

## Dataset

The dataset used is the SMS/Email Spam Collection dataset. It contains labeled examples of messages categorized as spam or ham.

## Methodology

1. **Data Preprocessing**: Cleaned and prepared the email text data.
2. **Feature Extraction**: Used TF-IDF vectorizer to convert text into numerical features.
3. **Model Training**: Multinomial Naive Bayes classifier.
4. **Model Evaluation**: Accuracy, Precision, Recall, and F1-score metrics.

## Model Performance

You can view below images that directly come from the notebook:

### performance Matrix

![Confusion Matrix](<img width="957" height="660" alt="Screenshot 2025-10-26 140449" src="https://github.com/user-attachments/assets/f65c3fb4-595e-4303-bef5-e39b3003e412" />
)

### Confusion Matrix

![Confusion Matrix](<img width="788" height="630" alt="Screenshot 2025-10-26 134702" src="https://github.com/user-attachments/assets/57ecf42b-7485-44b2-97c2-37b0a5b3d44a" />
)

### Accuracy Chart

![Accuracy Chart](<img width="614" height="301" alt="Screenshot 2025-10-26 151238" src="https://github.com/user-attachments/assets/38fd69c0-b6c2-4f21-8ee7-50537291825c" />
)

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



