#TUGAS WOOF
## Alendra Rafif 5025221297
## PPB - G


# Woof 🐕

## Overview
Woof adalah aplikasi Android yang menampilkan daftar anjing dengan informasi nama dan usia mereka. Aplikasi ini dibangun menggunakan **Jetpack Compose** dan mengimplementasikan **Material Design 3** dengan dukungan tema terang dan gelap.

## Fitur Utama
- **Daftar Anjing**: Menampilkan koleksi anjing dengan foto, nama, dan usia
- **Material Design 3**: Menggunakan komponen UI modern dengan sistem warna yang konsisten
- **Tema Dinamis**: Mendukung tema terang dan gelap
- **Responsive Layout**: Tata letak yang responsif dengan LazyColumn untuk performa optimal
- **Custom Typography**: Menggunakan font Abril Fatface dan Montserrat untuk tampilan yang menarik

## Teknologi yang Digunakan
- **Kotlin**: Bahasa pemrograman utama
- **Jetpack Compose**: Framework UI modern untuk Android
- **Material Design 3**: Sistem desain terbaru dari Google
- **Android Architecture Components**: Untuk struktur aplikasi yang solid

## Struktur Aplikasi

### MainActivity.kt
File utama yang berisi:
- `MainActivity`: Activity utama aplikasi
- `WoofApp`: Composable utama dengan Scaffold dan LazyColumn
- `DogItem`: Komponen untuk menampilkan setiap item anjing
- `DogIcon`: Komponen untuk menampilkan foto anjing
- `DogInformation`: Komponen untuk menampilkan nama dan usia anjing
- `WoofTopAppBar`: App bar dengan logo dan judul aplikasi

### UI Theme Package
**Theme.kt**
- Konfigurasi tema aplikasi dengan dukungan tema terang/gelap
- Integrasi dengan Material Design 3 color schemes
- Pengaturan status bar sesuai tema

**Color.kt**
- Definisi lengkap color palette untuk tema terang dan gelap
- Warna utama menggunakan skema hijau yang menenangkan
- Semua token warna Material Design 3

**Type.kt**
- Konfigurasi typography dengan custom font families
- **Abril Fatface**: Font untuk judul besar (displayLarge)
- **Montserrat**: Font untuk teks konten (displayMedium, bodyLarge, labelSmall)

**Shape.kt**
- Definisi bentuk komponen UI
- Rounded corners untuk berbagai elemen interface

## Arsitektur UI

### Komponen Utama
1. **Scaffold**: Struktur dasar aplikasi dengan top app bar
2. **LazyColumn**: List yang efisien untuk menampilkan data anjing
3. **Card**: Container untuk setiap item anjing
4. **Row & Column**: Layout untuk menyusun elemen UI

### Material Design 3 Features
- **Color Schemes**: Sistem warna yang konsisten
- **Typography Scale**: Hierarki teks yang jelas
- **Shape System**: Bentuk komponen yang unified
- **Dynamic Color**: Dukungan untuk warna dinamis Android 12+

## Cara Penggunaan
1. Aplikasi akan menampilkan daftar anjing dalam bentuk kartu
2. Setiap kartu berisi foto anjing, nama, dan usia
3. Scroll untuk melihat semua anjing dalam daftar
4. Tema akan menyesuaikan dengan pengaturan sistem (terang/gelap)

## Kustomisasi
- **Menambah Anjing**: Tambahkan data baru di file `dogs` data source
- **Mengubah Warna**: Modifikasi color palette di `Color.kt`
- **Mengubah Font**: Ganti font family di `Type.kt`
- **Mengubah Bentuk**: Sesuaikan shapes di `Shape.kt`

## Preview
Aplikasi menyediakan preview function untuk development:
- `WoofPreview()`: Preview tema terang
- `WoofDarkThemePreview()`: Preview tema gelap

## Lisensi
Aplikasi ini menggunakan lisensi Apache License 2.0

---

*Aplikasi ini merupakan contoh implementasi best practices untuk pengembangan aplikasi Android menggunakan Jetpack Compose dan Material Design 3.*
