# KlikJasa

Aplikasi jasa sewa dan rental terpercaya yang dibangun dengan Flutter.

## Fitur

- **Splash Screen** - Halaman pembuka dengan animasi loading
- **Home Screen** - Halaman utama dengan kategori layanan
- **Login Screen** - Halaman masuk dengan validasi form
- **Register Screen** - Halaman pendaftaran dengan validasi lengkap
- **Category Detail Screen** - Halaman detail kategori layanan

## Kategori Layanan

1. **Sewa Kos** - Layanan sewa kos dan asrama
2. **Sewa Rumah** - Layanan sewa rumah dan apartemen
3. **Rental Mobil** - Layanan rental kendaraan
4. **Jasa Lainnya** - Berbagai jasa tambahan

## Cara Menjalankan

### Prerequisites

- Flutter SDK (versi 3.0.0 atau lebih baru)
- Android Studio / VS Code
- Android SDK (untuk Android)
- Xcode (untuk iOS, hanya di macOS)

### Langkah-langkah

1. **Clone repository**
   ```bash
   git clone <repository-url>
   cd KlikJasa
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run aplikasi**
   ```bash
   flutter run
   ```

### Build APK

Untuk membuat file APK:

```bash
flutter build apk
```

File APK akan tersedia di `build/app/outputs/flutter-apk/app-release.apk`

## Struktur Project

```
KlikJasa/
├── lib/
│   └── main.dart                 # Entry point aplikasi
├── screens/
│   ├── splash_screen.dart        # Halaman splash
│   ├── home_screen.dart          # Halaman utama
│   ├── login_screen.dart         # Halaman login
│   ├── register_screen.dart      # Halaman register
│   └── category_detail_screen.dart # Halaman detail kategori
├── android/                      # Konfigurasi Android
├── ios/                         # Konfigurasi iOS (jika ada)
└── pubspec.yaml                 # Dependencies Flutter
```

## Teknologi yang Digunakan

- **Flutter** - Framework UI cross-platform
- **Dart** - Bahasa pemrograman
- **Material Design** - Design system

## Kontribusi

Silakan buat pull request untuk kontribusi atau laporkan bug melalui issues.

## Lisensi

Project ini dilisensikan di bawah MIT License. 