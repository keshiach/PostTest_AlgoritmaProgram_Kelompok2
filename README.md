# PostTest_AlgoritmaProgram_Kelompok2
# 📊 Proyek Analisis Data Kebahagiaan Global (Global Happiness Analysis)

Repositori ini berisi proyek kolaborasi kelompok untuk menganalisis, memvisualisasikan, dan menyusun infografis mengenai faktor-faktor yang memengaruhi skor kebahagiaan (*Happy Score*) di berbagai wilayah dunia. 

---

## 👥 Anggota Kelompok & Rincian Tugas (Job Description)

Untuk memastikan kelancaran proyek, pembagian beban kerja telah didistribusikan secara merata kepada seluruh anggota kelompok dengan rincian sebagai berikut:

### 🔵 Keshia
* **Pengolahan Data (Grafik 1 - Agregasi):** Mencari nilai maksimum *Happy Score* per wilayah (*Region*) dan menyajikannya dalam bentuk **Horizontal Bar Chart**.
* **Standar Kode:** Menggunakan pendekatan berbasis objek (`ax = axes[x, y]`).
* **Manajemen Repositori:** Membuat dan melakukan *setup* awal repositori GitHub kelompok (Public), serta bertanggung jawab menyusun berkas `README.md` ini.

### 🟣 Tiana
* **Pengolahan Data (Grafik 2 - Tren/Filter):** Menyaring data negara dengan kriteria `avg_income > 15.000` namun memiliki *Happy Score* di bawah rata-rata global, lalu menyajikannya dalam bentuk **Bar Chart**.
* **Standar Kode:** Menggunakan pendekatan berbasis objek (`ax = axes[x, y]`).
* **Desain Infografis:** Membuat template dan *layout* awal desain infografis dengan format Instagram Story (9:16) dan LinkedIn (1:1 / 4:5 / PDF Slider), serta memastikan keterbacaan teks grafik.

### 🟤 Ludi
* **Pengolahan Data (Grafik 5 - Gabungan):** Menggabungkan Grafik 1 hingga Grafik 4 ke dalam satu *grid* layout 2×2 menggunakan fungsi `plt.subplots(2, 2, figsize=(...))`.
* **Finalisasi Infografis:** Menggabungkan seluruh komponen grafik individual dan teks analisis/insight ke dalam template desain, lalu mengekspornya menjadi berkas resolusi tinggi (`.png`/`.jpg`/`.pdf`).

### 🟡 Najwa
* **Pengolahan Data (Grafik 4 - Distribusi):** Menganalisis variabilitas `std_satisfaction` dari 10 negara teratas dan menyajikannya dalam bentuk **Bar Chart**.
* **Standar Kode:** Menggunakan pendekatan berbasis objek (`ax = axes[x, y]`).
* **Penulisan Konten:** Menyusun narasi *insight* atau kesimpulan singkat yang edukatif dan mudah dipahami oleh audiens awam untuk kelima grafik yang tersedia.

### 🟢 Rayna
* **Pengolahan Data (Grafik 3 - Korelasi):** Menganalisis hubungan antara `avg_income` vs `median_income` menggunakan **Scatter Plot**.
* **Standar Kode:** Menggunakan pendekatan berbasis objek (`ax = axes[x, y]`).
* **Review & Quality Control:** Memeriksa dan merapikan seluruh sintaks kode anggota kelompok sebelum digabungkan ke berkas `.ipynb` final. Memastikan parameter pemisah data (`sep=';'` dan `decimal=','`) serta konsistensi elemen visual (judul, label sumbu, legenda) terpenuhi.

---

## ⚖️ Matriks Keseimbangan Beban Kerja

| Anggota Kelompok | Fokus Utama Tugas | Estimasi Beban Kerja |
| :--- | :--- | :---: |
| 🔵 **Keshia** | Grafik 1 (Agregasi) + GitHub Setup | 🟡 Sedang |
| 🟣 **Tiana** | Grafik 2 (Filter) + Layout Infografis | 🟡 Sedang |
| 🟤 **Ludi** | Grafik 5 (Grid 2x2) + Finalisasi Desain | 🟡 Sedang |
| 🟡 **Najwa** | Grafik 4 (Distribusi) + Penulisan Insight | 🟡 Sedang |
| 🟢 **Rayna** | Grafik 3 (Korelasi) + Code Review & Integrasi | 🟡 Sedang |

---

## 📦 Komitmen Bersama & Standar Kerja

1.  **Versi Kode Tunggal:** Seluruh proses analisis dan visualisasi disatukan ke dalam satu file utama: `main.ipynb` (atau sesuai nama berkas kelompok).
2.  **Manajemen Git:** Setiap anggota kelompok wajib melakukan *clone*, membuat *branch* (opsional), dan melakukan *commit/push* hasil kerjanya masing-masing ke repositori ini.
3.  **Struktur Berkas Repositori:**
    * 📁 `data/` : Berisi berkas data mentah (`.csv`).
    * 📁 `output/` : Berisi hasil ekspor infografis (`.png`, `.jpg`, `.pdf`).
    * 📄 `notebook.ipynb` : Berkas Jupyter Notebook utama yang berisi seluruh kode visualisasi.
    * 📄 `README.md` : Dokumentasi pembagian tugas proyek.

---

## 📢 Rencana Publikasi & Dokumentasi

Setelah proyek selesai, setiap anggota kelompok akan melakukan publikasi mandiri secara serentak paling lambat **Sabtu, 6 Juni 2026 pukul 23:59 WIB** pada platform berikut:

* **LinkedIn:** Mengunggah infografis final, menyertakan tautan menuju repositori GitHub ini pada *caption*, serta menandai (tag) akun **BKTI** dan seluruh **Asisten Praktikum (Asprak)** yang bertugas.
* **Instagram Story:** Mengunggah infografis dengan format 9:16 serta menandai akun Instagram resmi **BKTI** dan akun Asprak kelas.
* 
