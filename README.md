# Tugas Besar Pemrograman Data Analitik - Prediksi Keselamatan Penumpang Titanic

Repositori ini berisi materi proyek akhir untuk mata kuliah Pemrograman Data Analitik (IF5100-PDA) yang berfokus pada analisis data dan pemodelan prediktif pada dataset Titanic.

## Ringkasan Proyek

Tujuan dari proyek ini adalah untuk menganalisis faktor-faktor yang mempengaruhi kelangsungan hidup penumpang di kapal Titanic dan membangun model klasifikasi untuk memprediksi probabilitas keselamatan penumpang.

Proses yang dilakukan meliputi:
* Persiapan data (penanganan *missing values*, *outlier*).
* *Feature Engineering* (pembuatan fitur baru seperti `FamilySize` dan `IsAlone`).
* Analisis Data Eksploratif (EDA).
* Perbandingan beberapa model *Machine Learning* (termasuk *Logistic Regression*, *Random Forest*, dan *Gradient Boosting*).
* Model terbaik yang dicapai adalah **Gradient Boosting** dengan akurasi **0.81**.

## Struktur Repositori

| File | Deskripsi |
| :--- | :--- |
| `Tubes PDA - Titanic.ipynb` | Notebook Jupyter yang berisi seluruh langkah analisis data, visualisasi, persiapan data, dan implementasi model *Machine Learning*. |
| `Dokumen Tugas Besar PDA.pdf` | Dokumen laporan resmi Tugas Besar yang merinci metodologi, hasil, dan kesimpulan proyek ini. |

## Persyaratan (Dependency)

Untuk menjalankan notebook, Anda memerlukan pustaka Python standar untuk ilmu data seperti `pandas`, `seaborn`, `matplotlib`, `plotly`, dan modul dari `sklearn` (seperti `LogisticRegression`, `GradientBoostingClassifier`, `StandardScaler`, dll.).
