# Capstone-Project-Data-Classification-Summarization
Text Classification and Insight Extraction from Mental Health  Dataset using Traditional Machine Learning with Oversampling Technique

📘 Project Overview
Studi Kasus: Klasifikasi opini publik terkait isu kesehatan mental.
Tujuan: Mengelompokkan teks ke dalam kategori sentimen (positive, negative, neutral) dan mengevaluasi efektivitas model klasifikasi.
Permasalahan: Ketidakseimbangan jumlah data antar kelas menyebabkan bias pada model.
Solusi: Menerapkan teknik oversampling SMOTE untuk menyeimbangkan data sebelum pelatihan model.
Metode: Naïve Bayes dan SVM, diuji dalam 4 skenario (dengan/ tanpa SMOTE).

🔗 Raw Dataset Link
Sumber data publik dari Kaggle:
https://www.kaggle.com/code/annastasy/mental-health-sentiment-analysis-nlp-ml/input
Jumlah data: Ribuan tweet bertopik mental health

💡 Insight & Findings
SVM + SMOTE menghasilkan performa terbaik (F1-Score 84.46%, Akurasi 84.75%).
SMOTE efektif meningkatkan performa seluruh model, terutama dalam kondisi distribusi label yang tidak seimbang.
Naïve Bayes tanpa SMOTE menunjukkan performa terendah → tidak cocok untuk data tidak seimbang.

🤖 AI Support Explanation
Model AI Tradisional: Naïve Bayes dan Support Vector Machine (SVM).
Teknik yang Digunakan:
- TF-IDF Vectorization: Untuk mengubah teks menjadi fitur numerik.
- SMOTE: Teknik AI berbasis oversampling untuk mengatasi data imbalance.
- Tools: Google Colab, Python, scikit-learn, imbalanced-learn.

Peran AI:
✔ Memproses dan membersihkan data teks secara otomatis
✔ Menyeimbangkan data kelas minoritas
✔ Melatih dan mengevaluasi model klasifikasi
✔ Menyediakan automatic summarization dari hasil eksperimen

