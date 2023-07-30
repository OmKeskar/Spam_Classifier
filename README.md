# Spam Mail Classifier

This project is a spam mail classifier that uses Support Vector Machine (SVM) to classify emails as spam or non-spam. It utilizes the scikit-learn library in Python for machine learning tasks.

## Dataset

The dataset used for training and testing the classifier is the https://www.kaggle.com/datasets/ganiyuolalekan/spam-assassin-email-classification-dataset

Please note that the dataset should be in CSV format and contain two columns: 'Email Text' containing the email content and 'Target' containing the labels (0 for non-spam and 1 for spam).

## Usage

1. Place the downloaded dataset file ('spam_assassin.csv') in the project directory.

2. Run the 'spam_classifier.py' file using the following command:
   ```
   python spam_classifier.py
   ```

3. The program will load the dataset, split it into training and testing sets, create an SVM classifier, train the classifier, make predictions on the test data, and calculate the accuracy of the classifier.

4. The accuracy of the classifier will be displayed in the console.

## Customization

- If you have a different dataset, make sure it is in the appropriate format (CSV) and contains the necessary columns ('Email Text' and 'Target'). Update the code accordingly to load and preprocess your dataset.

- You can experiment with different SVM parameters by modifying the code in the file. For example, you can change the kernel type, regularization parameter, or class weights to improve the classifier's performance.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

