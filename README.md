# 2108107010083_Pertemuan_11_ANN
## 1. KLASIFIKASI MENGGUNAKAN ANN
   
Dataset Prediksi Obesitas memberikan informasi mengenai atribut/variabel yang komprehensif terkait demografi individu, kebiasaan gaya hidup, dan indikator kesehatan, yang bertujuan untuk memfasilitasi prediksi prevalensi obesitas. Data ini terdiri dari 100 sample mencakup beberapa varibel/kolom seperti usia, jenis kelamin, tinggi badan, berat badan, indeks massa tubuh (BMI), tingkat aktivitas fisik, dan kategori obesitas, yang memberikan wawasan berharga mengenai faktor-faktor yang memengaruhi hasil obesitas.

Dataset ini menyediakan sumber yang sangat berharga bagi para peneliti, ilmuwan data, dan profesional kesehatan yang ingin menyelidiki interaksi yang kompleks antara faktor-faktor yang berperan dalam obesitas serta mengembangkan strategi intervensi yang efektif.

Link dataset : https://www.kaggle.com/datasets/mrsimple07/obesity-prediction/data

Berikut adalah kolom-kolom yang digunakan:
- Age : Usia individu, dinyatakan dalam tahun.
-Gender : Jenis kelamin individu, dikategorikan sebagai pria atau wanita.
- Height : Tinggi individu
- Weight : Berat badan individu
- BMI : Metrik yang dihitung dari berat dan tinggi badan individu
- PhysicalActivityLevel : Tingkat aktivitas fisik individu
- ObesityCategory : Kategorisasi individu berdasarkan BMI mereka ke dalam kategori obesitas yang berbeda

Dari hasil akurasi dari menggunakan ANN dan SVM dapat diketahui bahwa:
- accuracy ANN = 0.975
- accuracy SVM = 0.92



## 2. REGRESI MENGGUNAKAN ANN
   
Dataset ini memberikan informasi tentang percobaan periklanan antara anggaran media sosial dan penjualan(dalam ribuan $). Pada data ini terdapat 172 sample dengan 4 kolom yaitu youtube, facebook, newspaper dan sales. sales akan menjadi label pada data ini(x) dan kolom lainnya akan menjadi data(y). 

pada data ini fitur yang paling berpengaruh terhadap target adalah Youtube sehingga saya menggunakan youtube untuk membangun model dan visualisasinya.
Link dataset : https://www.kaggle.com/datasets/fayejavad/marketing-linear-multiple-regression/data

Dari hasil akurasi dari menggunakan ANN dan SVM dapat diketahui bahwa:
SVM
Root Mean Square Error (RMSE): 3.8493374993168183
Mean Absolute Error (MAE): 3.030516702924456

ANN
Mean Squared Error: 18.87835809869715
Mean Absolute Error: 3.5625496828682386

Dari hasil diatas dapat diketahui bahwa ANN memiliki akurasi yang lebih tinggi dibandingkan SVM artinya ANN menangkap pola lebih kompleks dibandingkan menggunakan SVM. Akan tetapi, perlu diperhatikan kembali bahwa dalam pemilihan model tergantung terhadapt dataset yang digunakan, pemilihan parameter, permasalahan yang terjadi, dan ukuran dataset. Sehingga untuk memilih model dalam melakukan klasifikasi tergantung kebutuhan dataset.

## HOW TO RUN:

- git clone : https://github.com/0neejj/2108107010083_Pertemuan_11_ANN
  
- python3 -m venv env

- source env/bin/activate

- python pip install -r requirements.txt

- run code ANN_Classification.ipynb or ANN_Regression.ipynb
