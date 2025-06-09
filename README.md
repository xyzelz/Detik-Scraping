
<h1 align="center">📰 Detik.com News Scraper & Classifier</h1>

<p align="center">
  Scrape berita dari <strong>detik.com</strong> lalu klasifikasikan secara otomatis menjadi <em>Straight News</em> atau <em>In-Depth Reporting</em> menggunakan Python 🐍
</p>

---

## 🚀 Fitur Unggulan

✨ **Scrape Otomatis**  
🔍 Cari berdasarkan **keyword**  
⚡️ Ambil banyak artikel dengan **ThreadPoolExecutor** (multithreaded)  
🧹 **Ekstrak dan bersihkan** isi berita dengan `BeautifulSoup`  
🤖 **Klasifikasi otomatis** jenis artikel  
📊 **Simpan hasil ke Excel** (.xlsx)

---

## 🗂️ Struktur Proyek

```bash
.
├── main.py              # Program utama
├── utils.py             # Fungsi bantu untuk scraping dan klasifikasi
├── requirements.txt     # Library yang dibutuhkan
├── hasil/               # Output hasil scraping (Excel)
└── README.md            # Dokumentasi ini
```

---

## 🧪 Cara Penggunaan

### 1. Clone repo

```bash
git clone https://github.com/namakamu/detik-news-scraper.git
cd detik-news-scraper
```

### 2. Install dependensi

```bash
pip install -r requirements.txt
```

### 3. Jalankan

```bash
python main.py
```

🗣 Masukkan **kata kunci** dan jumlah artikel yang ingin diambil.  
📁 Hasil akan tersimpan dalam folder `hasil/` dalam format `.xlsx`.

---

## 🤖 Contoh Klasifikasi

| Judul Berita                           | Jenis Artikel       |
|----------------------------------------|----------------------|
| Presiden Resmikan Jalan Tol Baru       | Straight News        |
| Mengapa Harga Minyak Dunia Naik?       | In-Depth Reporting   |

Klasifikasi dilakukan berdasarkan:
- **Jumlah kata**
- **Struktur narasi**
- **Kedalaman analisis konten**

---

## 🛠 Teknologi yang Digunakan

- Python 3.x
- `requests`
- `BeautifulSoup`
- `concurrent.futures`
- `openpyxl`
- `re` (regular expressions)

---

## 📌 Catatan Penting

- ❌ **Bukan proyek resmi detik.com**
- 🧠 Hanya untuk keperluan **edukasi dan penelitian**
- 🤝 Gunakan dengan **bijak**, tidak untuk scraping masif atau pelanggaran TOS

---

## 🤝 Kontribusi

Kontribusi terbuka untuk semua!  
Fork project ini, buat fitur tambahan, atau bantu dokumentasi.  
Feel free to submit **pull requests** atau buka **issue** 💡

---

## 👤 Author

Made with ❤️ by [@xyzelz](https://github.com/xyzelz)  
📬 Hubungi jika ada ide, saran, atau pertanyaan

---

⭐ **Berikan bintang** jika kamu suka proyek ini!
