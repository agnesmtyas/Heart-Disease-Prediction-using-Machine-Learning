# Heart Disease Prediction using Machine Learning
Project ini bertujuan untuk membangun model machine learning yang dapat memprediksi kemungkinan seserogan terkena penyakit jantung. Penyakit jantung adalah kondisi medis yang melibatkan berbagai gangguan yang mempengaruhi kinerja jantung. Beberapa jenis penyakit jantung meliputi penyakit arteri koroner, gagal jantung, aritmia, dan penyakit jantung bawaan.
Data yang dianalisis menggunakan dataset penyakit jantung "Heart Disease Dataset" yang bersumber dari Kaggle. Data ini diambil sejak tahun 1988 yang terdiri dari 4 wilayah, yaitu Cleveland, Hungary, Switzerland, dan Long Beach V.

## Dataset 
* age = umur pasien
* sex = jenis kelamin pasien
* cp (chest pain type) = jenis nyeri dada (4 values)
* trestbps (resting blood pressure) = tekanan darah ketika beristirahat
* chol (serum cholestoral) = kadar kolesterol serum in mg/dl
* fbs (fasing blood sugar) = kadar gula darah dalam keadaan puasa > 120 mm/Hg
* restecg (resting electrocardiographic result) = hasil elektrokardiogram saat istirahat (values 0,1,2)
* thalach (maximum heart rate achieced) = denyut antung maksimum selama tes latihan
* exang (exercise induced angina) = mengindikasikan apakah angina (nyeri dada) dipicu oleh latihan fisik
* oldpeak (ST depression induced by exercise to rest) = mengukur depresi segment ST (perubahan dalam garis dasar elektrokardiogram) yang disebabkan oleh latihan fisik
* slope = kemiringan segment ST selama tes latihan
* ca (number of major vessels colored by flourosopy) = mengukur jumlah pembuluh darah utama yang terlihat dengan jelas melalui pewarnaan fluroskopi (values 0,1,2,3)
* thal = hasil tes thalium (radiosotop) untuk mendeteksi aliran darah ke jantung (1 = fixed defect; 2 = reversable defect)
* target = diagnosa penyakit jantung (0 = tidak terindikasi penyakit jantung dan 1 = terindikasi penyakit jantung)

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
