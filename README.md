Introduction:

The project titled Sentiment Analysis of Restaurant Reviews focuses on analyzing customer feedback using machine learning techniques. In the digital era, online reviews significantly influence the reputation and business of restaurants. Therefore, understanding the sentiment behind these reviews helps stakeholders make informed decisions to enhance customer satisfaction and improve service quality.

Objective:

The main goal of this project is to automatically classify restaurant reviews as positive or negative based on their textual content. This classification aids restaurant owners in quickly identifying areas that need improvement or appreciation, thereby helping them maintain a good relationship with their customers.

Tools and Technologies Used:

The project was developed using Python, with the help of key libraries such as:
pandas – for data manipulation,
scikit-learn – for model building and evaluation,
matplotlib – for visualization.
Text data was vectorized using TF-IDF (Term Frequency-Inverse Document Frequency) to convert raw reviews into a numerical format suitable for machine learning models.

Dataset and Preprocessing:

Although the dataset initially contained 1000 labeled restaurant reviews, the core task involved removing the raw dataset in the final presentation. The data was split into 80% training and 20% testing sets. Preprocessing involved removing noise, tokenizing, and applying TF-IDF transformation to extract meaningful features from the text.

Model Building:

Two classification algorithms were applied:

1.Support Vector Machine (SVM)

2.Logistic Regression

Both models were trained using the TF-IDF features extracted from the reviews. They were then evaluated on the test data using accuracy as the primary metric.

Results and Evaluation:

Both SVM and Logistic Regression models achieved an accuracy of 85%, indicating good performance in sentiment classification. Confusion matrices were also used to analyze the models' ability to distinguish between positive and negative reviews effectively.

Conclusion:

The project demonstrates the effective use of machine learning algorithms in performing sentiment analysis on customer reviews. It shows that traditional models like SVM and Logistic Regression, when combined with TF-IDF, can produce reliable results.
