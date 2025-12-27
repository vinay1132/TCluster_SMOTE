# 📊 Handling Class Imbalance in Time-Series Data using Temporal Clustering and SMOTE

This repository presents a research project focused on addressing the **class imbalance problem in time-series datasets** using a novel approach that combines **temporal clustering** with **SMOTE-based oversampling techniques**. The work was conducted as part of an academic project at the **Indian Institute of Technology Roorkee (IIT Roorkee)** under the supervision of **Prof. Pradumn K. Pandey**.

---

## 🧠 Problem Statement

In many real-world applications like fraud detection, medical diagnosis, and anomaly detection, datasets are highly imbalanced—where one class significantly outnumbers the other. Traditional oversampling techniques like **SMOTE** often fail to account for the **temporal dynamics** of data, leading to overfitting or poor generalization.

---

## 🚀 Proposed Solution

We propose a **Temporal Clustering-based Oversampling Framework (TCluster)** that:

- Segments time-series data into temporal intervals.
- Applies **K-Means clustering** within each interval.
- Performs **SMOTE-based oversampling** on filtered clusters to generate synthetic minority samples.
- Merges synthetic samples across time windows to maintain temporal consistency.

This approach ensures that the model adapts to evolving data distributions and mitigates the risk of overfitting caused by naive oversampling.

---

## 🧪 Experimental Setup

- **Datasets**: Haberman, PIMA, Credit Card Fraud, and Tackling Imbalance datasets.
- **Classifiers**: MLP, Logistic Regression, KNN, SVM, CNN.
- **Baseline Oversamplers**: SMOTE, Borderline-SMOTE, ADASYN, Random-SMOTE, KMeans-SMOTE, etc.

---

## 📈 Results

The proposed **TCluster** method outperformed traditional oversamplers across multiple metrics:

- Improved **Recall**, **F1-score**, and **G-mean**.
- Demonstrated robustness on high-imbalance datasets (e.g., Credit Card Fraud with IR > 500).
- Maintained temporal relevance in synthetic sample generation.

---

## 📚 Key Contributions

- Introduced a **time-aware oversampling strategy** for imbalanced time-series data.
- Demonstrated effectiveness across diverse datasets and classifiers.
- Highlighted limitations of existing SMOTE variants in temporal settings.

---

## 📄 License

This project is for academic and research purposes. For reuse or collaboration, please contact the author.

---

## 👤 Author

**Vinay Gupta**  
M.Tech, Department of Computer Science and Engineering  
Indian Institute of Technology Roorkee  
Enrollment No: 21535036  
