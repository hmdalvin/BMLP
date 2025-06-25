# 🔍 BMLP Final Project – Ahmad Alfianto

## 🇮🇩 Bahasa Indonesia

### 📝 Deskripsi Proyek
Repositori ini adalah bagian dari tugas akhir program Bangkit Machine Learning Path (BMLP). Proyek ini mencakup dua komponen utama:
- **Clustering** menggunakan PCA dan KMeans
- **Klasifikasi** menggunakan Decision Tree dan hyperparameter tuning

### 📁 Struktur Berkas

| Nama Berkas | Deskripsi |
|-------------|-----------|
| `PCA_model_clustering.h5` | Model clustering hasil reduksi dimensi dengan PCA |
| `[Clustering]_Submission_Akhir_BMLP_Ahmad_Alfianto.ipynb` | Notebook akhir untuk proses clustering |
| `[Klasifikasi]_Submission_Akhir_BMLP_Ahmad_Alfianto.ipynb` | Notebook akhir untuk proses klasifikasi |
| `[clustering]_submission_akhir_bmlp_ahmad_alfianto.py` | Script Python untuk clustering |
| `[klasifikasi]_submission_akhir_bmlp_ahmad_alfianto.py` | Script Python untuk klasifikasi |
| `data_clustering.csv` | Dataset awal hasil preprocessing |
| `data_clustering_inverse.csv` | Dataset setelah inverse transform |
| `decision_tree_model.h5` | Model klasifikasi Decision Tree akhir |
| `explore_DecisionTree_classification.h5` | Model klasifikasi awal sebelum tuning |
| `model_clustering.h5` | Model hasil KMeans tanpa PCA |
| `tuning_classification.h5` | Model klasifikasi setelah tuning |

### ▶️ Cara Menjalankan
1. Jalankan file `.ipynb` sesuai tahap (clustering atau klasifikasi)
2. Gunakan file `.csv` sebagai input data
3. Muat model `.h5` dengan `keras.models.load_model()`

### 📦 Ketergantungan
- Python 3.10+
- pandas, numpy, scikit-learn, matplotlib
- tensorflow / keras

---

## 🇬🇧 English Version

### 📝 Project Description
This repository is part of the final project submission for the Bangkit Machine Learning Path (BMLP) program. It includes two main components:
- **Clustering** using PCA and KMeans
- **Classification** using Decision Tree with hyperparameter tuning

### 📁 File Structure

| File Name | Description |
|-----------|-------------|
| `PCA_model_clustering.h5` | Clustering model with PCA dimensionality reduction |
| `[Clustering]_Submission_Akhir_BMLP_Ahmad_Alfianto.ipynb` | Final clustering notebook |
| `[Klasifikasi]_Submission_Akhir_BMLP_Ahmad_Alfianto.ipynb` | Final classification notebook |
| `[clustering]_submission_akhir_bmlp_ahmad_alfianto.py` | Python script for clustering |
| `[klasifikasi]_submission_akhir_bmlp_ahmad_alfianto.py` | Python script for classification |
| `data_clustering.csv` | Preprocessed input dataset |
| `data_clustering_inverse.csv` | Dataset after inverse transform |
| `decision_tree_model.h5` | Final Decision Tree model |
| `explore_DecisionTree_classification.h5` | Initial model before tuning |
| `model_clustering.h5` | KMeans model without PCA |
| `tuning_classification.h5` | Tuned classification model |

### ▶️ How to Run
1. Run the `.ipynb` notebooks based on task (clustering or classification)
2. Use `.csv` files as input
3. Load `.h5` models using `keras.models.load_model()`

### 📦 Requirements
- Python 3.10+
- pandas, numpy, scikit-learn, matplotlib
- tensorflow / keras
