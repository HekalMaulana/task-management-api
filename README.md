# 🚀 Task Prioritization AI - Backend API

Repositori ini berisi layanan *Backend API* berbasis algoritma *Machine Learning* (Naive Bayes) untuk memprioritaskan dan mengurutkan daftar tugas secara otomatis. Dibangun dengan performa tinggi menggunakan **FastAPI** dan **Scikit-Learn**.

## 📋 Prasyarat Sistem

Sistem ini sangat ringan dan fleksibel. Anda hanya membutuhkan:
* [Python 3.9 atau lebih baru](https://www.python.org/downloads/) (Sudah ter-install di sistem/server)
* Git

## 🛠️ Cara Instalasi & Menjalankan Program (Setup)

Ikuti langkah-langkah di bawah ini untuk menjalankan API di lokal atau server produksi Anda.

### Langkah 1: Clone Repositori
Buka terminal/command prompt, lalu *clone* repositori ini:
```bash
git clone [https://github.com/HekalMaulana/task-management-api.git](https://github.com/HekalMaulana/task-management-api.git)
cd task-management-api

# Membuat environment bernama 'env'
python -m venv env   # (atau 'python3 -m venv env' di Mac/Linux)

# Mengaktifkan environment (Windows)
env\Scripts\activate

# Mengaktifkan environment (Mac/Linux)
source env/bin/activate

# Install Dependency/Library yang dibutuhkan dan pastikan sudah berada didalam direktori ini
pip install -r requirements.txt

# Jalankan Server FastAPI (Untuk Development)
uvicorn main:app --reload

# Untuk Production
uvicorn main:app --host 0.0.0.0 --port 8000# task-management-api
