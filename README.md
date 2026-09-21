🌸 Iris Flower Classification with Random Forest

A machine learning project built with Python, `scikit-learn`, `pandas`, and `seaborn` to classify Iris flower species using physical measurements of sepals and petals.

This repository demonstrates data loading, feature handling, training a **Random Forest Classifier**, model evaluation, and saving a visual confusion matrix.



## 📌 Project Overview

The objective is to accurately predict the species of an Iris flower based on 4 measurements:

1. **Iris setosa**
2. **Iris versicolor**
3. **Iris virginica**

### 📊 Dataset Features

* `sepal length (cm)`
* `sepal width (cm)`
* `petal length (cm)`
* `petal width (cm)`

---

## 🛠️ Tech Stack & Requirements

* **Python 3.8+**
* **pandas** (Data handling & mapping)
* **scikit-learn** (Dataset, machine learning model, metrics)
* **seaborn** & **matplotlib** (Confusion matrix visual analysis)

### Installation

Clone the repository and install the required Python packages:

```bash
git clone https://github.com/your-username/iris-flower-classification.git
cd iris-flower-classification
pip install pandas scikit-learn seaborn matplotlib
```

---

## 🚀 Usage

Run the Python script to train the model, output evaluation metrics, and generate the confusion matrix plot:

```bash
python iris_classification.py
```

---

## 📈 Methodology & Workflow

1. **Data Loading & Mapping:** Loads the Iris dataset directly via `sklearn.datasets.load_iris` and maps target numbers to human-readable species labels (`setosa`, `versicolor`, `virginica`).
2. **Data Preprocessing & Splitting:** Prepares feature matrices $X$ and labels $y$, splitting them into an **80% training set** and **20% testing set** (`random_state=42`).
3. **Model Training:** Trains an Ensemble **Random Forest Classifier** (`RandomForestClassifier`) model.
4. **Model Evaluation:** Evaluates model performance using Accuracy Score, Classification Report (Precision, Recall, F1-Score), and Confusion Matrix.
5. **Visualization:** Displays and exports a heatmap of the Confusion Matrix as `iris_confusion_matrix.png`.

---

## 📁 Project Structure

```text
├── README.md                 # Project documentation
├── iris_classification.py    # Main script (Loads data, trains model, exports matrix plot)
└── iris_confusion_matrix.png # Generated confusion matrix heatmap
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
