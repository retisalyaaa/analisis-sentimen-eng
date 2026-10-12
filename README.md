# 📊 Aplikasi Analisis Sentimen Teks Bahasa Inggris

Aplikasi analisis sentimen berbasis *Natural Language Processing* (NLP) menggunakan Python dan Streamlit untuk menganalisis sentimen pada teks berbahasa Inggris.

Proyek ini memanfaatkan TextBlob dan VADER untuk mengeksplorasi polaritas, subjektivitas, serta skor sentimen teks melalui antarmuka interaktif dan visualisasi data.

## 📌 Tentang Proyek

Analisis sentimen merupakan salah satu penerapan *Natural Language Processing* (NLP) yang digunakan untuk mengidentifikasi kecenderungan sentimen dalam suatu teks, seperti positif, negatif, atau netral.

Proyek ini dikembangkan sebagai sarana pembelajaran untuk memahami penerapan analisis sentimen menggunakan Python. Pengguna dapat memasukkan teks berbahasa Inggris, kemudian melihat hasil analisis berupa klasifikasi sentimen, nilai polaritas, subjektivitas, serta skor sentimen pada setiap kata.

Hasil analisis ditampilkan melalui antarmuka interaktif yang dibangun menggunakan Streamlit dan dilengkapi visualisasi data agar lebih mudah dipahami.

## ✨ Fitur Utama

- **Input Teks:** Memungkinkan pengguna memasukkan teks berbahasa Inggris untuk dianalisis.
- **Klasifikasi Sentimen:** Mengelompokkan teks menjadi positif, negatif, atau netral berdasarkan nilai polaritas TextBlob.
- **Analisis Polaritas:** Menampilkan kecenderungan sentimen teks melalui nilai polaritas.
- **Analisis Subjektivitas:** Menampilkan nilai subjektivitas untuk membantu memahami karakteristik teks.
- **Analisis Sentimen per Kata:** Menggunakan VADER untuk memperoleh skor sentimen pada setiap kata.
- **Visualisasi Data:** Menampilkan hasil analisis dalam bentuk grafik menggunakan Altair.
- **Antarmuka Interaktif:** Menyediakan tampilan aplikasi yang dibangun dengan Streamlit.

## 🛠️ Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| Python | Bahasa pemrograman utama |
| Streamlit | Membangun antarmuka aplikasi interaktif |
| TextBlob | Menganalisis polaritas dan subjektivitas teks |
| VADER Sentiment | Menghasilkan skor sentimen |
| Pandas | Mengolah dan menyusun data hasil analisis |
| Altair | Membuat visualisasi data |

## ⚙️ Instalasi dan Persiapan

Ikuti langkah-langkah berikut untuk menjalankan proyek di komputer lokal.

### Prasyarat

Pastikan perangkat telah memiliki:
- Python
- pip
- Git

### 1. Clone Repository

Buka terminal, kemudian jalankan perintah berikut:

```bash
git clone https://github.com/retisalyaaa/analisis-sentimen-eng.git
```

### 2. Masuk ke Direktori Proyek

```bash
cd analisis-sentimen-eng
```

### 3. Buat Virtual Environment

Disarankan untuk menggunakan lingkungan virtual agar dependensi proyek terpisah dari proyek lainnya.

```bash
python -m venv .venv
```

Aktifkan virtual environment pada Windows:

```bash
.venv\Scripts\activate
```

Untuk macOS atau Linux:

```bash
source .venv/bin/activate
```

### 4. Instal Dependensi

```bash
pip install streamlit textblob pandas altair vaderSentiment
```

### 5. Jalankan Aplikasi

```bash
streamlit run SentimentAnalysis.py
```

Setelah aplikasi berhasil dijalankan, buka alamat lokal yang muncul pada terminal. Secara default, Streamlit biasanya menggunakan `http://localhost:8501`.

## 🧪 Cara Menggunakan Aplikasi

1. Jalankan aplikasi menggunakan Streamlit.
2. Buka halaman utama aplikasi.
3. Masukkan teks berbahasa Inggris pada kolom yang tersedia.
4. Klik tombol **Analyze** untuk memulai analisis.
5. Amati hasil klasifikasi sentimen, nilai polaritas, subjektivitas, skor sentimen per kata, dan visualisasi yang ditampilkan.

### Contoh Input

```text
I really enjoy learning new programming skills!
```

Aplikasi akan menganalisis teks tersebut menggunakan TextBlob dan VADER, kemudian menampilkan hasil sesuai dengan metode analisis yang diterapkan.

*Catatan: Hasil klasifikasi dan nilai skor bergantung pada teks yang dimasukkan serta metode analisis yang digunakan.*

## 📂 Struktur Proyek

```text
analisis-sentimen-eng/
├── README.md
└── SentimentAnalysis.py
```

## 📚 Hal yang Dipelajari

Melalui proyek ini, beberapa konsep yang dipelajari meliputi:

- Penerapan dasar *Natural Language Processing* (NLP) menggunakan Python.
- Penggunaan library TextBlob dan VADER untuk analisis sentimen.
- Pemahaman konsep polaritas dan subjektivitas teks.
- Pengolahan data hasil analisis menggunakan Pandas.
- Visualisasi hasil analisis menggunakan Altair.
- Pengembangan aplikasi interaktif menggunakan Streamlit.
- Penyusunan dokumentasi proyek untuk publikasi di GitHub.

## ⚠️ Keterbatasan

- Aplikasi difokuskan pada analisis teks berbahasa Inggris.
- Hasil analisis belum tentu mampu memahami sarkasme, konteks percakapan, atau makna tersirat secara akurat.
- Skor sentimen per kata dapat berbeda dari kecenderungan sentimen keseluruhan kalimat.
- Hasil analisis merupakan estimasi berdasarkan metode yang digunakan, bukan penilaian mutlak terhadap emosi seseorang.

## 🚀 Rencana Pengembangan

Beberapa pengembangan yang dapat dilakukan selanjutnya:

- Menambahkan validasi input dan penanganan teks kosong.
- Memperbaiki tampilan serta penyajian hasil analisis.
- Menambahkan contoh teks untuk membantu pengguna memahami hasil analisis.
- Mengembangkan pengujian untuk mengevaluasi hasil analisis sentimen.
- Mengeksplorasi metode NLP lainnya untuk membandingkan hasil analisis.

## 👩‍💻 Tentang Pengembang

**Retisalya** — [GitHub Profile](https://github.com/retisalyaaa)

Mahasiswa Teknologi Informasi yang tertarik pada pengembangan perangkat lunak, analisis data, dan penerapan *Natural Language Processing*.

Proyek ini merupakan bagian dari proses pembelajaran dan pengembangan keterampilan di bidang teknologi.

---

⭐ Jika proyek ini menarik atau bermanfaat, jangan ragu untuk menjelajahi repository dan memberikan masukan.

