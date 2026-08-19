# Gastrointestinal-Tract-Cancer-Classification-using-ResNet50

## 📌 Overview

Deep learning-based gastrointestinal tract cancer classification using ResNet50. The project combines Grad-CAM, SHAP, and LIME for explainable AI, highlighting important image regions and features that influence model predictions for transparent and interpretable medical image analysis.

The complete model development and experimentation were performed using **Google Colab**.

## 🚀 Key Features

* ResNet50-based image classification
* Histopathology image preprocessing
* Model training and validation
* Performance evaluation using classification metrics
* **Grad-CAM** for visualizing important regions
* **SHAP** for feature-level explanations
* **LIME** for local prediction explanations
* Explainable predictions for medical image analysis

## 🧠 Model

**ResNet50** is used as the primary deep learning architecture. Its residual connections help train deeper networks effectively while reducing the vanishing-gradient problem.

### Explainability Methods

| Method   | Purpose                                                |
| -------- | ------------------------------------------------------ |
| Grad-CAM | Highlights image regions influencing predictions       |
| SHAP     | Explains feature contributions to predictions          |
| LIME     | Provides local explanations for individual predictions |

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* ResNet50
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* SHAP
* LIME
* Google Colab

## 📂 Project Structure

```text
Gastrointestinal-Tract-Cancer/
│
├── dataset/
├── notebooks/
│   └── GI_Cancer_ResNet50.ipynb
│
├── results/
│   ├── confusion_matrix.png
│   ├── gradcam/
│   ├── shap/
│   └── lime/
│
├── README.md
└── requirements.txt
```

## ▶️ How to Run

### 1. Open in Google Colab

Upload the notebook to **Google Colab** or open the `.ipynb` file directly.

### 2. Install Dependencies

```bash
pip install tensorflow numpy pandas matplotlib scikit-learn shap lime
```

### 3. Load Dataset

Upload or mount the gastrointestinal tract histopathology dataset in Google Colab and update the dataset path in the notebook.

### 4. Train the Model

Run the preprocessing, training, and evaluation cells in the notebook.

### 5. Generate Explanations

After training, use:

* **Grad-CAM** to visualize important regions.
* **SHAP** to analyze feature contributions.
* **LIME** to explain individual predictions.

## 📊 Evaluation

The model can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## 🔍 Explainable AI

A key objective of this project is not only to classify images but also to make predictions more interpretable. Grad-CAM, SHAP, and LIME provide visual and feature-level insights into the model's decision-making process.

## Results
<img width="1134" height="577" alt="image" src="https://github.com/user-attachments/assets/a791cb7f-a350-4738-829f-9fbf8f1f5aaf" />

<img width="1711" height="557" alt="image" src="https://github.com/user-attachments/assets/6204d175-01ad-450c-97b7-58597f427e47" />

<img width="1315" height="462" alt="image" src="https://github.com/user-attachments/assets/e64844ea-a968-4455-a60c-af4bf57e7830" />


## ⚠️ Disclaimer

This project is developed for **research and educational purposes only**. It is not intended to provide medical diagnosis or replace professional clinical judgment.

## 👩‍💻 Author

**N Aishwarya**
Information Science and Engineering
