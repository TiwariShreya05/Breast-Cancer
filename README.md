# 🩺 Breast Cancer Prediction

A deep learning project that classifies tumors as malignant or benign using a Neural Network built with TensorFlow and Keras, trained on the scikit-learn Breast Cancer dataset.

---   

## 📌 Project Overview  

This project builds a binary classification model using 30 tumor features to predict whether a tumor is:   
  
- **Malignant** (cancerous) → Label `0`  
- **Benign** (non-cancerous) → Label `1`
        
The model is trained and evaluated on the Breast Cancer Wisconsin dataset from scikit-learn.
   
---
🖼️ Project Visualizations

📊 Training, Accuracy & Loss 
<p align="center"> <img src="https://github.com/user-attachments/assets/d0aa1023-7c0e-4f1c-a950-1f9eff59e293" width="80%"/> </p>

<p align="center"> <img src="https://github.com/user-attachments/assets/aa571ed8-693b-4e6b-8cff-30dfbb734004" width="80%"/> </p>

<p align="center"> <img src="https://github.com/user-attachments/assets/42795669-8fb8-4388-b07c-10072c08c6f4" width="80%"/> </p>

🧪 Predictions & Output Screens

<p align="center"> <img src="https://github.com/user-attachments/assets/0870151a-7947-45e5-a783-aca7a44aa8d3" width="70%"/> </p>

<p align="center"> <img src="https://github.com/user-attachments/assets/018dcf0f-0434-48b4-9c5b-aacc019c477c" width="70%"/> </p>

<p align="center"> <img src="https://github.com/user-attachments/assets/0844bcec-8b06-4c7a-a406-26bc5ff342de" width="70%"/> </p>

---
## 🧠 Model Details

| Property   | Value                        |
|------------|------------------------------|
| Algorithm  | Neural Network (Keras)       |
| Features   | 30 tumor measurements        |
| Target     | `0` = Malignant, `1` = Benign |
| Activation | ReLU (hidden), Sigmoid (output) |
| Evaluation | Accuracy, Precision, Recall, F1 |

### Architecture
```
Input (30 features) → Dense Layer (ReLU) → Output Layer (Sigmoid)
```

### Results

| Metric    | Score |
|-----------|-------|
| Accuracy  | 97.4% |
| Precision | ~97%  |
| Recall    | ~97%  |
| F1-Score  | ~97%  |

---

## 🚀 Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/TiwariShreya05/breast-cancer-prediction.git
cd breast-cancer-prediction
```

**2. Install dependencies**
```bash
pip install tensorflow scikit-learn matplotlib numpy
```

**3. Run the notebook**

Open the `.ipynb` file in Jupyter or Google Colab and run all cells step-by-step.

---

## 🛠 Tech Stack

- **Python** — data processing and model training
- **TensorFlow / Keras** — neural network
- **scikit-learn** — dataset and evaluation metrics
- **NumPy** — data manipulation
- **Matplotlib** — training visualizations

---

## 📬 Contact

- 💼 LinkedIn: [linkedin.com/in/shreya-tiwari-520b692b3](https://www.linkedin.com/in/shreya-tiwari-520b692b3/)
- 📧 Email: shreyatiwari0801@gmail.com
- 🐙 GitHub: [github.com/TiwariShreya05](https://github.com/TiwariShreya05)
