#  Iris Flower Classification using Artificial Neural Networks (ANN)

##  Project Overview

This project develops an Artificial Neural Network (ANN) using TensorFlow/Keras to classify Iris flowers into three species: Setosa, Versicolor, and Virginica. The workflow includes data preprocessing, feature scaling, label encoding, model training, evaluation, and prediction on unseen samples.

The Iris dataset is one of the most popular datasets in machine learning and serves as an excellent introduction to multiclass classification using deep learning.

---

##  Objectives

* Perform data preprocessing and exploratory checks.
* Encode categorical target labels.
* Normalize feature values using StandardScaler.
* Build a deep learning ANN model.
* Train and evaluate the model.
* Generate classification metrics.
* Save the trained model and scaler.
* Predict species for unseen flower samples.

---

##  Dataset Information

The Iris dataset contains 150 flower samples with 4 numerical features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

Target Classes:

* Setosa
* Versicolor
* Virginica

Dataset Size: **150 Rows × 5 Columns**

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* TensorFlow
* Keras
* Joblib
* Jupyter Notebook

---

##  Data Preprocessing

The following preprocessing steps were performed:

* Null Value Check
* Duplicate Value Check
* Dataset Inspection
* Label Encoding
* One-Hot Encoding
* Feature Scaling using StandardScaler
* Train-Test Split (80:20)

---

##  ANN Architecture

| Layer          | Neurons    | Activation |
| -------------- | ---------- | ---------- |
| Input Layer    | 4 Features | -          |
| Hidden Layer 1 | 10         | ReLU       |
| Hidden Layer 2 | 8          | ReLU       |
| Output Layer   | 3          | Softmax    |

### Model Configuration

* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Metric: Accuracy
* Epochs: 50
* Batch Size: 8

---

##  Project Workflow

Load Dataset

⬇️

Data Preprocessing

⬇️

Label Encoding

⬇️

One-Hot Encoding

⬇️

Feature Scaling

⬇️

Train-Test Split

⬇️

ANN Model Building

⬇️

Model Training

⬇️

Model Evaluation

⬇️

Accuracy & Classification Report

⬇️

Model Saving

⬇️

Prediction on Unseen Data

---

##  Results

* Achieved high classification accuracy (96%–100%).
* Successfully classified all three Iris species.
* Demonstrated strong multiclass prediction performance.
* Generated detailed classification metrics.
* Saved the trained model and scaler for future deployment.

---

##  Project Structure

```text
Iris_ANN_Project/
│
├── Iris_ANN_Classification.ipynb
├── iris_ann_model.keras
├── iris_scaler.pkl
├── requirements.txt
└── README.md
```

##  Installation

```bash
pip install -r requirements.txt
```

##  Run Project

```bash
jupyter notebook
```

Open:

```text
Iris_ANN_Classification.ipynb
```

and run all cells.

---

##  Sample Prediction

```python
new_flower = [[5.1, 3.5, 1.4, 0.2]]
```

### Predicted Output

```text
Setosa
```

---

##  Conclusion

This project successfully developed a deep learning-based ANN model for Iris flower classification. Through data preprocessing, feature scaling, and neural network training, the model achieved excellent accuracy and reliably classified flower species. The trained model can be reused for future predictions and serves as a strong foundation for multiclass classification projects using TensorFlow and Keras.

---

##  Author

**Shamsiya KP**

AI & Data Science Enthusiast | Machine Learning & Deep Learning Developer
