🧠 Naive Bayes Classifier — Social Network Ads

This project demonstrates how to build, train, and evaluate a Gaussian Naive Bayes classifier using the Social Network Ads dataset.
The model predicts whether a user will purchase a product based on their Age and Estimated Salary.

📦 Libraries Used

pandas, numpy – data handling

matplotlib – visualization

scikit-learn – preprocessing, model training, evaluation

joblib – saving the trained model

⚙️ Workflow

Load dataset from data/Social_Network_Ads.csv

Split data into training and test sets

Scale features using StandardScaler

Train a Gaussian Naive Bayes model

Evaluate the model with metrics (accuracy, precision, recall, F1-score) and a confusion matrix

Save the trained model to models/classifier.pkl (consider saving the scaler too)

🧩 Example Prediction
classifier.predict(sc.transform([[30, 87000]]))

📊 Output

Model evaluation metrics

Confusion matrix visualization