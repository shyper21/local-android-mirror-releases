# MirrorSync Releases

Repository ini digunakan untuk menerbitkan installer dan metadata update resmi
MirrorSync.

## Instalasi

1. Unduh `MirrorSync-Setup-v1.2.1.exe` atau paket ZIP dari halaman Releases.
2. Cocokkan SHA-256 dengan `SHA256SUMS.txt`.
3. Jalankan EXE. Jika Smart App Control memblokir EXE yang belum ditandatangani,
   extract ZIP lalu jalankan `Install-MirrorSync.cmd`.

Aplikasi berjalan lokal pada `127.0.0.1:3030` dan menggunakan ADB serta scrcpy.
Repository release tidak menyimpan data HP, pairing code, alias device,
clipboard, atau log pengguna.

## Keamanan

- Installer tidak membutuhkan Administrator.
- Installer tidak menonaktifkan antivirus atau firewall.
- Jangan menonaktifkan Smart App Control untuk memasang aplikasi.
- Node.js runtime, ADB, dan scrcpy disertakan dalam paket.
- Pairing code disensor dari log command aplikasi.
- Update diperiksa melalui metadata `latest.json` dan paket diverifikasi SHA-256.
