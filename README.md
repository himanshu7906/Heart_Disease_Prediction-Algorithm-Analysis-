# Heart Disease Prediction Using Machine Learning

## Overview
Heart disease is a leading cause of mortality worldwide, making early detection and prevention crucial. This project leverages **Machine Learning** to predict heart disease based on various health parameters, improving research and proactive healthcare solutions.

## Project Description
The project involves analyzing a heart disease dataset, preprocessing the data, and training multiple **classification models** to predict the presence of heart disease in patients. Different **Machine Learning algorithms** were implemented to determine the most effective model.

## Dataset
- **Source:** [UCI Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
- **Type:** Binary classification (Presence or Absence of Heart Disease)
- **Features:** Various medical attributes such as age, cholesterol levels, blood pressure, etc.

## Algorithms Used
The following machine learning models were implemented and evaluated:

1. **Logistic Regression** (Scikit-learn)
2. **Naive Bayes** (Scikit-learn)
3. **Support Vector Machine (SVM)** (Scikit-learn)
4. **K-Nearest Neighbors (KNN)** (Scikit-learn)
5. **Decision Tree** (Scikit-learn)
6. **Random Forest** (Scikit-learn)
7. **XGBoost** (Scikit-learn)
8. **Artificial Neural Network (ANN)** (Keras)

## Results
- The **Random Forest** model achieved the highest accuracy of **95%**, making it the most effective for this dataset.
- Performance evaluation was conducted using metrics such as accuracy, precision, recall, and F1-score.

## Installation & Usage
To run this project, follow these steps:

### Prerequisites
Ensure you have **Python 3.x** and the required libraries installed.

### Installation
```bash
# Clone the repository
git clone https://github.com/your-username/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction

# Install dependencies
pip install -r requirements.txt
```

### Running the Model
```bash
# Run the Jupyter Notebook
jupyter notebook
# Open the .ipynb file and execute the cells
```

## Future Enhancements
- **Hyperparameter tuning** to further optimize model performance.
- **Feature engineering** for improved prediction accuracy.
- **Deployment** as a web-based application for real-world use.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request with improvements.

## License
This project is licensed under the **MIT License**.

---


