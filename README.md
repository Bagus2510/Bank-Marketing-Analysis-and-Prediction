**Bank Marketing - Prediksi Langganan Deposito Berjangka**

📝 **Deskripsi Proyek**

Proyek ini bertujuan untuk membangun model machine learning yang dapat memprediksi apakah seorang klien bank akan berlangganan (atau "subscribe") deposito berjangka (term deposit) atau tidak. Dataset yang digunakan adalah Bank Marketing Dataset, yang berisi data kampanye pemasaran langsung melalui telepon oleh sebuah institusi perbankan di Portugal.

Analisis dan model yang dikembangkan dalam proyek ini diharapkan dapat membantu bank meningkatkan efektivitas kampanye pemasaran di masa depan, menargetkan klien yang memiliki probabilitas lebih tinggi untuk berlangganan produk.

**🎯 Tujuan Proyek**
1. Analisis Data Eksploratif (EDA): Menganalisis dan memahami karakteristik data, distribusi variabel, dan hubungan antar fitur dengan variabel target.

2. Pra-pemrosesan Data: Membersihkan data, menangani nilai yang hilang (jika ada), mengkodekan variabel kategorikal, dan melakukan penskalaan data numerik.

3. Pembangunan Model: Melatih beberapa model klasifikasi (misalnya, Regresi Logistik, Random Forest, atau Gradient Boosting) untuk memprediksi variabel target y.

4. Evaluasi Model: Mengevaluasi performa model menggunakan metrik seperti akurasi, presisi, recall, F1-score, dan Confusion Matrix.

5. Interpretasi Hasil: Mengidentifikasi faktor-faktor atau fitur yang paling berpengaruh dalam memprediksi keputusan klien untuk berlangganan deposito.

**📊 Deskripsi Dataset**

Dataset ini berisi 45.211 entri dan 17 kolom (16 fitur input dan 1 fitur output). Variabel-variabel tersebut dapat dikelompokkan menjadi tiga kategori:

**1. Data Klien Bank**

age: Usia klien (numerik).

job: Jenis pekerjaan klien (kategorikal).

marital: Status pernikahan klien (kategorikal).

education: Tingkat pendidikan klien (kategorikal).

default: Apakah klien memiliki kredit macet? (yes, no).

balance: Rata-rata saldo tahunan klien, dalam Euro (numerik).

housing: Apakah klien memiliki pinjaman rumah? (yes, no).

loan: Apakah klien memiliki pinjaman pribadi? (yes, no).

**2. Data Kontak Terakhir dari Kampanye**

contact: Jenis komunikasi kontak (cellular, telephone).

day: Hari terakhir kontak pada bulan tersebut (numerik).

month: Bulan terakhir kontak (jan, feb, mar, dll.).

duration: Durasi kontak terakhir, dalam detik (numerik). Catatan: Fitur ini sangat memengaruhi output, namun durasi tidak diketahui sebelum panggilan selesai.

**3. Data Lainnya**

campaign: Jumlah kontak yang dilakukan selama kampanye ini (numerik).

pdays: Jumlah hari sejak klien terakhir dihubungi dari kampanye sebelumnya. (-1 berarti tidak pernah dihubungi sebelumnya).

previous: Jumlah kontak yang dilakukan sebelum kampanye ini (numerik).

poutcome: Hasil dari kampanye pemasaran sebelumnya (failure, nonexistent, success).

**Variabel Target**

y: Apakah klien telah berlangganan deposito berjangka? (yes, no).

**Sumber Dataset:** 
https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing/data
