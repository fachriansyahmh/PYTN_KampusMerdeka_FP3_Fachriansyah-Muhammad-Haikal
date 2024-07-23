# Prediksi Risiko Gagal Jantung dengan Ensemble Model

buka link berikut untuk detail projectnya : <a href="https://github.com/fachriansyahmh/Prediksi_Risiko_Gagal_Jantung_dengan_Ensemble_Model/blob/main/Prediksi_Risiko_Gagal_Jantung_dengan_Ensemble_Model.ipynb" target="_blank">Project</a>

## Latar Belakang

Penyakit gagal jantung adalah kondisi yang serius dan mempengaruhi kualitas hidup serta tingkat kematian pasien. Prediksi yang akurat tentang risiko gagal jantung dapat membantu tenaga medis dalam mengidentifikasi pasien yang rentan dan memungkinkan pengambilan tindakan pencegahan yang tepat.

Dalam hal ini, penggunaan ensemble model menjadi relevan karena dapat memanfaatkan kekuatan berbagai algoritma pembelajaran mesin yang berbeda. Ensemble model menggabungkan hasil prediksi dari beberapa model yang berbeda, seperti KNN, random forest, naive bayes, dan lainnya. Dengan memadukan prediksi dari beberapa model, ensemble model dapat mengurangi bias dan varians yang mungkin ada dalam model tunggal, dan pada akhirnya menghasilkan prediksi yang lebih akurat.

Ensemble model memiliki beberapa variasi, seperti voting ensemble, bagging, dan boosting. Misalnya, pada voting ensemble, prediksi akhir didapatkan dengan memilih hasil prediksi mayoritas dari model yang terlibat. Dengan menggabungkan hasil prediksi dari beberapa model yang berbeda, ensemble model pada dataset Heart Failure Prediction dapat meningkatkan akurasi dan performa prediksi. Dalam konteks medis, hal ini akan membantu dalam mengidentifikasi pasien dengan risiko tinggi gagal jantung, sehingga dapat dilakukan tindakan pencegahan yang tepat untuk meningkatkan prognosis dan kualitas hidup mereka.

## Dataset

Dataset yang digunakan dalam projek ini adalah **Heart Failure** yang berisi kelangsungan hidup pasien dengan gagal jantung dari kreatinin serum dan fraksi ejeksi. Dataset ini berjumlah 299 dengan 13 atribut. Pada projek ini atribut yang akan digunakan dan diperlukan untuk membuat sistem prediksi sebanyak 13 antara lain sebagai berikut:

- `age`: umur pasien
- `anaemia`: apakah ada pengurangan haemoglobin
- `creatinine_phosphokinase`: level enzim CPK dalam mcg/L
- `diabetes`: apakah pasien punya riwayat diabetes
- `ejection_fraction`: persentase darah yang meninggalkan jantung dalam persentasi di setiap kontraksi jantung
- `high_blood_pressure`: apakah pasien punya darah tinggi
- `platelets`: jumlah platelet di darah dalam kiloplatelets/mL
- `serum_creatinine`: level serum creatinine di darah dalam mg/dL
- `serum_sodium`: level serum sodium di darah dalam mEq/L
- `sex`: apakah pasien pria atau wanita
- `smoking`: apakah pasien merokok
- `time`: waktu dalam hari untuk follow-up
- `DEATH_EVENT`: apakah pasien sudah meninggal saat waktu follow-up

## Objektif

1. Menemukan faktor-faktor yang mempengaruhi keselamatan pasien dari penyakit jantung.
2. Menemukan akurasi prediksi keselamatan pasien dari penyakit jantung menggunakan konsep Classification dengan Ensemble Model.
3. Memberikan wawasan yang dapat bermanfaat bagi masyarakat mengenai penyakit jantung.

## Pengambilan Kesimpulan

### Faktor-Faktor

Dapat diketahui faktor-faktor yang mempengaruhi keselamatan pasien dengan riwayat penyakit jantung adalah sebagai berikut:

- `age`: umur pasien
- `anaemia`: apakah ada pengurangan haemoglobin
- `creatinine_phosphokinase`: level enzim CPK dalam mcg/L
- `diabetes`: apakah pasien punya riwayat diabetes
- `ejection_fraction`: persentase darah yang meninggalkan jantung dalam persentasi di setiap kontraksi jantung
- `high_blood_pressure`: apakah pasien punya darah tinggi
- `platelets`: jumlah platelet di darah dalam kiloplatelets/mL
- `serum_creatinine`: level serum creatinine di darah dalam mg/dL
- `serum_sodium`: level serum sodium di darah dalam mEq/L
- `sex`: apakah pasien pria atau wanita
- `smoking`: apakah pasien merokok
- `time`: waktu dalam hari untuk follow-up
- `DEATH_EVENT`: apakah pasien sudah meninggal saat waktu follow-up

### Akurasi

Berdasarkan pelatihan ensemble model yang telah dilakukan dapat diperoleh akurasi dari model Voting dari keempat model (Naive Bayes, KNN, Random Forest, dan Logistic Regression) adalah sebesar 87.70%.

### Wawasan

Insight yang ditemukan dalam prediksi keselamatan pasien dengan riwayat penyakit jantung adalah sebagai berikut:

- Dapat diketahui bahwa pasien yang meninggal karena penyakit jantung paling banyak berumur 60-an tahun.
- Dapat diketahui bahwa pasien yang memiliki penyakit jantung kebanyakan berjenis kelamin laki-laki.
- Dapat diketahui bahwa pasien yang meninggal biasanya memiliki kadar kreatinin lebih tinggi dan/atau kadar sodium yang lebih rendah.

## Kesimpulan

Proyek ini menunjukkan bahwa penggunaan ensemble model dapat meningkatkan akurasi prediksi risiko gagal jantung pada pasien. Dengan mengidentifikasi faktor-faktor kunci yang mempengaruhi keselamatan pasien, tenaga medis dapat mengambil tindakan pencegahan yang tepat untuk meningkatkan prognosis dan kualitas hidup pasien dengan riwayat penyakit jantung.
