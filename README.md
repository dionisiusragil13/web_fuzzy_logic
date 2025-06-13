# Penentuan Keringanan UKT Mahasiswa dengan Logika Fuzzy Mamdani
Aplikasi web ini dirancang untuk membantu dalam penentuan keringanan Uang Kuliah Tunggal (UKT) bagi mahasiswa menggunakan implementasi Logika Fuzzy Mamdani. Sistem ini mempertimbangkan tiga variabel utama untuk melakukan klasifikasi, yaitu: Pendapatan Orang Tua, Tanggungan Orang Tua, dan Kepemilikan Kendaraan.

# Fitur Utama
Implementasi Logika Fuzzy Mamdani untuk penentuan keringanan UKT.

Antarmuka web yang intuitif untuk input data.

Output klasifikasi keringanan UKT berdasarkan aturan fuzzy.

# Prasyarat
Sebelum menjalankan aplikasi ini, pastikan Anda memiliki:

## 1. Python 3.x terinstal di sistem Anda.

## 2. pip (Package Installer for Python).

# Instalasi
Ikuti langkah-langkah di bawah ini untuk menginstal dan menyiapkan proyek di lingkungan lokal Anda:

## 1. Clone Repositori:
Jika Anda belum meng-clone repositori ini, lakukan dengan perintah berikut:

```git clone https://github.com/dionisiusragil13/web_fuzzy_logic.git```

## 2. Masuk ke Direktori Proyek:
Navigasikan ke direktori proyek yang baru saja Anda clone:

```cd web_fuzzy_logic```

## 3. Buat Lingkungan Virtual (Opsional, tapi Sangat Disarankan):
Membuat lingkungan virtual membantu mengisolasi dependensi proyek Anda.

```python -m venv venv```

## 4. Aktifkan Lingkungan Virtual:

- Untuk Windows:

```.\venv\Scripts\activate```

- Untuk macOS/Linux:

```source venv/bin/activate```

## 5. Instal Library yang Dibutuhkan:
Setelah lingkungan virtual aktif, instal semua library yang diperlukan dari requirements.txt:

```pip install -r requirements.txt```

# Cara Menggunakan
Setelah semua library terinstal, Anda bisa menjalankan aplikasi web ini:

Menggunakan `flask run` (Direkomendasikan)
## 1. Pastikan Lingkungan Virtual Aktif (jika Anda membuatnya).

## 2. Atur Variabel Lingkungan FLASK_APP:
Beritahu Flask di mana file aplikasi Anda berada.

- Untuk Windows:

```set FLASK_APP=app.py```

- Untuk macOS/Linux:

```export FLASK_APP=app.py```

## 3. Jalankan Aplikasi Flask:

```flask run```

Aplikasi akan berjalan di `http://127.0.0.1:5000/` secara default. Buka URL ini di browser Anda.

## Menggunakan Python Interpreter Langsung
Sebagai alternatif, Anda juga bisa menjalankan `app.py` langsung dengan interpreter Python, meskipun flask run lebih disarankan untuk pengembangan Flask.

## 1. Pastikan Lingkungan Virtual Aktif.

## 2. Jalankan `app.py` :

```bash
python app.py
```

Aplikasi akan berjalan di `http://127.0.0.1:5000/` secara default. Buka URL ini di browser Anda.

## Struktur Proyek (Ringkas)

- `app.py` : File utama aplikasi Flask yang menangani logika web dan integrasi logika fuzzy.
- `requirements.txt` : Daftar semua library Python yang dibutuhkan proyek.
- `static/` : Folder untuk file statis seperti CSS, JavaScript, gambar.
- `templates/` : Folder untuk file HTML template yang digunakan oleh Flask.
- `.gitignore` : File yang menentukan file dan folder yang harus diabaikan oleh Git.
- `fuzzy_mamdani.ipynb` *(jika ada)*: Notebook Jupyter yang mungkin berisi eksplorasi atau implementasi awal logika fuzzy.
- `klasifikasimhs.csv` *(jika ada)*: Dataset yang digunakan.
