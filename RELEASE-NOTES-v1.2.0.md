# MirrorSync v1.2.0

## Perubahan

- Nama aplikasi, shortcut, installer, dan tampilan diubah menjadi MirrorSync.
- Data lokal dipindahkan ke `%LOCALAPPDATA%\MirrorSync` dengan migrasi otomatis
  dari `%LOCALAPPDATA%\TOOLS-MIRROR`.
- Folder instalasi baru: `%LOCALAPPDATA%\Programs\MirrorSync`.
- Auto-update menggunakan paket ZIP `MirrorSync-Setup-v1.2.0.zip` dan verifikasi
  SHA-256 sebelum instalasi.
- EXE dan ZIP siap disalin ke flashdisk tanpa perlu mengunduh ulang.

## Instalasi

Jalankan `MirrorSync-Setup-v1.2.0.exe`. Jika Smart App Control memblokir EXE
karena penerbit belum ditandatangani, gunakan ZIP, extract seluruh isinya, lalu
jalankan `Install-MirrorSync.cmd`. Jangan matikan antivirus atau Smart App Control.
