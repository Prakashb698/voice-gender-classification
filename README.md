# Voice Gender Classification using Machine Learning

This project classifies voice samples as male or female based on acoustic features using several machine learning models.

## 📌 Objective

To develop and compare classification models that can predict gender from voice sample properties such as mean frequency, entropy, and pitch range.

## 🧠 Models Used

- Decision Tree
- Random Forest
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM - Linear Kernel)

## 📊 Evaluation Metrics

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Misclassification Rate

A comparison table was created to summarize results across all models.

## 📈 Visualizations

- Pie chart of gender distribution
- Boxplot of mean frequency by gender
- Histogram of mode frequency
- Correlation heatmap
- Pairplot of selected features

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 🧪 Usage

Clone this repo and run the notebook:

```bash
git clone https://github.com/yourusername/voice-gender-classification.git
cd voice-gender-classification
jupyter notebook notebook/voice_gender_classification.ipynb
