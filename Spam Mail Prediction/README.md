# Spam Mail Prediction

This project uses machine learning to classify emails as spam or ham (not spam) based on their content. The model is trained on a dataset of labeled emails and can predict whether a new email is likely to be spam or not.

## Project Overview

The goal of this project is to build a classification model that can accurately identify spam emails. This involves:

1. Preprocessing the email data.
2. Converting text data to feature vectors.
3. Training a Logistic Regression classifier.
4. Evaluating the model's performance.
5. Creating a predictive system for new emails.

## Dataset

The dataset used in this project is [mail_data.csv](https://github.com/DarkGuardian641/Learn-Machine-Learning/blob/main/Spam%20Mail%20Prediction/mail_data.csv), which contains the following columns:

- Category: The label indicating whether the email is 'spam' or 'ham'.
- Message: The text content of the email.

### Dataset Preview

Below is a preview of the first few rows of the dataset:

| Category | Message |
|:--------:|:--------|
| ham | Go until jurong point, crazy.. Available only in bugis n great world la e buffet... Cine there got amore wat... |
| ham | Ok lar... Joking wif u oni... |
| spam | Free entry in 2 a wkly comp to win FA Cup final tkts 21st May 2005. Text FA to 87121 to receive entry question(std txt rate)T&C's apply 08452810075over18's |
| ham | U dun say so early hor... U c already then say... |
| ham | Nah I don't think he goes to usf, he lives around here though |

The dataset consists of **5,572 emails** in total, with a mix of spam and ham messages.

## Requirements

The following Python libraries are required to run the notebook:

- numpy
- pandas
- scikit-learn

Install the necessary libraries using the following command:

```bash
pip install numpy pandas scikit-learn
```

## Notebook Structure

1. **Importing Dependencies**: Necessary Python libraries are imported.
2. **Data Collection and Preprocessing**: The dataset is loaded and preprocessed.
3. **Label Encoding**: Categorical labels are encoded (spam as 0, ham as 1).
4. **Train-Test Split**: Data is split into training and testing sets.
5. **Feature Extraction**: Text is converted to feature vectors using TF-IDF.
6. **Model Training**: A Logistic Regression model is trained on the feature vectors.
7. **Model Evaluation**: The model's accuracy is evaluated on both training and test data.
8. **Building a Predictive System**: A system to predict whether new emails are spam or ham.

## Running the Project

1. Clone the repository or download the project files.
2. Ensure all required libraries are installed.
3. Open the [spam-mail-prediction.ipynb](https://github.com/DarkGuardian641/Learn-Machine-Learning/blob/main/Spam%20Mail%20Prediction/spam-mail-prediction.ipynb) notebook in Jupyter Notebook or any other compatible environment.
4. Run the notebook cells sequentially to see the data analysis, model training, and predictions.

## Results

The Logistic Regression model achieved excellent performance:

- **Accuracy on Training Data**: 96.77%
- **Accuracy on Test Data**: 96.68%

These results indicate that the model is highly effective at distinguishing between spam and ham emails, with minimal overfitting.

## Conclusion

This project demonstrates how machine learning can be applied to text classification problems, specifically for spam detection. The high accuracy achieved by the model shows that Logistic Regression combined with TF-IDF feature extraction is an effective approach for this task.

The simplicity and interpretability of this approach make it suitable for real-world applications, where identifying spam emails accurately is important for user experience and security.

## Author
[Atharva Baikar](https://github.com/DarkGuardian641)
