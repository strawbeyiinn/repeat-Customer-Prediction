👤 Author : Ferrincia Avril & Beyond Revata Hwang

📊 Repeat Customer Prediction
  Proyek ini bertujuan untuk memprediksi apakah seorang customer akan melakukan pembelian ulang (repeat customer) menggunakan machine learning.

🚀 Overview
  Dalam proyek ini dilakukan proses end-to-end data science, mulai dari:
  Data preprocessing
  Exploratory Data Analysis (EDA)
  Feature engineering
  Handling imbalanced data
  Model training & evaluation
  Model yang digunakan berfokus pada klasifikasi untuk memprediksi kemungkinan customer melakukan pembelian kembali.

📁 Dataset
  Dataset berisi informasi terkait customer dan transaksi, seperti:
  Informasi demografis
  Riwayat pembelian
  Perilaku transaksi
  Target:
  repeat_customer (0 = tidak repeat, 1 = repeat)

⚙️ Tech Stack
  Python
  Pandas & NumPy
  Matplotlib & Seaborn
  Scikit-learn
  Imbalanced-learn (SMOTE)
  Jupyter Notebook
  
🔄 Workflow
  1. Data Preprocessing
    Handling missing values
    Encoding fitur kategorikal
  Normalisasi/standarisasi data
  2. Exploratory Data Analysis (EDA)
    Analisis distribusi data
    Korelasi antar fitur
  Visualisasi pola customer
  3. Handling Imbalanced Data
    Menggunakan SMOTE untuk mengatasi ketidakseimbangan kelas
  4. Model Training
    Beberapa model yang digunakan:
    Random Forest Classifier
    (opsional jika ada) model lain untuk perbandingan
  5. Evaluation
    Evaluasi model menggunakan:
    Accuracy
    Precision
    Recall
    F1-score
    Precision-Recall Curve

📈 Hasil
  Model mampu mengidentifikasi customer yang berpotensi melakukan repeat order dengan performa yang cukup baik berdasarkan metrik evaluasi.

📈 Key Business Insights
  1. 🎯 Customer Behavior Drives Retention
  Customer dengan frekuensi transaksi tinggi dan recent activity memiliki kemungkinan lebih besar untuk menjadi repeat customer.
    👉 Strategi:
    Fokus pada customer yang baru saja melakukan pembelian dengan:
    Email follow-up
    Personalized recommendations
  2. 💰 High-Value Customers ≠ Always Loyal
  Tidak semua customer dengan transaksi besar akan kembali.
    👉 Insight:
    Nilai transaksi tinggi tidak selalu menjamin repeat
    Perlu kombinasi dengan engagement & frequency
    👉 Strategi:
    Jangan hanya target “big spender”
    Bangun loyalty program berbasis perilaku, bukan hanya nilai transaksi
  3. ⚠️ Silent Churn Risk
    Customer yang tidak melakukan transaksi dalam periode tertentu memiliki probabilitas rendah untuk kembali.
    👉 Strategi:
    Implementasi early warning system
    Kirim diskon terbatas, reminder campaign, retargeting ads
  4. ⚖️ Importance of Imbalanced Learning
  Tanpa penanganan imbalance, model cenderung bias ke non-repeat customer.
    👉 Insight teknis → bisnis:
    Jika tidak ditangani, perusahaan bisa:
      Kehilangan peluang retensi
      Salah target campaign
  5. 📊 Model as Decision Support Tool
    Model dapat digunakan untuk:
      Segmentasi customer
      Prioritas marketing campaign
      Alokasi budget yang lebih efisien

💡 Business Impact
  Dengan implementasi model ini, perusahaan dapat:
    Meningkatkan customer retention rate
    Mengurangi marketing cost (lebih targeted)
    Meningkatkan Customer Lifetime Value (CLV)
