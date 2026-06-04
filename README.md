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
