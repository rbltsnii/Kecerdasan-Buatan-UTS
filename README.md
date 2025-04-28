---

# 🚀 UTS Kecerdasan Buatan

Repositori ini berisi hasil Ujian Tengah Semester (UTS) untuk mata kuliah **Kecerdasan Buatan**

---

## 🧠 Soal 1: Sistem Pakar Hama Tanaman

### Deskripsi
Sistem Pakar ini bertujuan untuk mendiagnosis jenis hama atau penyakit tanaman berdasarkan gejala yang diamati, menggunakan metode **logika proposisional**.

### Gejala yang Diamati
- G1: Daun menguning
- G2: Terdapat bercak hitam
- G3: Daun berlubang
- G4: Tanaman layu

### Hipotesis Diagnosa
- H1: Hama Wereng
- H2: Jamur Daun
- H3: Ulat Daun
- H4: Busuk Akar

### Aturan Logika
- Jika **Daun menguning** dan **Tanaman layu**, maka kemungkinan besar **Hama Wereng**.
- Jika **Terdapat bercak hitam** dan **Daun menguning**, maka kemungkinan **Jamur Daun**.
- Jika **Daun berlubang**, maka kemungkinan **Ulat Daun**.
- Jika hanya **Tanaman layu** (tanpa gejala lain), maka kemungkinan **Busuk Akar**.

### Pseudocode
Input gejala → Cocokkan aturan → Keluarkan diagnosis.

### Implementasi
Telah tersedia implementasi dalam:
- **Python**: fungsi `sistem_pakar()` menerima inputan gejala dan mengembalikan diagnosis.
- **Prolog**: menggunakan aturan fakta dan inferensi berbasis query.

---

## 📝 Soal 2: Review Jurnal AI

### Judul Jurnal
**"Architecture of Smart Health Care System Using Artificial Intelligence"**  
Oleh: **M.M. Kamruzzaman**

### Ringkasan
Penelitian ini bertujuan mengembangkan arsitektur sistem kesehatan pintar berbasis **AI** untuk meningkatkan efisiensi diagnosis medis. Menggunakan pendekatan **machine learning** dan **deep learning**, sistem dapat membaca data kompleks seperti citra radiologi dan rekam medis elektronik, lalu memberikan diagnosis otomatis dan akurat. Manfaat utamanya meliputi percepatan diagnosis, pengurangan beban dokter, dan penghematan biaya rumah sakit.

### Ide Pengembangan Lanjutan
- Integrasi dengan **wearable devices** dan **IoT** untuk monitoring kesehatan real-time.
- Penerapan **blockchain** untuk menjaga keamanan dan privasi data medis.

### Ide Aplikasi Serupa
Pengembangan aplikasi mobile berbasis AI untuk **monitoring kesehatan masyarakat** di daerah terpencil, dilengkapi dengan konsultasi dokter via **telemedicine**.

---

## 📁 Struktur Repositori

```
├── README.md
├── Review_Jurnal_AI.pdf
├── Sistem_Pakar_Hama_Tanaman.docx

```

---

## ✍️ Penulis
**Nama:** [Rabiul Tsani Ghifarulhaq A]  
**NIM:** [2306141]  
**Mata Kuliah:** Kecerdasan Buatan  

---
