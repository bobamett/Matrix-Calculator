# 📊 Matrix Calculator

![Matrix Calculator](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

Kalkulator Matriks interaktif berbasis web untuk melakukan berbagai operasi aljabar linear dengan visualisasi langkah-langkah penyelesaian yang detail.

## 🌟 Demo

🔗 **[Live Demo](https://bobamett.github.io/Matrix-Calculator/matrix_calculator.html)**

## 📋 Daftar Isi

- [Tentang Project](#-tentang-project)
- [Fitur](#-fitur)
- [Screenshot](#-screenshot)
- [Teknologi](#-teknologi)
- [Instalasi](#-instalasi)
- [Cara Penggunaan](#-cara-penggunaan)
- [Metode Perhitungan](#-metode-perhitungan)
- [Tim Pengembang](#-tim-pengembang)
- [Kontribusi](#-kontribusi)
- [Lisensi](#-lisensi)
- [Kontak](#-kontak)

## 🎯 Tentang Project

**Matrix Calculator** adalah aplikasi web yang dikembangkan untuk membantu mahasiswa, pelajar, dan profesional dalam melakukan perhitungan matriks dengan cepat dan akurat. Aplikasi ini menampilkan setiap langkah perhitungan secara detail, sehingga sangat berguna untuk pembelajaran dan verifikasi hasil manual.

### Tujuan Project
- Menyediakan tools pembelajaran Aljabar Linear yang mudah diakses
- Memvisualisasikan proses perhitungan matriks step-by-step
- Membantu verifikasi hasil perhitungan manual
- Meningkatkan pemahaman tentang metode numerik

## ✨ Fitur

### 🔢 Metode Perhitungan
- **Gauss Elimination** - Solusi sistem persamaan linear
- **Gauss-Jordan** - Reduced row echelon form
- **Cofactor Expansion** - Perhitungan determinan
- **Inverse Matrix** - Mencari matriks invers

### 🎨 Fitur Tambahan
- ✅ Input matriks fleksibel (2×2 hingga 5×5)
- ✅ Random fill untuk testing cepat
- ✅ Visualisasi step-by-step
- ✅ Responsive design (mobile & desktop)
- ✅ User interface modern dan intuitif
- ✅ Reset dan clear dengan satu klik
- ✅ Tampilan hasil dengan presisi desimal

## 📸 Screenshot

```
[Tambahkan screenshot aplikasi di sini]
```

## 🛠️ Teknologi

Project ini dibangun menggunakan:

- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) **HTML5** - Struktur halaman web
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) **CSS3** - Styling dan layout responsif
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) **Vanilla JavaScript** - Logika perhitungan dan interaktivitas

**Tidak ada dependency eksternal** - Pure vanilla web technologies!

## 🚀 Instalasi

### Option 1: Clone Repository

```bash
# Clone repository
git clone https://github.com/bobamett/Matrix-Calculator.git

# Masuk ke direktori project
cd Matrix-Calculator

# Buka file HTML di browser
# Untuk Windows:
start matrix_calculator.html
# Untuk Mac:
open matrix_calculator.html
# Untuk Linux:
xdg-open matrix_calculator.html
```

### Option 2: Download ZIP

1. Klik tombol **Code** → **Download ZIP**
2. Extract file ZIP
3. Buka `matrix_calculator.html` di browser

### Option 3: Akses Online

Langsung akses via GitHub Pages: [https://bobamett.github.io/Matrix-Calculator/matrix_calculator.html](https://bobamett.github.io/Matrix-Calculator/matrix_calculator.html)

## 📖 Cara Penggunaan

### Langkah-langkah:

1. **Pilih Metode Perhitungan**
   - Klik salah satu dari 4 tombol metode yang tersedia

2. **Tentukan Ukuran Matriks**
   - Input jumlah baris dan kolom
   - Klik "Buat Matriks"

3. **Isi Nilai Matriks**
   - Masukkan nilai secara manual, atau
   - Klik "Isi Acak" untuk generate angka random

4. **Hitung**
   - Klik tombol "Hitung"
   - Lihat hasil dan langkah-langkah penyelesaian

5. **Reset** (opsional)
   - Klik "Reset" untuk mengosongkan semua input

### Tips Penggunaan:
- Gunakan **Tab** untuk navigasi cepat antar input
- Nilai desimal dipisah dengan **titik** (.), bukan koma
- Untuk hasil terbaik, gunakan angka bulat atau desimal sederhana

## 🔬 Metode Perhitungan

### 1️⃣ Gauss Elimination
Menyelesaikan sistem persamaan linear Ax = b dengan:
- Forward elimination (bentuk segitiga atas)
- Back substitution untuk mencari solusi
- Partial pivoting untuk stabilitas numerik

**Use case**: Sistem persamaan linear, ranking matriks

### 2️⃣ Gauss-Jordan
Eliminasi lengkap hingga bentuk reduced row echelon:
- Normalisasi setiap pivot menjadi 1
- Eliminasi ke atas dan ke bawah
- Hasil langsung tanpa substitusi

**Use case**: Solusi sistem persamaan, mencari invers

### 3️⃣ Cofactor Expansion
Menghitung determinan dengan ekspansi kofaktor:
- Ekspansi pada baris pertama
- Rekursif untuk sub-matriks
- Detail perhitungan setiap minor

**Use case**: Determinan, tes invertibility

### 4️⃣ Inverse Matrix
Mencari matriks invers A⁻¹:
- Augmented matrix [A|I]
- Gauss-Jordan elimination
- Hasil [I|A⁻¹]

**Use case**: Solusi sistem persamaan, transformasi linear

## 👥 Tim Pengembang

Project ini dikembangkan oleh mahasiswa **Teknik Perkapalan - UPN Veteran Jakarta**:

| Nama | NIM |
|------|-----|
| Rifki Andrian | 2210313004 |
| Anandita Fatihah | 2210313012 |
| Deva Natasya | 2210313020 |
| Colin Steven Aruan | 2210313026 |
| Muhammad Aljabbar | 2210313033 |
| Adam Rayhan | 2210313066 |

**Dosen Pembimbing**: [Nama Dosen]  
**Mata Kuliah**: Aljabar Linear / Metode Numerik

## 🤝 Kontribusi

Kontribusi sangat diterima! Berikut cara berkontribusi:

1. Fork repository ini
2. Buat branch baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

### Ide Kontribusi:
- 🐛 Fix bugs
- ✨ Tambah fitur baru (Cramer's Rule, Eigenvalue, dll)
- 📝 Perbaiki dokumentasi
- 🎨 Tingkatkan UI/UX
- 🌐 Tambahkan bahasa lain (English version)

## 📄 Lisensi

Distributed under the MIT License. See `LICENSE` for more information.

```
MIT License

Copyright (c) 2025 Matrix Calculator Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

## 📞 Kontak

**Admin & Contact Person**: Adam Rayhan

- 📧 Email: [2210313066@mahasiswa.upnvj.ac.id](mailto:2210313066@mahasiswa.upnvj.ac.id)
- 🏫 Institusi: UPN Veteran Jakarta
- 🎓 Jurusan: Teknik Perkapalan
- 📍 Alamat: Jl. Pd. Labu Raya, Cilandak, Jakarta Selatan 12450

**Quick Actions**:
- 🐛 [Laporkan Bug](mailto:2210313066@mahasiswa.upnvj.ac.id?subject=Laporan%20Bug%20-%20Matrix%20Calculator)
- 💡 [Kirim Saran](mailto:2210313066@mahasiswa.upnvj.ac.id?subject=Saran%20-%20Matrix%20Calculator)
- ❓ [Tanya Jawab](mailto:2210313066@mahasiswa.upnvj.ac.id?subject=Pertanyaan%20-%20Matrix%20Calculator)

## 🔗 Links

- 🌐 **Live Demo**: [https://bobamett.github.io/Matrix-Calculator/](https://bobamett.github.io/Matrix-Calculator/)
- 📦 **Repository**: [https://github.com/bobamett/Matrix-Calculator](https://github.com/bobamett/Matrix-Calculator)
- 🏛️ **UPN Veteran Jakarta**: [https://upnvj.ac.id](https://upnvj.ac.id)

## 🙏 Acknowledgments

- Terima kasih kepada dosen pembimbing atas bimbingannya
- Referensi algoritma dari buku "Linear Algebra and Its Applications"
- Inspirasi UI dari berbagai modern web calculator
- Komunitas Stack Overflow untuk solusi debugging

---

<div align="center">

**⭐ Jika project ini membantu, jangan lupa beri star! ⭐**

Made with ❤️ by Tim Teknik Perkapalan UPN Veteran Jakarta

[⬆ Back to Top](#-matrix-calculator)

</div>
