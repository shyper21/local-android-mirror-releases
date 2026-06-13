# Local Android Mirror Releases

Repository ini digunakan untuk menerbitkan installer dan metadata update resmi
Local Android Mirror.

## Instalasi

1. Unduh `Local-Android-Mirror-Setup-v1.1.0.exe` dari halaman Releases.
2. Cocokkan SHA-256 dengan file checksum release.
3. Jalankan installer EXE. Aplikasi dipasang untuk user Windows saat ini.

Aplikasi berjalan lokal pada `127.0.0.1:3030` dan menggunakan ADB serta scrcpy.
Repository release tidak menyimpan data HP, pairing code, alias device, clipboard,
atau log pengguna.

## Keamanan

- Installer tidak membutuhkan Administrator.
- Installer tidak menonaktifkan antivirus atau firewall.
- Jangan menonaktifkan Smart App Control; verifikasi hash EXE resmi sebelum instalasi.
- Node.js runtime, ADB, dan scrcpy disertakan dalam paket.
- Pairing code disensor dari log command aplikasi.
- Periksa file `SHA256SUMS.txt` sebelum instalasi.
- Update berikutnya dapat diperiksa dan dipasang dari tombol **Check Update**.
