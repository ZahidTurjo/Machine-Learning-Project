🩺 Breast Cancer Detection Web App

This is a simple machine learning-powered web app that predicts whether a tumor is **benign** or **malignant** based on breast cancer diagnostic data. It uses a trained on Logistic Regression and is deployed with **Flask**.

---
```
## 📁 Project Structure

Breast-Cancer-Detection/
├── app.py # Flask backend script
├── model.pkl # Trained ML model
├── Breast_Cancer_Detection.ipynb # Model training notebook
├── templates/
│ └── index.html # HTML form for input
└── README.md # Project documentation
```

## 🧠 About the Model

- Dataset: dataset from kaggle (https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset/data)
- Model: Logistic Regression
- Target: 0 = Malignant, 1 = Benign

---

## 💻 How to Run This Project Locally

### 1. Clone the Repository

```
git clone https://github.com/yourusername/Breast-Cancer-Detection.git
cd Breast-Cancer-Detection
```
2. Install Required Packages
```
Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Then install dependencies:
pip install flask scikit-learn pandas numpy
```

4. Train the Model (if model.pkl is not included)
``` Run the notebook to train and save the model:
jupyter notebook Breast_Cancer_Detection.ipynb
 ```

5. Start the Flask App
``` python app.py ```
