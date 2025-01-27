# Analisis Klasifikasi Kanker Payudara menggunakan SVM dan KNN

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis dataset kanker payudara menggunakan algoritma Machine Learning, yaitu **Support Vector Machine (SVM)** dan **K-Nearest Neighbors (KNN)**. Dataset yang digunakan adalah *Breast Cancer Wisconsin (Diagnostic)* dari pustaka `scikit-learn`. Model dievaluasi menggunakan berbagai metrik klasifikasi untuk membandingkan performanya.

## 📂 Struktur Proyek
- `BreastCancerClassification.ipynb`: Script utama untuk preprocessing, training, evaluasi, dan visualisasi model.
- `breast_cancer_dataset.csv`: Dataset yang telah disimpan dalam format CSV untuk digunakan kembali.
- `README.md`: Dokumentasi proyek ini.

## 🛠️ Teknologi yang Digunakan
- Python 3
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn
- NumPy

## 🔍 Tahapan Analisis
1. **Load Data**: Memuat dataset kanker payudara dari `sklearn.datasets`.
2. **Preprocessing Data**:
   - Mengecek missing value dan duplikasi data.
   - Normalisasi fitur menggunakan `StandardScaler`.
   - Pembagian dataset menjadi training dan testing set.
   - Visualisasi distribusi data.
3. **Pemodelan Machine Learning**:
   - **SVM**: Melakukan hyperparameter tuning menggunakan GridSearchCV.
   - **KNN**: Menentukan jumlah tetangga optimal dengan GridSearchCV.
4. **Evaluasi Model**:
   - **Confusion Matrix** untuk melihat prediksi model.
   - **Metrik Evaluasi**: Akurasi, Precision, Recall, F1-Score.
   - **ROC Curve** untuk membandingkan performa kedua model.
5. **Menyimpan Dataset** ke dalam file CSV untuk referensi di masa depan.

## 📊 Hasil Visualisasi
Proyek ini mencakup beberapa visualisasi seperti:
- Distribusi kelas dalam dataset.
- Confusion matrix untuk SVM dan KNN.
- Perbandingan skor metrik klasifikasi.
- Kurva ROC untuk membandingkan performa model.

## 📌 Kesimpulan
- **SVM** menunjukkan performa yang lebih baik dibandingkan **KNN** dalam klasifikasi dataset kanker payudara.
- ROC Curve membantu dalam memahami trade-off antara sensitivitas dan spesifisitas.
- Dataset telah disimpan dalam CSV sehingga dapat digunakan kembali untuk eksperimen selanjutnya.

💡 *Terima kasih semoga bermanfaat!*

