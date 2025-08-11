# 📱 Android Kotlin Project

Proyek ini adalah contoh aplikasi Android yang dibuat menggunakan **Kotlin**.  
Tujuannya adalah untuk mempelajari dan mengimplementasikan dasar-dasar pengembangan aplikasi Android dengan bahasa Kotlin, termasuk penggunaan **Activity**, **View Binding**, **RecyclerView**, serta penerapan konsep **OOP (Object-Oriented Programming)** di Android.


# ✨ Fitur Utama
- **Antarmuka Modern** dengan Material Design
- **RecyclerView** untuk menampilkan daftar data secara dinamis
- **View Binding** untuk menghindari penggunaan `findViewById`
- **Navigasi antar Activity**
- **Pengelolaan Data** menggunakan model Kotlin
- **Event Handling** pada tombol dan elemen UI


#🛠️ Teknologi yang Digunakan
- **Kotlin** sebagai bahasa pemrograman utama
- **Android Studio** sebagai IDE pengembangan
- **Gradle** untuk build system
- **Material Components** untuk UI/UX modern


# 📂 Struktur Proyek

```
Android-Kotlin/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── example/
│   │   │   │           └── namaprojectanda/
│   │   │   │               ├── MainActivity.kt      # <-- File kode Kotlin utama
│   │   │   │               └── (file-file Kotlin lainnya...)
│   │   │   ├── res/
│   │   │   │   ├── drawable/                      # <-- Gambar, ikon, bentuk XML
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml        # <-- File layout UI (XML)
│   │   │   │   ├── mipmap/                        # <-- Ikon aplikasi (ic_launcher)
│   │   │   │   └── values/
│   │   │   │       ├── colors.xml
│   │   │   │       ├── strings.xml
│   │   │   │       └── themes.xml
│   │   │   └── AndroidManifest.xml              # <-- Manifest aplikasi (izin, komponen)
│   │   ├── test/                                # <-- Direktori untuk Unit Test
│   │   └── androidTest/                         # <-- Direktori untuk Instrumented Test
│   ├── build.gradle.kts                         # <-- Konfigurasi build khusus untuk modul 'app'
│   └── proguard-rules.pro                     # <-- Aturan ProGuard untuk optimasi kode
│
├── gradle/
│   └── wrapper/
│
├── .gitignore
├── build.gradle.kts                             # <-- Konfigurasi build untuk SELURUH proyek
├── gradle.properties
├── gradlew                                      # <-- Gradle wrapper script untuk Mac/Linux
├── gradlew.bat                                  # <-- Gradle wrapper script untuk Windows
└── settings.gradle.kts                          # <-- Pengaturan modul dalam proyek
```



## 🚀 Cara Menjalankan Proyek
1. Clone Repository
   ```bash
   git clone https://github.com/Achmadtegar23/Android-Kotlin.git
   
2. Buka di Android Studio
   ```bash
   File → Open → pilih folder Android-Kotlin

3. Sync Gradle
   ```bash
   Klik "Sync Now" jika diminta

4. Jalankan Aplikasi (Jika bermasalah silahkan berdiskusi dengan AI)
   ```bash
    Gunakan emulator Android atau perangkat fisik
