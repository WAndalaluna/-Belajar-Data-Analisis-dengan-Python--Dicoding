<!-- # Belajar-Data-Analisis-dengan-Python-Dicoding

Proyek: Analisis Data E-Commerce

Repository ini berisi proyek analisis data yang berfokus pada E-Commerce Public Dataset. Tujuan proyek ini adalah untuk menghasilkan wawasan dan informasi yang bermanfaat dari data yang dianalisis, dengan hasil yang divisualisasikan melalui dashboard yang dideploy menggunakan Streamlit.

# Struktur Direktori
/data: Direktori ini berisi dataset yang digunakan dalam proyek dalam format .csv
- all_data.csv
- geolocation.csv

/dashboard: Berisi file Python utama yang digunakan untuk membangun dan mendepoy dashboard hasil analisis data.
- dashboard.py: Script utama untuk menjalankan dashboard Streamlit.
- func.py: Script yang berisi fungsi-fungsi pendukung untuk analisis data.

notebook.ipynb: File Jupyter Notebook yang digunakan untuk proses analisis data.

requirements.txt: pustaka yang diperlukan untuk menjalankan proyek.

# Instalasi
Ikuti langkah-langkah berikut untuk mengatur dan menjalankan proyek ini secara lokal:

1. Clone repository:
git clone https://github.com/WAndalaluna/-Belajar-Data-Analisis-dengan-Python--Dicoding.git

2. Pastikan memiliki lingkungan Python yang sesuai dan pustaka yang diperlukan.
- pip install streamlit
- pip install -r requirements.txt

Penggunaan

1.Masuk ke direktori proyek:
cd -Belajar-Data-Analisis-dengan-Python--Dicoding/dashboard/

2.Jalankan aplikasi Streamlit:
streamlit run dashboard.py
memulai server streamlit di dashboard anda -->

# Belajar-Data-Analisis-dengan-Python-Dicoding"

## Project Analisis Data

Repository ini berisi proyek analisis data yang saya kerjakan dengan deployment menggunakan **Streamlit**

## Deskripsi

Tujuan proyek ini adalah untuk menghasilkan wawasan dan informasi yang bermanfaat dari data yang dianalisis, dengan hasil yang divisualisasikan melalui dashboard yang dideploy menggunakan Streamlit.

## Struktur Direktori

├── dashboard/
│   ├── __pycache__/
│   ├── dashboard.py         # Script utama untuk menjalankan dashboard Streamlit.
│   ├── func.py              # Fungsi pendukung untuk analisis dan pengolahan data.
├── data/
│   ├── all_data.csv           # Data gabungan semua kategori untuk analisis.
│   ├── customers_dataset.csv  # Data pelanggan.
│   ├── geolocation.csv        # Data lokasi geografis.
│   ├── geolocation_dataset.csv # Data lokasi geografis yang lebih mendetail.
│   ├── order_items_dataset.csv # Data item pesanan.
│   ├── order_payments_dataset.csv # Data pembayaran.
│   ├── order_reviews_dataset.csv # Data ulasan pesanan.
│   ├── orders_dataset.csv      # Data pesanan.
│   ├── product_category_name_translation.csv # Kategori produk.
│   ├── products_dataset.csv     # Data produk.
│   ├── sellers_dataset.csv      # Data penjual.
├── LICENSE
├── notebook.ipynb             # Jupyter Notebook untuk eksplorasi dan analisis data.
├── README.md                  # File ini berisi panduan penggunaan proyek.
├── requirements.txt           # Daftar pustaka yang dibutuhkan.
├── streamlit.png              # Gambar yang mungkin digunakan di dalam aplikasi atau dokumen.


## Instalasi

1. Clone repository ini ke komputer lokal Anda menggunakan perintah berikut:

   ```shell
   git clone https://github.com/WAndalaluna/-Belajar-Data-Analisis-dengan-Python--Dicoding.git
   ```

2. Pastikan Anda memiliki lingkungan Python yang sesuai dan pustaka-pustaka yang diperlukan. Anda dapat menginstal pustaka-pustaka tersebut dengan menjalankan perintah berikut:

   ```shell
   pip install streamlit
   pip install -r requirements.txt
   ```

## Penggunaan

1. Masuk ke direktori proyek (Local):

   ```shell
   cd -Belajar-Data-Analisis-dengan-Python--Dicoding/dashboar
   streamlit run dashboard.py
   ```

   Atau bisa mengunjungi website berikut [Project Data Analytics](https://dicoding-e-commerce.streamlit.app/)

   <img src="./dashboard/ss.png" alt="Streamlit logo"></img>
