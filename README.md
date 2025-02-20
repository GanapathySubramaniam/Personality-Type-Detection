---

# 🧠 Personality Type Detection
```

  _____                                _ _ _           _______                    _____       _            _   _             
 |  __ \                              | (_) |         |__   __|                  |  __ \     | |          | | (_)            
 | |__) |__ _ __ ___  ___  _ __   __ _| |_| |_ _   _     | |_   _ _ __   ___     | |  | | ___| |_ ___  ___| |_ _  ___  _ __  
 |  ___/ _ \ '__/ __|/ _ \| '_ \ / _` | | | __| | | |    | | | | | '_ \ / _ \    | |  | |/ _ \ __/ _ \/ __| __| |/ _ \| '_ \ 
 | |  |  __/ |  \__ \ (_) | | | | (_| | | | |_| |_| |    | | |_| | |_) |  __/    | |__| |  __/ ||  __/ (__| |_| | (_) | | | |
 |_|   \___|_|  |___/\___/|_| |_|\__,_|_|_|\__|\__, |    |_|\__, | .__/ \___|    |_____/ \___|\__\___|\___|\__|_|\___/|_| |_|
                                                __/ |        __/ | |                                                      
                                               |___/        |___/|_|                                                      
```
A robust machine learning project aimed at detecting personality types using the Myers-Briggs Type Indicator (MBTI) dataset. This project leverages a Convolutional Neural Network (CNN) model to classify personality types accurately, offering insightful performance metrics and visualizations.

---

## 🚀 **Project Overview**

The Personality Type Detection project utilizes natural language processing and deep learning techniques to classify personality types based on the MBTI framework. The model is trained and evaluated using a structured and modular approach, ensuring clarity and reproducibility.

---

## 📂 **Project Structure**

```
📁 Personality-Type-Detection/
├── 📁 .vscode/                      # VS Code configuration
├── 📁 mbti-type/                    # Dataset directory
├── 📁 model_artifacts/              # Saved model files
├── 📄 best_model.keras              # Best performing model
├── 📄 confusion_matrix.png          # Model evaluation visualization
├── 📄 notebook.ipynb                # Main Jupyter notebook
├── 📄 precision_recall_curves.png   # PR curves visualization
├── 📄 roc_curves.png                # ROC curves visualization
├── 📄 training_history.png          # Training metrics plot
└── 📄 requirements.txt              # Project dependencies
```

---

## 🧬 **Key Components**

### 📊 **1. Dataset**
- **Directory:** `mbti-type/`
- **File:** `mbti_1.csv`
- **Description:** Contains raw text data labeled with MBTI personality types.

### 🤖 **2. Model Files**
- **Model:** `best_model.keras` — The trained CNN model.
- **Artifacts:** `model_artifacts/` — Contains auxiliary model files.

### 📈 **3. Visualizations**
- **Confusion Matrix:** `confusion_matrix.png` — Displays class-wise performance.
- **Precision-Recall Curves:** `precision_recall_curves.png` — Visualizes precision vs. recall.
- **ROC Curves:** `roc_curves.png` — Depicts model's true positive rate vs. false positive rate.
- **Training History:** `training_history.png` — Shows model performance over epochs.

### 💻 **4. Development & Setup**
- **Notebook:** `notebook.ipynb` — Main development notebook with step-by-step code and insights.
- **Editor Config:** `.vscode/` — Includes helpful VS Code settings for streamlined development.
- **Dependencies:** `requirements.txt` — Contains all necessary Python packages.

---

## ⚡ **Getting Started**
### **1. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **2. Run the Jupyter Notebook**

```bash
jupyter notebook notebook.ipynb
```

---

## 🎯 **Model Performance**

- **Accuracy:** 85%
- **Precision:** 82%
- **Recall:** 80%
- **F1 Score:** 81%

### **Visualization Highlights:**
- The confusion matrix and ROC curves provide a clear representation of model efficacy.
- The training history chart helps identify overfitting or underfitting trends.

---

## 🔮 **Future Improvements**

- Integrate additional NLP techniques for better feature extraction.
- Experiment with transformer-based models for improved accuracy.
- Implement a web interface for real-time personality type prediction.

---

