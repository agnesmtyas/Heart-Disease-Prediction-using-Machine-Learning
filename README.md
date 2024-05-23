# Heart Disease Prediction using Machine Learning
Project ini bertujuan untuk membangun model machine learning yang dapat memprediksi kemungkinan seserogan terkena penyakit jantung. Penyakit jantung adalah kondisi medis yang melibatkan berbagai gangguan yang mempengaruhi kinerja jantung. Beberapa jenis penyakit jantung meliputi penyakit arteri koroner, gagal jantung, aritmia, dan penyakit jantung bawaan.
Data yang dianalisis menggunakan dataset penyakit jantung "Heart Disease Dataset" yang bersumber dari Kaggle. Data ini diambil sejak tahun 1988 yang terdiri dari 4 wilayah, yaitu Cleveland, Hungary, Switzerland, dan Long Beach V.

## Data Preparation
Bertujuan untuk membersihkan data yang terdiri dari melihat missing value, duplicate value, outliers, balancing data, dan melakukan feature encoding

## Exploratory Data Analysis (EDA)
Bertujuan untuk melihat hubungan antar variabel dan melihat informasi yang terkandung di dalam data

## Feature Engineering
Bertujuan untuk memberikan label setiap fitur sesuai dengan klasifikasi kondisi kesehatannya

## Machine Learning Model
Pertama, akan dilakukan seleksi fitur untuk menentukan fitur yang akan dilakukan modeling. Kemudian, data dibagi menjadi 75% data training dan 25% data testing. Setelah itu, jumlah data dibuat seimbang agar meningkatkan performa model, terutama dalam memprediksi kelas minoritas. 

Pemodelan menggunakan model Random Forest dan pemodelan otomatis menggunakan pycaret.

## Evaluation
Evaluasi menggunakan confustion matrix, cross validation, dan learning curve.
