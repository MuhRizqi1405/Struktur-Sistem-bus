# 🚀 Struktur Antar Hubungan & Kinerja Bus Komputer

## 📌 1. Struktur Antar Hubungan
Struktur antar hubungan menggambarkan bagaimana elemen dalam sistem saling berinteraksi dan memengaruhi satu sama lain. Berikut beberapa jenisnya:

### 🔹 #Struktur_Hierarkis
- Hubungan berbentuk tingkatan, seperti:
  - **Organisasi Perusahaan**: CEO → Manajer → Karyawan
  - **Struktur Pemerintahan**: Presiden → Menteri → Gubernur → Wali Kota

### 🔹 #Struktur_Jaringan
- Hubungan yang lebih fleksibel, tanpa hierarki tetap:
  - **Media sosial**: Interaksi antar pengguna
  - **Perdagangan global**: Negara-negara saling bertransaksi

### 🔹 #Struktur_Matriks
- Setiap entitas bisa memiliki lebih dari satu jalur keterkaitan:
  - **Perusahaan Multinasional**: Divisi regional dan produk
  - **Universitas**: Dosen mengajar di beberapa fakultas

### 🔹 #Struktur_Fungsional
- Hubungan berdasarkan tugas atau fungsi:
  - **Departemen dalam perusahaan**: Keuangan, SDM, Pemasaran, Operasional
  - **Tim proyek**: Pemrograman, Desain, Manajemen

### 🔹 #Struktur_Simbiosis
- Hubungan saling menguntungkan:
  - **Produsen & Konsumen**: Saling membutuhkan
  - **Perusahaan teknologi & vendor hardware**: Kolaborasi inovasi

---

## ⚡ 2. Penyebab Penurunan Kinerja Bus
Ketika terlalu banyak perangkat terhubung ke **bus**, kinerja bisa menurun karena beberapa alasan berikut:

### 🔹 #Kontensi_Bus
- Banyak perangkat berebut akses, menyebabkan **konflik dan keterlambatan**.

### 🔹 #Bandwidth_Terbatas
- Semakin banyak perangkat, semakin kecil jatah **bandwidth** untuk masing-masing.

### 🔹 #Waktu_Propagasi
- Sinyal butuh lebih banyak waktu untuk mencapai tujuan jika bus terlalu panjang.

### 🔹 #Beban_Listrik
- Penambahan perangkat meningkatkan **kapasitansi**, mengganggu sinyal.

### 🔹 #Kolisi_Data
- Tanpa manajemen yang baik, data bisa bertabrakan, menyebabkan retransmisi.

### ✅ #Solusi
- Gunakan **bus dengan bandwidth lebih besar** seperti **PCIe**
- Terapkan **buffering & cache** untuk mengurangi bottleneck
- Gunakan **topologi star atau switch-based**
- Terapkan **arbitrasi bus atau TDMA** untuk pengelolaan akses

---

## 🎯 3. Prioritas Perangkat & Waktu Tunggu
Biasanya, perangkat dengan prioritas paling rendah justru punya **waktu tunggu rata-rata lebih singkat**. Kenapa? 🤔

### 🔹 #Peluang_Konflik_Rendah
- Perangkat prioritas rendah **jarang meminta akses**, sehingga ketika meminta, kemungkinan langsung dilayani lebih besar.

### 🔹 #FIFO_Efek
- Jika permintaan perangkat rendah, mereka bisa segera diproses **tanpa antre panjang**.

### 🔹 #Pola_Akses_Berbeda
- Perangkat prioritas tinggi sering berkompetisi satu sama lain, menyebabkan mereka **menunggu lebih lama**.

### ⚠️ #Kapan_Kondisi_Ini_Tidak_Berlaku?
1. **#Beban_Tinggi**: Jika semua perangkat terus aktif, prioritas rendah bisa **tidak kebagian akses**.
2. **#Tanpa_Aging**: Jika tidak ada mekanisme aging, prioritas rendah bisa mengalami **starvation**.
3. **#Interupsi_Tinggi**: Jika perangkat prioritas tinggi terus mengakses bus, prioritas rendah bisa **terabaikan**.
4. **#Algoritma_Berbeda**: Jika sistem menggunakan **Round-Robin**, semua perangkat dapat akses **secara bergantian**.

---

> 🔥 **Kesimpulan**: Meskipun perangkat prioritas rendah sering punya waktu tunggu lebih singkat, kondisi ini bisa berubah tergantung beban sistem dan algoritma manajemen bus. 🚀
