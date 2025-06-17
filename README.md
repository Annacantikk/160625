# 160625
Proyek Akhir: Menyelesaikan Permasalahan Institusi Pendidikan

📌 Business Understanding
Jaya Jaya Institut merupakan salah satu institusi pendidikan perguruan yang telah berdiri sejak tahun 2000. Hingga saat ini ia telah mencetak banyak lulusan dengan reputasi yang sangat baik. Akan tetapi, terdapat banyak juga siswa yang tidak menyelesaikan pendidikannya alias dropout.

Jumlah dropout yang tinggi ini tentunya menjadi salah satu masalah yang besar untuk sebuah institusi pendidikan. Oleh karena itu, Jaya Jaya Institut ingin mendeteksi secepat mungkin siswa yang mungkin akan melakukan dropout sehingga dapat diberi bimbingan khusus.

Nah, sebagai calon data scientist masa depan Anda diminta untuk membantu Jaya Jaya Institut dalam menyelesaikan permasalahannya. Mereka telah menyediakan dataset yang dapat Anda unduh melalui tautan berikut: students' performance. Selain itu, mereka juga meminta Anda untuk membuatkan dashboard agar mereka mudah dalam memahami data dan memonitor performa siswa. 

📌 Permasalahan Bisnis
1. Bagaimana mengidentifikasi mahasiswa yang memiliki potensi dropout sedini mungkin?
2. Apa faktor-faktor yang paling berpengaruh terhadap kelulusan dan dropout?
3. Bagaimana menyajikan data performa siswa dalam bentuk yang mudah dipahami dan dapat ditindaklanjuti oleh pengambil keputusan?

📌 Cakupan Proyek
1. Eksplorasi dan pembersihan data mahasiswa dari Jaya Jaya Institut.
2. Analisis data deskriptif untuk memahami karakteristik mahasiswa berdasarkan status akhir (dropout, graduate, enrolled).
3. Pembangunan model prediksi machine learning untuk mendeteksi potensi dropout.
4. Pembuatan dashboard interaktif untuk memantau performa dan risiko mahasiswa.
5. Memberikan rekomendasi strategis berbasis data.

📌 Persiapan
Sumber data: Dataset students' performance dari Jaya Jaya Institut.
Format: CSV / Excel
Link: https://github.com/dicodingacademy/dicoding_dataset/blob/main/students_performance/data.csv

📌 Setup environment:
1. Google Colab untuk eksplorasi dan training model
2. Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, streamlit, dll.
3. Streamlit Cloud atau local host untuk men-deploy dashboard

📌 Business Dashboard
Dashboard ini dibuat untuk menampilkan analisis dan visualisasi kunci seperti:

Distribusi status akhir mahasiswa

Tren dropout berdasarkan gender, marital status, nationality, scholarship, tuition payment

Fitur penting penyebab dropout

Prediksi status mahasiswa berdasarkan input variabel

📌 Menjalankan Sistem Machine Learning
Model machine learning dikembangkan menggunakan algoritma seperti Logistic Regression, Random Forest, dan XGBoost.
Langkah:

Preprocessing data (handling missing values, encoding)

Feature selection

Train-test split

Model training & evaluation (accuracy, recall, F1-score)

Implementasi pipeline untuk prediksi

📌 Conclusion
Beasiswa dan pembayaran biaya kuliah sangat berkontribusi terhadap keberhasilan mahasiswa.

Mahasiswa perempuan memiliki tingkat kelulusan lebih tinggi dibanding laki-laki.

Mahasiswa internasional menunjukkan tingkat dropout yang lebih rendah.

Status pernikahan tertentu menunjukkan korelasi dengan risiko dropout.

Model prediktif berhasil dibangun dan dapat digunakan untuk memberikan peringatan dini.

📌 Rekomendasi Action Items
Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.
1. Tingkatkan Dukungan untuk Mahasiswa Perempuan -> Mahasiswa perempuan (0) jauh lebih banyak yang lulus (graduate) dibanding laki-laki.
💡 Action: Fokus pertahankan dan perkuat strategi pembelajaran yang mendukung keberhasilan perempuan. Selidiki juga hambatan yang dialami laki-laki.
2. Evaluasi Status Pernikahan Tertentu -> Pada grafik byMaritalStatus, status “1–2” mendominasi dropout dan enrolled.
💡 Action: Lakukan analisis lebih lanjut pada kelompok ini: apakah mereka butuh dukungan finansial, fleksibilitas kelas, atau bimbingan?
3. Internasional Tidak Banyak Dropout -> Dari grafik byNacionality%, mahasiswa internasional memiliki angka dropout rendah.
💡 Action: Amati kebijakan atau layanan apa yang membuat mahasiswa internasional bertahan dan adaptasikan bagi mahasiswa lokal.
4. Scholarship Sangat Efektif -> Dari byScholarship, penerima beasiswa (1) punya angka graduate lebih tinggi & dropout lebih rendah.
💡 Action: Perluas cakupan beasiswa bagi kelompok rawan DO (Drop Out).
5. Tuition Payment = Higher Success -> Mahasiswa yang membayar tuition (1) mendominasi lulusan.
💡 Action: Tinjau kembali kebijakan bebas biaya: apakah menyebabkan kurangnya komitmen? Atau mungkin perlu pendampingan ekstra.


Supabase mauliditaanna@gmail.com 3Sht&h+j6nv_C+L
