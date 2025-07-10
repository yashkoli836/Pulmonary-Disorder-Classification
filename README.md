# 🧠 Patient Diagnosis with Deep Learning & Ensemble Models

This project implements deep learning and ensemble learning techniques to perform predictive modeling for patient diagnosis. It leverages demographic data, patient records, and labeled datasets to train, validate, and test various machine learning models, including CNN-GRU with attention mechanisms.

---

## 📁 Project Structure

```
├── .gitignore                   # Git ignore rules
├── DL_Models.ipynb              # Notebook with baseline deep learning models
├── Deep_Learning_new.ipynb      # Contains CNN-GRU with attention model
├── Ensemble_Learners.ipynb      # Notebook with ensemble machine learning models
│
├── X_train.csv                  # Training feature data
├── y_train.csv                  # Training labels
├── X_test.csv                   # Testing feature data
├── y_test.csv                   # Testing labels
│
├── demographic_info.txt         # Additional demographic data for patients
├── patient_diagnosis.csv        # Master dataset with patient diagnosis records
└── README.md                    # Project documentation (this file)
```

---

## ✅ Features

- 🧠 **Deep Learning Models**: Implemented CNN, GRU, and attention-based hybrid models.
- 🔀 **Ensemble Learning**: Includes techniques like Random Forests, Gradient Boosting, etc.
- 📊 **Structured Data**: Utilizes demographic and diagnosis data in `.csv` and `.txt` formats.
- 📈 **Train/Test Pipeline**: Separate datasets for training and evaluation.
- 🧪 **Evaluation Metrics**: Model accuracy, precision, recall, and F1-score.

---

## 🛠️ Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.8+
- Jupyter Notebook
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`
- `tensorflow` or `pytorch` (depending on the model)

### Run Instructions

1. Clone the repository.
2. Open the desired `.ipynb` file in Jupyter.
3. Run all cells to train and evaluate models.

---

## 📌 Notes

- `Deep_Learning_new.ipynb` contains the most advanced model: CNN-GRU with attention.
- You can enrich the dataset using `demographic_info.txt` for additional features.
- `patient_diagnosis.csv` serves as the central data file from which other subsets may be derived.

---

## 📄 License

This project is intended for academic and research purposes only. Please cite or credit appropriately if used.
