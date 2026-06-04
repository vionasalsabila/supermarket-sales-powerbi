# Supermarket Sales Dashboard

## 1. Business Problem
Project ini bertujuan untuk menganalisis performa penjualan, profitabilitas, dan preferensi metode pembayaran di jaringan supermarket pada tahun 2019. Dashboard ini dirancang untuk membantu tim manajemen memantau metrik utama secara real-time dan mengambil keputusan strategis terkait manajemen inventaris serta taktik pemasaran.

## 2. Executive Key Insights (Analisis Strategis)
Berdasarkan visualisasi data pada dashboard, berikut adalah 3 temuan kritikal:

* **Profitabilitas & Konsistensi Tren:** Jaringan supermarket berhasil membukukan Total Revenue sebesar **307.59Rb** dengan Net Revenue **322.97Rb** dan total Profit mencapai **15.38Rb**. Tren profit harian menunjukkan fluktuasi yang sangat aktif sepanjang Q1 2019 (Januari - Maret), dengan lonjakan tertinggi (*peak penjualan*) terjadi di pertengahan bulan Februari dan Maret.
* **Analisis Lini Produk (Product Line Performance):** 
  * Produk **Food and beverages** merupakan *top performer* utama yang memimpin di dua aspek sekaligus: menghasilkan *Revenue* tertinggi dan mendapatkan kepuasan pelanggan tertinggi dengan *Rata-rata Rating* mencapai **7.11**.
  * Sebaliknya, produk **Home and lifestyle** berada di posisi paling bawah dengan rata-rata rating **6.84**, yang mengindikasikan perlunya evaluasi kualitas produk atau layanan pada kategori tersebut.
* **Perilaku Pembayaran Pelanggan (Payment Method Preference):** Metode pembayaran di supermarket ini terbagi cukup merata ke dalam tiga opsi. Penggunaan **Cash (Tunai)** dan **E-wallet (Dompet Digital)** mendominasi pasar secara seimbang dengan porsi masing-masing **34.34%**, disusul oleh **Credit Card** sebesar **31.25%**. 

## 3. Tech Stack & Data Modeling
* **Tools:** Power BI Desktop
* **Data Transformation:** Power Query (Data cleaning, standarisasi tipe data, dan format mata uang/satuan ribu `Rb`).
* **UI/UX Optimization:** 
  * Menerapkan pengelompokan warna kontras untuk membedakan struktur *Header* (Aksen Merah Muda), *KPI Cards* (Tosca modern untuk *quick monitoring*), dan *Slicer Filter* interaktif.
  * Pembuatan visualisasi multi-dimensi menggunakan *Donut Chart* untuk komposisi persentase, *Line Chart* untuk tren waktu, serta *Matrix/Table* dengan *Conditional Formatting* hijau pada kolom Profit untuk mempermudah pemindaian data (*scannability*).

## 4. Dashboard Preview
Berikut adalah tampilan penuh dari dashboard yang telah dioptimalkan:

![Supermarket Sales Dashboard Preview](dashboard_preview.png)

---
*Catatan: File mentah analisis `.pbix` tersedia di repository ini dan dapat diunduh untuk kebutuhan audit rumus atau pengembangan model data lebih lanjut.*
