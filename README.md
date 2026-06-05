# 📊 Happiness and Satisfaction Data Analysis Project

## 👥 Anggota Kelompok

| Nama      | Tanggung Jawab                                    |
| --------- | ------------------------------------------------- |
| 🔵 Keshia | Grafik 1 (Agregasi) + Setup GitHub                |
| 🟣 Tiana  | Grafik 2 (Tren/Filter) + Desain Layout Infografis |
| 🟤 Ludi   | Grafik 5 (Gabungan) + Finalisasi Infografis       |
| 🟡 Najwa  | Grafik 4 (Distribusi) + Penulisan Insight         |
| 🟢 Rayna  | Grafik 3 (Korelasi) + Review & Perapian Kode      |

---

# 🎯 Deskripsi Proyek

Proyek ini bertujuan melakukan analisis data **Happiness and Satisfaction** menggunakan Python dan visualisasi data untuk menemukan pola, tren, hubungan antar variabel, serta menyajikan hasil analisis dalam bentuk infografis yang informatif dan mudah dipahami.


---

# 📈 Pembagian Tugas Detail

## 🔵 KESHIA

### Grafik 1 — Analisis Agregasi Regional

**Tugas Pengolahan Data**

* Membersihkan data awal jika diperlukan.
* Mengelompokkan data berdasarkan `Region`.
* Menghitung nilai maksimum `Happy Score` pada setiap region.
* Membuat **Horizontal Bar Chart** menggunakan pendekatan objek:

```python
ax = axes[x, y]
```

* Menambahkan:

  * Judul grafik
  * Label sumbu
  * Nilai pada bar (jika memungkinkan)

### Tugas GitHub

* Membuat repository GitHub kelompok (Public).
* Mengatur struktur folder proyek.
* Mengunggah:

  * Dataset (.csv)
  * Notebook (.ipynb)
  * Infografis (.png/.jpg/.pdf)
* Membuat dan memperbarui README.md.
* Memastikan seluruh anggota dapat melakukan commit dan push.

---

## 🟣 TIANA

### Grafik 2 — Analisis Tren/Filter

**Tugas Pengolahan Data**

* Menentukan rata-rata global `Happy Score`.
* Menyaring negara dengan:

  * `avg_income > 15000`
  * `Happy Score < rata-rata global`
* Membuat visualisasi **Bar Chart** menggunakan pendekatan objek.
* Menambahkan label dan anotasi yang informatif.

### Tugas Desain Infografis

* Mendesain template utama infografis.
* Menentukan:

  * Warna
  * Tipografi
  * Layout visual
* Menyiapkan format:

  * Instagram Story (9:16)
  * LinkedIn Post (1:1)
  * LinkedIn Portrait (4:5)
  * PDF Slide

---

## 🟤 LUDI

### Grafik 5 — Visualisasi Gabungan

**Tugas Pengolahan Data**

* Menggabungkan Grafik 1–4 dalam satu tampilan menggunakan:

```python
plt.subplots(2,2, figsize=(...))
```

* Menyesuaikan ukuran dan tata letak grafik.
* Memastikan seluruh grafik tampil proporsional dan mudah dibaca.

### Tugas Finalisasi Infografis

* Mengintegrasikan:

  * Grafik dari seluruh anggota
  * Insight dari Najwa
  * Template desain dari Tiana
* Mengekspor hasil akhir menjadi:

  * PNG
  * JPG
  * PDF resolusi tinggi

---

## 🟡 NAJWA

### Grafik 4 — Analisis Distribusi

**Tugas Pengolahan Data**

* Menentukan 10 negara dengan skor kebahagiaan tertinggi.
* Mengambil nilai `std_satisfaction`.
* Membuat **Bar Chart** distribusi menggunakan pendekatan objek.
* Menambahkan label dan keterangan yang relevan.

### Tugas Penulisan Insight

* Menulis interpretasi untuk seluruh grafik.
* Menyusun kesimpulan yang:

  * Ringkas
  * Informatif
  * Mudah dipahami masyarakat umum
* Menjelaskan makna data tanpa istilah teknis yang berlebihan.

---

## 🟢 RAYNA

### Grafik 3 — Analisis Korelasi

**Tugas Pengolahan Data**

* Menganalisis hubungan:

  * `avg_income`
  * `median_income`
* Membuat **Scatter Plot** menggunakan pendekatan objek.
* Menambahkan:

  * Judul
  * Label sumbu
  * Garis tren (jika diperlukan)

### Review & Quality Assurance

* Memeriksa konsistensi kode seluruh anggota.
* Memastikan penggunaan:

```python
sep=';'
decimal=','
```

* Menyeragamkan:

  * Judul grafik
  * Label sumbu
  * Ukuran font
  * Warna dan gaya visualisasi
* Menghapus kode yang redundan sebelum notebook final digabungkan.

---

# 📂 Struktur Repository

```text
📦 Happiness-and-Satisfaction-Analysis
│
├── data/
│   └── Kelas_D_Happiness_and_Satisfaction.csv
│
├── notebooks/
│   └── Analisis_Happiness.ipynb
│
├── infographic/
│
├── images/
│   └── seluruh grafik hasil analisis
│
└── README.md
```

---

# 🤝 Tanggung Jawab Bersama

Seluruh anggota wajib:

✅ Menyelesaikan tugas sesuai pembagian

✅ Melakukan commit hasil pekerjaan masing-masing ke GitHub

✅ Memberikan dokumentasi kode yang jelas

✅ Membantu proses integrasi notebook final

✅ Melakukan pengecekan akhir sebelum pengumpulan

---

# 🛠 Tools yang Digunakan

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab
* GitHub
* Canva/Figma (Infografis)

---

# 📌 Output Proyek

1. Dataset yang telah dianalisis
2. Lima grafik visualisasi data
3. Notebook Python (.ipynb)
4. Infografis final
5. Repository GitHub lengkap dengan dokumentasi proyek
