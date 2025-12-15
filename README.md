# Automated Quality Assessment of Fresh Produce Using Deep Learning

## 📌 Overview
This repository presents an automated quality assessment system for fresh fruits and vegetables using deep learning and computer vision techniques.  
The objective of this research is to accurately classify produce items as **Healthy** or **Rotten**, reducing subjectivity and manual inspection in agricultural quality control.

The system was developed as part of a **final-year BSc (Hons) Computer Science research project** and evaluates multiple deep learning architectures using a large-scale image dataset.

---

## 🧠 Models Implemented
The following models were implemented, trained, and evaluated independently:

- **VGG16**
- **MobileNetV2**
- **EfficientNetV2-S**
- **MobileNetV2 + Vision Transformer (ViT) Hybrid**

Each model is provided as a separate Kaggle notebook to ensure clarity, reproducibility, and fair comparison.

---

## 📂 Dataset
- **Dataset Name:** Fruit and Vegetable Disease – Healthy vs Rotten  
- **Source:** Kaggle  
- **Total Images:** ~29,000  
- **Classes:** 28 (14 fruits and vegetables × Healthy / Rotten)

📎 Dataset link:  
https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification

> **Note:** The dataset is not included in this repository due to licensing restrictions.  
> Please download it directly from Kaggle.

---

## 🏗️ Project Structure
fresh-produce-quality-assessment/
│
├── notebooks/
│ ├── VGG16.ipynb
│ ├── MobileNetV2.ipynb
│ ├── EfficientNetV2_S.ipynb
│ └── MobileNetV2_ViT.ipynb
│
├── results/
│
├── figures/
│
├── README.md
├── requirements.txt
└── .gitignore


---

## ⚙️ Implementation Details
- Framework: **TensorFlow / Keras**
- Programming Language: **Python**
- Environment: **Kaggle Notebook (GPU)**
- Data Pipeline: `tf.data`
- Optimization: Adam optimizer
- Evaluation Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

All models were trained using standardized preprocessing and evaluation protocols to ensure fair comparison.

---

## 🚀 How to Run the Code
1. Open **Kaggle Notebook**
2. Upload the desired notebook from the `notebooks/` folder
3. Attach the dataset from Kaggle
4. Enable GPU (Settings → Accelerator → GPU)
5. Run all cells

---

## 📊 Results Summary
Among the evaluated models, **EfficientNetV2-S** achieved the highest performance with strong generalization and training stability.  
Detailed accuracy plots and confusion matrices will be added in the `results/` and `figures/` folders.

---

## 📌 Future Work
- Expand the dataset with real-world images
- Apply advanced data augmentation strategies
- Explore lightweight transformer architectures
- Deploy the trained model as a web or mobile application

---

## 👩‍💻 Author
**Madushi Sulakshana**  
BSc (Hons) Computer Science  
Sri Lanka

---

## 📚 Citation
If you use this work for academic or research purposes, please cite it appropriately.  
A citation file will be provided in future updates.
