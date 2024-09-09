# Multilingual Customer Support Ticket Classification

This project focuses on classifying multilingual customer support tickets using various machine learning models. The dataset contains customer support emails in multiple languages, including German, English, Spanish, and French. The objective is to classify these tickets into different departments based on the email content, and prioritize them accordingly.

## Project Structure

The project includes the following steps:

1. **Exploratory Data Analysis (EDA)**: Understanding the dataset and visualizing the distribution of ticket categories.

2. **Data Preprocessing**: Cleaning and transforming the text data for model training using techniques like TF-IDF vectorization and tokenization.

3. **Model Training**: Training the dataset on different machine learning models:
   - LSTM (Long Short-Term Memory)
   - SGD (Stochastic Gradient Descent)
   - KNN (K-Nearest Neighbors)
   - K Means Clustering
   - XGBoost (Extreme Gradient Boosting)
   - SVM (Support Vector Machine)

4. **Evaluation and Prediction**: Evaluating the models using metrics like accuracy, precision, recall, and F1-score.

## Dataset

The dataset is a collection of customer support email tickets labeled by:
- **Department**: The department the ticket is related to.
- **Priority**: The urgency of the ticket.
- **Language**: The language in which the email is written.
- **Category**: Software, hardware, or accounting category.
- **Full Email Text**: The complete email body.

Dataset Link : https://www.kaggle.com/datasets/tobiasbueck/email-ticket-text-german-classification

## Results

After training, you can compare the performance of different models using the classification reports and accuracy scores. The best-performing model can be selected based on these results.

## Contributing

If you wish to contribute to this project, feel free to fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

The project was inspired by the need to optimize multilingual customer support using machine learning techniques.

Special thanks to the authors and maintainers of the Python libraries used in this project.
