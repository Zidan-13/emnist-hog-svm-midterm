# EMNIST Handwritten Character Classification using HOG + SVM

## Deskripsi Proyek
Proyek ini mengimplementasikan klasifikasi karakter tulisan tangan menggunakan dataset EMNIST Letters.  
Ekstraksi fitur dilakukan dengan Histogram of Oriented Gradients (HOG), dan klasifikasi menggunakan Support Vector Machine (SVM) kernel RBF.  
Evaluasi dilakukan dengan metode Leave-One-Out Cross Validation (LOOCV).

## Dataset
Dataset EMNIST Letters dapat diunduh dari:  
https://www.kaggle.com/datasets/crawford/emnist  

File `emnist-letters-train.csv` harus ditempatkan di folder yang sama dengan notebook.

## Persyaratan Sistem
- Python 3.x  
- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  
- scikit-image  
- tqdm  

Install library yang diperlukan dengan:  
```bash
pip install numpy pandas matplotlib seaborn scikit-learn scikit-image tqdm
