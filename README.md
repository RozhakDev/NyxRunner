# NyxRunner - Deployment Otomatis Proyek GitHub ke Google Colab 🌙

**NyxRunner** membantu kamu menjalankan proyek GitHub secara otomatis di Google Colab. Cocok banget buat developer atau siapa pun yang punya laptop spesifikasi minim tapi butuh proses deploy cepat dan ringan.

## Fitur Utama

* **Log Lengkap**: Setiap langkah menampilkan `[INFO]`, `[DEBUG]`, dan lainnya supaya gampang debug.
* **Clone Repo Otomatis**: Tinggal jalanin, repo langsung di-clone ke Colab.
* **Install Dependensi**: Semua kebutuhan dari `requirements.txt` langsung terpasang.
* **Ngrok Tunnel**: Akses server Flask dari URL publik secara instan.

## Cara Menggunakan

1. **Buka Colab** dan upload file `NyxRunner_Deploy_Auto.ipynb`.
2. Jalankan sel dari atas ke bawah.
3. Ikuti log `[INFO]` untuk memantau proses.
4. Dapatkan URL publik dan nikmati server Flask yang sudah siap.

## Struktur Utama

```
NyxRunner_Deploy_Auto.ipynb   # Notebook utama untuk deployment otomatis
requirements.txt              # Daftar dependensi proyek (sesuaikan dengan kebutuhan repo)
run.py                        # File server Flask yang dijalankan
```

## Catatan

* Pastikan token ngrok valid sebelum menjalankan notebook.
* Jika terjadi error, cek log `[DEBUG]` untuk detail.

## Peringatan & Edukasi

> Proyek **NyxRunner** dibuat hanya untuk tujuan pembelajaran dan edukasi.
> Gunakan dengan penuh tanggung jawab dan jangan disalahgunakan ya~ 💖

## Penutup ❤️

Proyek ini lahir untuk memudahkan teman-teman developer yang ingin **deploy cepat, ringan, dan praktis**.
Selamat mencoba dan semoga bermanfaat!