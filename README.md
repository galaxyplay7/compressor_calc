# Starting Air Compressor Calculator

Kalkulator web sederhana untuk menghitung **kapasitas minimum kompresor udara start (starting air compressor)** yang dibutuhkan, berdasarkan konsumsi udara per start, jumlah mesin, jumlah start, dan waktu pengisian.

Semua perhitungan berjalan 100% di browser kamu. Tidak ada data yang dikirim ke server.

## Rumus

```
Q = (Vst × neng × nst) / T
```

| Simbol | Arti | Satuan |
|--------|------|--------|
| `Q` | Kapasitas kompresor yang dibutuhkan | Nm³/hr |
| `Vst` | Konsumsi udara start per satu kali start | Nm³ |
| `neng` | Jumlah mesin (engine) | EA |
| `nst` | Jumlah start | kali |
| `T` | Waktu pengisian kompresor | hr (jam) |

### Contoh

Jika `Vst` = 5,5 Nm³, `neng` = 3, `nst` = 3, dan `T` = 1,5 jam:

- Total volume udara = 5,5 × 3 × 3 = 49,5 Nm³
- Q = 49,5 / 1,5 = **33 Nm³/hr**

## Fitur

- Input sederhana dengan validasi form
- Hasil langsung beserta rincian total volume udara
- Tombol **Salin Hasil** untuk menyalin hasil ke clipboard
- Tombol **Reset** untuk mengulang dari awal
- Tekan `Enter` di kolom input untuk langsung menghitung
- Tampilan responsif (nyaman di HP maupun laptop)

## Cara Menjalankan

Tidak perlu instalasi. Pilih salah satu:

1. **Buka langsung**: download repo ini, lalu buka file `index.html` di browser.
2. **GitHub Pages**: di repo, buka *Settings → Pages*, pilih branch `main` folder `/ (root)`, lalu simpan. Halaman akan tersedia di `https://galaxyplay7.github.io/compressor_calc/`.

> Halaman memakai Tailwind CSS dan font Inter lewat CDN, jadi butuh koneksi internet saat pertama kali dibuka.

## Teknologi

- HTML, CSS, dan JavaScript murni (vanilla)
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts

## Catatan Penggunaan

Hasil kalkulator ini adalah **estimasi awal** untuk membantu perencanaan. Untuk keperluan desain final, sertifikasi, atau kepatuhan terhadap aturan klasifikasi, tetap rujuk standar dan perhitungan resmi yang berlaku.

## Kebijakan Privasi

Lihat [PRIVACY.md](PRIVACY.md).

## Kontribusi

Saran dan perbaikan sangat terbuka. Silakan buka [Issue](https://github.com/galaxyplay7/compressor_calc/issues) atau kirim Pull Request.
