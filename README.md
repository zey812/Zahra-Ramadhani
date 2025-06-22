# 🍔 Fast Food Calorie Classification & Summarization

## 📌 Project Overview
Proyek ini bertujuan untuk mengklasifikasikan dan menganalisis kandungan kalori dari lebih dari 500 menu makanan cepat saji dari berbagai restoran ternama di Amerika Serikat. Selain itu, dilakukan juga proses summarization (peringkasan informasi) untuk menyampaikan insight secara ringkas dan informatif.

## 📁 Dataset
- Sumber: [Fast Food Nutrition Dataset - Kaggle](https://www.kaggle.com/datasets/brandenciranni/fast-food-nutrition)
- Jumlah entri: 500+ menu makanan
- Fitur: kalori, lemak total, lemak jenuh, gula, protein, karbohidrat, dan lainnya

## 🎯 Tujuan Analisis
- Mengklasifikasikan makanan berdasarkan tingkat kalorinya (low, medium, high)
- Mengidentifikasi restoran dengan rata-rata kalori tertinggi
- Menyusun ringkasan per restoran dan per menu berdasarkan kandungan nutrisi

## 🧠 Tools & Model
- **Google Colab** (Python)
- **Scikit-learn**: RandomForestClassifier, LogisticRegression
- **NLTK / Transformers** (untuk summarization teks)
- **Matplotlib & Seaborn** (visualisasi data)

  ## 🤖 AI Support Explanation
- **Classification Model** digunakan untuk mengelompokkan menu berdasarkan restoran dari nilai nutrisi atau kandungan.
- **Summarization Model** digunakan untuk meringkas hasil analisis deskriptif secara otomatis.

## 🔍 Temuan Utama
- **McDonald's** memiliki **rata-rata kalori tertinggi** per menu (> 640 kalori/item)
- **Subway** memiliki **jumlah menu tinggi kalori terbanyak** (≥ 25 item)
- **Sonic** dan **Burger King** juga berkontribusi besar pada menu kalori tinggi karena porsi/topping yang besar.
- Menu seperti *Double Bacon Smokehouse Burger* (1130 kalori) menjadi penyumbang dominan

## 🧾 Ringkasan Hasil (Summarization Output)
> Analisis terhadap lebih dari 500 menu makanan cepat saji menunjukkan bahwa McDonald's memiliki rata-rata kalori per menu tertinggi, sementara Subway memiliki jumlah menu tinggi kalori terbanyak. Restoran seperti Sonic dan Burger King juga memiliki kalori tinggi karena porsinya yang besar dan toppingnya beragam.

## 🔗 Link Notebook (Colab)
- 📄 [Fast Food_Capstone_Project.ipynb](https://github.com/zey812/Zahra-Ramadhani/blob/main/Fast%20Food_Capstone%20Project.ipynb)

## 👩‍💻 Author
Zahra Ramadhani  
Capstone Project - Data Classification & Summarization  
Universitas Siliwangi | Sistem Informasi | Semester 2

