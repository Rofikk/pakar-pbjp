# Pakar PBJP

Aplikasi pakar berbasis web untuk membantu calon penyedia menilai kesiapan awal mengikuti Pengadaan Barang/Jasa Pemerintah (PBJP).

## Fitur

- asesmen lima tahap;
- skor kesiapan dan klasifikasi risiko;
- rekomendasi tindakan berdasarkan jawaban;
- pemeriksaan legalitas, akun pengadaan, kapasitas, dan integritas;
- basis regulasi dengan tautan ke sumber resmi;
- penyimpanan jawaban hanya pada browser;
- hasil dapat dicetak atau disimpan sebagai PDF;
- responsif untuk desktop dan perangkat seluler.

## Batas penggunaan

Aplikasi ini merupakan alat edukasi dan pemeriksaan awal. Hasilnya bukan keputusan Pokja Pemilihan/Pejabat Pengadaan, bukan pendapat hukum, dan tidak menggantikan pembacaan dokumen pemilihan serta peraturan sektoral yang berlaku.

## Menjalankan secara lokal

Buka `index.html` langsung di browser atau jalankan server statis:

```bash
python3 -m http.server 8000
```

Lalu buka `http://localhost:8000`.

## Publikasi

Repositori menyertakan GitHub Actions untuk memublikasikan situs ke GitHub Pages setiap kali perubahan masuk ke branch `main`.

