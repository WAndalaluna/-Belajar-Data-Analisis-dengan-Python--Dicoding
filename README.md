# Belajar-Data-Analisis-dengan-Python-Dicoding

Proyek: Analisis Data E-Commerce

Repository ini berisi proyek analisis data yang berfokus pada E-Commerce Public Dataset. Tujuan proyek ini adalah untuk menghasilkan wawasan dan informasi yang bermanfaat dari data yang dianalisis, dengan hasil yang divisualisasikan melalui dashboard yang dideploy menggunakan Streamlit.

# Struktur Direktori
/data: Direktori ini berisi dataset yang digunakan dalam proyek dalam format .csv.gz.
- all_data.csv.gz
- geolocation.csv.gz

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
memulai server streamlit di dashboard anda
