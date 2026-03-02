# 📱 Biodata Flutter

Aplikasi profil personal berbasis Flutter dengan desain modern dan elegan.

![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

## 📸 Screenshot

| Dark Mode |
|:---------:|
| Modern glassmorphism design dengan gradient background |

## ✨ Fitur

- 🎨 **Desain Modern** - Glassmorphism UI dengan efek kaca semi-transparan
- 🌈 **Gradient Background** - Kombinasi warna dark purple-navy yang elegan
- 🖼️ **Profile Card** - Foto profil dengan border gradient dan glow effect
- 📊 **Info Cards** - Tampilan informasi dengan icon berwarna berbeda
- 📱 **Responsive** - Mendukung berbagai ukuran layar
- 🌙 **Dark Theme** - Tema gelap yang nyaman untuk mata

## 🛠️ Teknologi

- **Framework:** Flutter 3.x
- **Bahasa:** Dart
- **UI:** Material Design 3
- **State Management:** StatelessWidget

## 📁 Struktur Proyek

```
biodata_flutter/
├── lib/
│   └── main.dart          # Entry point & UI aplikasi
├── assets/
│   └── images/
│       └── profile.jpg    # Foto profil
├── pubspec.yaml           # Dependencies & assets config
└── README.md
```

## 🚀 Cara Menjalankan

### Prasyarat

- Flutter SDK 3.x atau lebih baru
- Dart SDK 3.x atau lebih baru
- Android Studio / VS Code dengan Flutter extension

### Instalasi

1. **Clone repository**
   ```bash
   git clone https://github.com/username/biodata_flutter.git
   cd biodata_flutter
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Jalankan aplikasi**
   ```bash
   flutter run
   ```

## 📝 Konfigurasi

### Mengganti Foto Profil

1. Letakkan foto di folder `assets/images/`
2. Rename menjadi `profile.jpg` atau update path di `main.dart`
3. Pastikan sudah terdaftar di `pubspec.yaml`:
   ```yaml
   flutter:
     assets:
       - assets/images/
   ```

### Mengubah Data Profil

Edit data di file `lib/main.dart` pada bagian:
- Nama: `'Gavin Dwi Aurora Putra'`
- NRP: `'3124521018'`
- Institusi, Program Studi, Semester, Lokasi

## 🎨 Customisasi Warna

Warna utama dapat diubah di `main.dart`:

| Komponen | Warna | Hex Code |
|----------|-------|----------|
| Primary | Purple | `#6C63FF` |
| Accent | Cyan | `#00D9FF` |
| NRP | Red | `#FF6B6B` |
| Semester | Teal | `#4ECDC4` |
| Lokasi | Yellow | `#FFBE0B` |
| Background | Navy | `#1A1A2E`, `#16213E`, `#0F3460` |

## 👤 Author

**Gavin Dwi Aurora Putra**
- NRP: 3124521018
- Institusi: Politeknik Elektronika Negeri Surabaya
- Program Studi: D3 Teknik Informatika
- Semester: 4

## 📄 License

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

<p align="center">
  Made with ❤️ using Flutter
</p>
