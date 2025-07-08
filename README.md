

# ❤️ Heart Disease Prediction Using ANN

This project aims to predict the presence of heart disease using an Artificial Neural Network (ANN) built with Keras. The model performs binary classification based on patient health data and has been trained and evaluated using standard machine learning practices.

---

## 📁 Dataset

The dataset used contains several clinical features related to heart health such as:

- Age
- Gender
- Resting blood pressure
- Cholesterol level
- Fasting blood sugar
- ECG results
- Max heart rate
- Exercise-induced angina
- And more...

The data was preprocessed by standardizing features and splitting into training and test sets.

---

## 🧠 Model Architecture

The ANN is implemented using **Keras Sequential API** with:

- Input Layer: matching the number of features
- Hidden Layer(s): 1 or more dense layers with ReLU activation
- Output Layer: softmax activation for classification
- Loss Function: `categorical_crossentropy`
- Optimizer: `Adam`
- Metrics: `accuracy`

---

## 🛠️ Preprocessing Steps

1. **Data Standardization** using `StandardScaler`
2. **Train-Test Split** (e.g., 80:20)
3. **One-hot Encoding** for target labels
4. **Model Training** over defined number of epochs

---

## 📊 Evaluation

Model performance was evaluated using:

- Accuracy
- Loss
- Prediction comparison between actual and predicted labels

---

## 📌 Results

While exact metrics may vary depending on hyperparameters and data shuffling, the model was able to classify the presence or absence of heart disease with promising accuracy on the test set.


