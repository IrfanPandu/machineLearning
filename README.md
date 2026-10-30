# Modul Praktikum Pembelajaran Mesin 2025/2026

Repository ini berisi implementasi dari seluruh Job Sheet (JS) mata kuliah **RTI235004 - Pembelajaran Mesin** dari Politeknik Negeri Malang.

## 📚 Daftar Job Sheet

Berikut adalah daftar Job Sheet yang tersedia:

### ✅ JS01 - Pengenalan Pembelajaran Mesin
**Status: Template Tersedia**
- `Praktikum1.ipynb` - Instalasi dan konfigurasi perangkat
- `TG1_Template.ipynb` - Template tugas praktikum (instalasi library: PyPREP, Scipy, wandb, pyECG)
- `TugasPendahuluan_JS02_Template.csv` - Template pengumpulan data mahasiswa

**Topik:**
- Konsep AI, ML, DL, GenAI
- Tipe pembelajaran mesin (Supervised, Unsupervised, Semi-supervised, Reinforcement)
- Etika dan tantangan AI

---

### ✅ JS02 - Pemahaman Data dan Pra Pengolahan Data
**Status: Template Tersedia**
- `Praktikum1_EDA.ipynb` - Exploratory Data Analysis dengan dataset Titanic
- `Praktikum2_PraPengolahanDataTerstruktur.ipynb` - Data imputation
- `Praktikum3_SeleksiFiturEncodingStandardisasi.ipynb` - Feature selection, encoding, standardization
- `Praktikum4_PengolahanCitra.ipynb` - Preprocessing data citra (resize, grayscale)
- `TugasPraktikum_WisconsinBreastCancer.ipynb` - Tugas dengan dataset Wisconsin Breast Cancer

**Topik:**
- Rekognisi dan pengenalan pola
- Jenis-jenis data
- EDA (histogram, boxplot, heatmap, scatter plot)
- Data imputation dan standardization

---

### ✅ JS03 - Ekstraksi Fitur
**Status: Template Tersedia**
- `Praktikum1_EkstraksiFiturDataTerstruktur.ipynb` - Ekstraksi fitur dari dataset Titanic (FamilySize, Title, AgeBin, CabinDeck)

**Topik:**
- Feature extraction dari data terstruktur
- Feature selection
- Data splitting

---

### ✅ JS04 - Klasterisasi
**Status: Template Tersedia**
- `Praktikum1_KMeans.ipynb` - Implementasi K-Means dengan dataset Iris, Elbow Method

**Topik:**
- K-Means Clustering
- DBSCAN Clustering
- Metode Elbow untuk menentukan k optimal

---

### ⚠️ JS05 - Klasterisasi Hierarki
**Status: Folder tersedia, konten perlu dilengkapi**

**Topik:**
- Hierarchical Clustering
- HDBSCAN
- Evaluasi clustering

---

### ⚠️ JS06 - ANN (Approximate Nearest Neighbors)
**Status: Folder tersedia, konten perlu dilengkapi**

**Topik:**
- ANNOY (Spotify)
- FAISS
- HNSW

---

### ⚠️ JS06 - Regresi
**Status: Folder tersedia, konten perlu dilengkapi**

**Topik:**
- Regresi Linear
- Regresi Non-Linear

---

### ✅ JS09 - Klasifikasi
**Status: Template Tersedia**
- `Praktikum1_kNN.ipynb` - Implementasi k-Nearest Neighbors dengan dataset Iris

**Topik:**
- k-Nearest Neighbors (kNN)
- Naive Bayes

---

### ✅ JS11 - Klasifikasi 2 (Support Vector Machine)
**Status: Template Tersedia**
- `Praktikum1_SVMDataDummyLinier.ipynb` - SVM dengan data dummy linear

**Topik:**
- Support Vector Machine (SVM)
- Kernel linear dan non-linear
- Klasifikasi citra wajah

---

### ✅ JS13 - Artificial Neural Network (ANN) dan Evaluasi Classifier
**Status: Template Tersedia**
- `Praktikum1_JSTBackpropagationManual.ipynb` - JST sederhana dengan backpropagation manual (XOR problem)

**Topik:**
- Jaringan Saraf Tiruan
- Forward pass dan Backpropagation
- Evaluasi classifier

---

### ✅ JS14 - Convolutional Neural Network
**Status: Template Tersedia**
- `Praktikum1_CatVsDog.ipynb` - Klasifikasi Cat vs Dog dengan CNN

**Topik:**
- CNN architecture
- Image classification
- Data augmentation

---

### ⚠️ JS15 - Pipeline Machine Learning & Deployment
**Status: Folder tersedia, konten perlu dilengkapi**

**Topik:**
- Training model (Day vs Night classification)
- Deployment ke Hugging Face (Docker + Flask)

---

## 📋 Cara Menggunakan

### 1. Persiapan Environment
Pastikan Anda sudah menginstall:
- Python 3.8+
- Anaconda (recommended)
- Jupyter Notebook / VS Code dengan ekstensi Jupyter
- Git (optional)

### 2. Install Dependencies
```bash
# Install library dasar
pip install numpy pandas matplotlib seaborn scikit-learn

# Install library deep learning (untuk JS13, JS14, JS15)
pip install tensorflow keras

# Install library computer vision
pip install opencv-python

# Install library khusus (untuk JS01 Tugas)
pip install pyprep scipy wandb py-ecg-detectors
```

### 3. Struktur Folder
```
machineLearning/
├── JS01/                      # Pengenalan ML
├── JS02/                      # Pemahaman Data & Preprocessing
├── JS03/                      # Ekstraksi Fitur
├── JS04/                      # Klasterisasi (K-Means, DBSCAN)
├── JS05/                      # Klasterisasi Hierarki
├── JS06_ANN/                  # Approximate Nearest Neighbors
├── JS06_Regresi/              # Regresi
├── JS09/                      # Klasifikasi (kNN, Naive Bayes)
├── JS11/                      # Klasifikasi 2 (SVM)
├── JS13/                      # ANN & Evaluasi Classifier
├── JS14/                      # CNN
├── JS15/                      # Pipeline ML & Deployment
└── README.md                  # File ini
```

### 4. Download Dataset
Beberapa praktikum memerlukan dataset eksternal:
- **Titanic Dataset** - Untuk JS02 dan JS03
- **Iris Dataset** - Untuk JS04 dan JS09
- **Wisconsin Breast Cancer** - Untuk JS02 Tugas
- **Cat vs Dog Dataset** - Untuk JS14
- Dataset lainnya tersedia di link yang disediakan dalam setiap notebook

### 5. Menjalankan Notebook
1. Buka folder Job Sheet yang ingin dikerjakan
2. Jalankan Jupyter Notebook atau VS Code
3. Buka file `.ipynb` yang sesuai
4. Jalankan cell secara berurutan dari atas ke bawah
5. Ikuti instruksi dalam setiap cell

---

## 🎯 Tugas yang Perlu Diselesaikan

### Prioritas Tinggi
- [ ] **JS01**: Isi data NIM dan Nama pada template tugas
- [ ] **JS01**: Kumpulkan 30 data teman untuk Tugas Pendahuluan JS02
- [ ] **JS02**: Lengkapi tugas Wisconsin Breast Cancer
- [ ] **JS03**: Praktikum ekstraksi fitur
- [ ] **JS04**: Praktikum K-Means clustering

### Untuk Dilengkapi
- [ ] **JS05**: Tambahkan praktikum Hierarchical Clustering
- [ ] **JS06 (ANN)**: Tambahkan praktikum ANNOY, FAISS, HNSW
- [ ] **JS06 (Regresi)**: Tambahkan praktikum Regresi
- [ ] **JS09**: Tambahkan praktikum Naive Bayes
- [ ] **JS11**: Tambahkan praktikum SVM dengan kernel non-linear
- [ ] **JS13**: Tambahkan praktikum evaluasi classifier
- [ ] **JS14**: Tambahkan praktikum klasifikasi multilabel CIFAR
- [ ] **JS15**: Tambahkan praktikum deployment

---

## 📝 Catatan Penting

1. **Nama File Tugas**: Saat mengumpulkan tugas, gunakan format `TG#_NIM_NAMA.ipynb`
   - Contoh: `TG1_2341760001_BUDI_SANTOSO.ipynb`

2. **Dataset**: Simpan dataset di folder yang sama dengan notebook atau sesuaikan path dalam kode

3. **Google Colab**: Jika menggunakan Google Colab, upload dataset terlebih dahulu menggunakan:
   ```python
   from google.colab import files
   uploaded = files.upload()
   ```

4. **Referensi**: Selalu sertakan referensi pada tugas yang memerlukan analisis dan pembahasan

---

## 🔗 Referensi

- [Modul Praktikum Online](https://polinema.gitbook.io/jti-modul-praktikum-pembelajaran-mesin-2025-2026)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Keras Documentation](https://keras.io/)

---

## 👥 Kontribusi

Repository ini dibuat untuk keperluan pembelajaran. Silakan lakukan modifikasi sesuai kebutuhan belajar Anda.

---

## 📅 Update Terakhir

**Tanggal**: 22 Oktober 2026

**Status Pengerjaan**:
- ✅ JS01: Template tersedia
- ✅ JS02: Template tersedia
- ✅ JS03: Template tersedia  
- ✅ JS04: Template tersedia
- ⚠️ JS05-JS15: Perlu dilengkapi

---

**Selamat Belajar! 🚀**
