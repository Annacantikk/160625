# 160625
Proyek Akhir: Menyelesaikan Permasalahan Institusi Pendidikan

#📌 Business Understanding
Jaya Jaya Institut merupakan salah satu institusi pendidikan perguruan yang telah berdiri sejak tahun 2000. Hingga saat ini ia telah mencetak banyak lulusan dengan reputasi yang sangat baik. Akan tetapi, terdapat banyak juga siswa yang tidak menyelesaikan pendidikannya alias dropout.

Jumlah dropout yang tinggi ini tentunya menjadi salah satu masalah yang besar untuk sebuah institusi pendidikan. Oleh karena itu, Jaya Jaya Institut ingin mendeteksi secepat mungkin siswa yang mungkin akan melakukan dropout sehingga dapat diberi bimbingan khusus.

Nah, sebagai calon data scientist masa depan Anda diminta untuk membantu Jaya Jaya Institut dalam menyelesaikan permasalahannya. Mereka telah menyediakan dataset yang dapat Anda unduh melalui tautan berikut: students' performance. Selain itu, mereka juga meminta Anda untuk membuatkan dashboard agar mereka mudah dalam memahami data dan memonitor performa siswa. 

#📌 Permasalahan Bisnis
1. Bagaimana mengidentifikasi mahasiswa yang memiliki potensi dropout sedini mungkin?
2. Apa faktor-faktor yang paling berpengaruh terhadap kelulusan dan dropout?
3. Bagaimana menyajikan data performa siswa dalam bentuk yang mudah dipahami dan dapat ditindaklanjuti oleh pengambil keputusan?

#📌 Cakupan Proyek
1. Eksplorasi dan pembersihan data mahasiswa dari Jaya Jaya Institut.
2. Analisis data deskriptif untuk memahami karakteristik mahasiswa berdasarkan status akhir (dropout, graduate, enrolled).
3. Pembangunan model prediksi machine learning untuk mendeteksi potensi dropout.
4. Pembuatan dashboard interaktif untuk memantau performa dan risiko mahasiswa.
5. Memberikan rekomendasi strategis berbasis data.

#📌 Persiapan
Sumber data: Dataset students' performance dari Jaya Jaya Institut.
Format: CSV / Excel
Link: https://github.com/dicodingacademy/dicoding_dataset/blob/main/students_performance/data.csv

#📌 Setup environment:
1. Google Colab untuk eksplorasi dan training model
2. Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, streamlit, dll.
3. Streamlit Cloud atau local host untuk men-deploy dashboard

#📌 Business Dashboard
![Screenshot 2025-05-17 114356](https://github.com/user-attachments/assets/8c4d4d8d-79d9-4444-b9a2-3271f9988938)
Dashboard interaktif ini dirancang untuk membantu institusi dalam memantau performa mahasiswa secara menyeluruh. Visualisasi yang disajikan mencakup distribusi status akhir mahasiswa (enrolled, dropout, graduated), tren dropout berdasarkan variabel seperti gender, status pernikahan, kewarganegaraan, beasiswa, dan pembayaran biaya kuliah. Selain itu, dashboard ini juga menampilkan fitur-fitur penting yang mempengaruhi risiko dropout serta menyediakan fitur prediksi status mahasiswa berdasarkan input karakteristik tertentu. Dengan tampilan yang informatif dan mudah digunakan, dashboard ini mempermudah pihak institusi dalam mengambil keputusan berbasis data.

#📌 Menjalankan Sistem Machine Learning
Sistem prediksi dikembangkan menggunakan algoritma machine learning seperti Decision Tree, Random Forest, dan XGBoost.
Untuk menjalankan sistem ini, langkah-langkah yang dilakukan meliputi:
1. Preprocessing data – seperti penanganan nilai kosong dan encoding variabel kategori.
2. Feature selection – memilih fitur yang paling berpengaruh terhadap status akhir mahasiswa.
3. Train-test split – membagi data menjadi data latih dan data uji.
4. Training & evaluation – melatih model dan mengevaluasi performa menggunakan metrik seperti akurasi, recall, dan F1-score.
5. Pipeline implementation – mengintegrasikan model terbaik ke dalam pipeline yang siap digunakan untuk prediksi.

Prototype ini dapat diakses secara online dan menyediakan fitur prediksi status mahasiswa berdasarkan input yang diberikan pengguna.
Link Prototype: https://annacantikk-expert0625.streamlit.app/

#📌 Conclusion
Hasil analisis menunjukkan bahwa beasiswa dan pembayaran biaya kuliah memiliki pengaruh signifikan terhadap keberhasilan akademik mahasiswa. Mahasiswa perempuan tercatat memiliki tingkat kelulusan yang lebih tinggi dibanding laki-laki. Mahasiswa internasional menunjukkan tingkat dropout yang lebih rendah, mengindikasikan adanya faktor pendukung yang efektif. Selain itu, status pernikahan tertentu tampaknya berhubungan dengan risiko dropout yang lebih tinggi. Dengan model prediktif yang telah dibangun, institusi kini dapat memberikan peringatan dini kepada mahasiswa yang berisiko, sehingga intervensi dan bimbingan dapat diberikan secara tepat waktu.

#📌 Rekomendasi Action Items
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
