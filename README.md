# RFM Analysis

## __Overview__

Dalam industri e-commerce, **mempertahankan pelanggan** dan **mengidentifikasi pelanggan terbaik** merupakan aspek krusial untuk menjaga kelangsungan bisnis dan meningkatkan pertumbuhan penjualan. Seiring dengan tren belanja online yang terus meningkat, perusahaan-perusahaan e-commerce, seperti **Perusahaan XYZ E-Commerce**, perlu terus berinovasi dalam mengembangkan strategi pemasaran yang efektif, khususnya terkait dengan retensi pelanggan.

**Perusahaan XYZ E-Commerce** adalah platform yang menyediakan berbagai macam produk, seperti **furnitur**, **alat tulis kantor (ATK)**, dan **elektronik**. Dengan semakin banyak pelanggan yang berbelanja dari berbagai wilayah, perusahaan mengumpulkan sejumlah besar data transaksi. Data ini dapat digunakan untuk **memahami perilaku pelanggan**, yang sangat penting untuk menyusun strategi guna menjaga hubungan dengan pelanggan dan meningkatkan penjualan mereka.

Untuk itu, perusahaan perlu menerapkan **analisis RFM** (**Recency, Frequency, Monetary**) untuk mengidentifikasi pelanggan terbaik, memahami pola belanja, serta merumuskan strategi yang lebih tepat guna meningkatkan loyalitas pelanggan dan memaksimalkan pendapatan.

---

## __Pernyataan Masalah__

Seiring dengan meningkatnya jumlah pelanggan dan transaksi di **Perusahaan XYZ E-Commerce**, perusahaan menghadapi tantangan dalam mengelola pelanggan secara efektif. Tantangan utama yang dihadapi antara lain:

1. **Menjaga pelanggan agar tetap loyal**: Beberapa pelanggan mungkin hanya berbelanja satu atau dua kali, lalu tidak kembali. Perusahaan membutuhkan cara untuk mengidentifikasi pelanggan yang masih aktif dan merumuskan strategi yang efektif untuk meningkatkan **frekuensi pembelian** mereka.
   
2. **Mengidentifikasi pelanggan terbaik**: Dari sekian banyak pelanggan, ada yang memberikan kontribusi besar dalam hal **frekuensi dan nilai pembelian**. Penting untuk mengidentifikasi pelanggan bernilai tinggi ini dan memastikan mereka tetap puas serta loyal kepada perusahaan.

Dengan menggunakan analisis RFM, kita dapat mengelompokkan pelanggan berdasarkan **waktu pembelian terakhir (Recency)**, **frekuensi pembelian (Frequency)**, dan **nilai total pembelian (Monetary)**. Berdasarkan data ini, kita dapat menjawab pertanyaan-pertanyaan penting, seperti:

- Siapa saja pelanggan terbaik yang perlu mendapatkan perhatian khusus dari perusahaan?
- Bagaimana cara meningkatkan loyalitas pelanggan yang berpotensi untuk menjadi lebih setia?
- Pelanggan mana yang berisiko untuk tidak kembali berbelanja, dan bagaimana cara memulihkan mereka?

---

## __Data__

Untuk menjawab pertanyaan-pertanyaan di atas, digunakan dataset penjualan dari **Perusahaan XYZ E-Commerce** untuk periode **2011 hingga 2014**, yang mencakup data transaksi, produk, dan pelanggan. Data ini akan dianalisis menggunakan model **RFM** untuk memberikan skor berdasarkan:

1. **Recency**: Jarak waktu sejak transaksi terakhir pelanggan hingga tanggal referensi (contohnya, 1 Januari 2015). Semakin baru transaksinya, semakin tinggi skor recency yang diberikan.
   
2. **Frequency**: Jumlah total transaksi yang dilakukan oleh pelanggan dalam periode tertentu. Semakin sering pelanggan berbelanja, semakin tinggi frekuensinya, dan semakin tinggi skornya.
   
3. **Monetary**: Total uang yang dihabiskan oleh pelanggan selama periode tersebut. Semakin besar nilai pembelian pelanggan, semakin tinggi skor monetary yang diberikan.

### Dataset ini terdiri dari kolom-kolom berikut yang relevan untuk analisis RFM:
- **Order ID**: ID unik untuk setiap transaksi.
- **Order Date**: Tanggal transaksi dilakukan.
- **Customer Name**: Nama pelanggan yang melakukan transaksi.
- **Sales**: Total uang yang dihasilkan dari setiap transaksi.

Melalui data ini, segmen pelanggan akan dibuat berdasarkan skor RFM untuk membantu merumuskan **strategi pemasaran yang lebih terarah**, seperti **kampanye retensi pelanggan**, **peningkatan frekuensi pembelian**, dan **program loyalitas**.

---
