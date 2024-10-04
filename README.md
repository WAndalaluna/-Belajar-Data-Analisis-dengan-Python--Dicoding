# Belajar-Data-Analisis-dengan-Python-Dicoding

Proyek: Analisis Data E-Commerce

Repository ini berisi proyek analisis data yang berfokus pada E-Commerce Public Dataset. Tujuan proyek ini adalah untuk menghasilkan wawasan dan informasi yang bermanfaat dari data yang dianalisis, dengan hasil yang divisualisasikan melalui dashboard yang dideploy menggunakan Streamlit.

# Struktur Direktori
/data: 
Direktori ini berisi dataset yang digunakan dalam proyek dalam format .csv.gz.
all_data.csv.gz
geolocation.csv.gz

/dashboard: Berisi file Python utama yang digunakan untuk membangun dan mendepoy dashboard hasil analisis data.

dashboard.py: Script utama untuk menjalankan dashboard Streamlit.
func.py: Script yang berisi fungsi-fungsi pendukung untuk analisis data.
notebook.ipynb: File Jupyter Notebook yang digunakan untuk proses analisis data.

# Instalasi
Ikuti langkah-langkah berikut untuk mengatur dan menjalankan proyek ini secara lokal:

Clone repository ke komputer lokal Anda:

bash
Copy code
git clone https://github.com/WAndalaluna/-Belajar-Data-Analisis-dengan-Python--Dicoding.git

Instal pustaka Python yang dibutuhkan:

bash
Copy code
pip install streamlit
pip install -r requirements.txt
Penggunaan
Masuk ke direktori proyek:

bash
Copy code
cd dicoding/dashboard/
Jalankan aplikasi Streamlit:

bash
Copy code
streamlit run dashboard.py
Ini akan memulai server Streamlit dan membuka dashboard di browser web Anda.