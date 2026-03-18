# 📊 Analisis Sentimen Ulasan Shopee (Naive Bayes Classifier)

## 📝 Deskripsi Proyek
Proyek ini bertujuan untuk melakukan **analisis sentimen terhadap ulasan aplikasi Shopee di Google Play Store** menggunakan metode **Naive Bayes Classifier (NBC)**.  

Analisis ini mengklasifikasikan ulasan pengguna ke dalam tiga kategori:
- ✅ Positif  
- ⚖️ Netral  
- ❌ Negatif  

---

## 🎯 Tujuan
- Mengumpulkan data ulasan aplikasi Shopee dari Google Play Store  
- Melakukan preprocessing teks ulasan  
- Memberikan label sentimen berdasarkan rating  
- Membangun model klasifikasi menggunakan **Naive Bayes (MultinomialNB)**  
- Mengevaluasi performa model  

---

## 🧠 Metodologi

### 1. Pengumpulan Data
Data diambil menggunakan library:
google-play-scraper

Dengan parameter:
- App ID: `com.shopee.id`
- Bahasa: Indonesia
- Jumlah data: ±2000 ulasan

---

### 2. Data Labeling
Label sentimen ditentukan berdasarkan rating:
- ⭐ 4–5 → **Positif**
- ⭐ 3 → **Netral**
- ⭐ 1–2 → **Negatif**

---

### 3. Preprocessing Teks
Tahapan preprocessing meliputi:
- Case Folding  
- Cleansing (hapus simbol/angka)  
- Normalisasi kata  
- Stopword Removal  
- Stemming  
- Tokenizing  

---

### 4. Split Data
Dataset dibagi menjadi:
- Data Training  
- Data Testing  

---

### 5. Feature Extraction
Menggunakan metode:
TF-IDF (Term Frequency - Inverse Document Frequency)

---

### 6. Modeling
Model yang digunakan:
Multinomial Naive Bayes

---

### 7. Evaluasi Model
Menggunakan metrik:
- Confusion Matrix  
- Accuracy  
- Precision  
- Recall  
- F1-Score  

---

## 📦 Library yang Digunakan
- pandas  
- numpy  
- google-play-scraper  
- scikit-learn  
- nltk / sastrawi  

---

## 📁 Struktur Proyek
├── Analisis_Sentimen_Shopee.ipynb  
├── README.md  
└── dataset (opsional)  

---

## 📊 Output yang Dihasilkan
- Dataset ulasan Shopee  
- Model klasifikasi sentimen  
- Evaluasi performa model  
- Visualisasi hasil analisis  

---

## 🚀 Cara Menjalankan
1. Install dependencies:
pip install google-play-scraper pandas numpy scikit-learn  

2. Jalankan notebook:
jupyter notebook  

3. Buka file analisis sentimen.ipynb

---

## 📌 Kesimpulan
Metode **Naive Bayes Classifier** mampu digunakan untuk:
- Mengklasifikasikan sentimen ulasan pengguna  
- Memberikan insight terhadap kepuasan pengguna aplikasi Shopee  

---

## 👨‍💻 Author
Bayu Prasetyo  
---
