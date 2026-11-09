# Bagian 2 — Analisis Komparatif Platform

## Tabel Analisis Komparatif Platform

| Aspek | Web | Desktop | Mobile |
| :--- | :--- | :--- | :--- |
| **Bahasa utama** | JavaScript, TypeScript, HTML, CSS | C++, C#, Java, Swift, Python | Kotlin, Swift, Dart, JavaScript |
| **Arsitektur** | Client-Server (REST API/GraphQL, Microservices) | Standalone / Monolithic / Client-Server | Client-Server / Mobile-First Architecture |
| **Cara distribusi** | Web Browser via URL (Domain) | Installer (.exe, .dmg, .deb) / App Store | App Store (Google Play Store, Apple App Store) / APK |
| **Keunggulan** | Akses instan tanpa instalasi, *cross-platform*, pembaruan langsung dari server (*real-time update*) | Performa tinggi, akses penuh ke hardware/OS lokal, dapat berjalan offline secara optimal | Portabel, memanfaatkan fitur perangkat (GPS, Kamera, Sensor), notifikasi *push* |
| **Keterbatasan** | Keterbatasan akses hardware lokal, sangat bergantung pada koneksi internet | Membutuhkan instalasi dan pembaruan manual, keterbatasan kompatibilitas antar OS | Resource terbatas (baterai, RAM, layar kecil), proses *publishing* butuh review store |
| **Contoh aplikasi** | Google Docs, Trello, Figma Web | Visual Studio Code, Adobe Photoshop, Microsoft Word | WhatsApp, Instagram, Gojek |

---

## Referensi

1. MDN Web Docs. *Web Web Technology for Developers*. Tersedia di: https://developer.mozilla.org/
2. Android Developers Documentation. *Core topics in Android Development*. Tersedia di: https://developer.android.com/guide
3. Microsoft Learn. *Desktop Application Development Documentation*. Tersedia di: https://learn.microsoft.com/en-us/windows/apps/

Refleksi Pengembangan Platform

1. Platform yang Paling Menarik untuk Dipelajari dan Alasannya

Platform yang paling menarik bagi saya untuk dipelajari adalah Web Development. Alasan utamanya adalah sifatnya yang cross-platform dan fleksibilitas akses yang sangat tinggi, di mana aplikasi dapat langsung diakses oleh pengguna melalui browser tanpa perlu melalui proses instalasi. Selain itu, ekosistem web berkembang sangat pesat dengan tersedianya berbagai framework modern (seperti React, Vue, atau Next.js) yang memungkinkan pembuatan antarmuka responsif serta interaktif secara efisien.

2. Tantangan Terbesar saat Setup Environment

Tantangan terbesar yang saya hadapi saat melakukan setup environment adalah keselarasan versi alat (tools compatibility) serta konfigurasi path dan sistem autentikasi. Saat menginstal Git, Node.js, npm, dan Java, sering timbul isu ketergantungan versi (version mismatch) atau perintah terminal yang tidak dikenali karena variabel Environment System Path belum dikonfigurasi dengan benar. Selain itu, menghubungkan terminal lokal ke repository GitHub kerap memerlukan pengaturan kredensial/autentikasi yang tepat.

3. Rencana untuk Mengatasi Tantangan Tersebut

Untuk mengatasi tantangan ini, rencana yang akan saya terapkan adalah:

Dokumentasi Terstruktur: Membaca dan mengikuti dokumentasi resmi secara teliti untuk setiap instalasi alat.

Penggunaan Version Manager: Memanfaatkan tools seperti NVM (Node Version Manager) atau SDKMAN! untuk mempermudah pengelolaan serta peralihan antarversi software tanpa merusak sistem dasar.

Pemecahan Masalah Komunitas: Memanfaatkan forum teknis seperti Stack Overflow, Github Issues, dan dokumentasi resmi saat menjumpai pesan error teknis pada terminal.