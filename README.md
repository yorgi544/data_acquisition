# README
# Akuisisi Data Akomodasi Wisata Kabupaten Badung, Bali

## 1. Identitas Mahasiswa

- **Nama:** Herkulano Yorgi Novriandri Simuk
- **NIM:** 2501010203
- **Program Studi:** Informatika
- **Institusi:** INSTIKI

## 2. Deskripsi Proyek

Proyek ini bertujuan untuk melakukan akuisisi data akomodasi wisata yang berada di Kabupaten Badung, Bali.

Data diperoleh dari OpenStreetMap (OSM) menggunakan Overpass API. Data yang dikumpulkan meliputi informasi tempat akomodasi wisata seperti hotel, penginapan, dan jenis akomodasi lainnya.

## 3. Tujuan Proyek

1. Mengumpulkan data akomodasi wisata di Kabupaten Badung.
2. Memanfaatkan OpenStreetMap sebagai sumber data terbuka.
3. Menghasilkan dataset dengan minimal 100 record.
4. Mengumpulkan minimal 5 kolom data.
5. Menyimpan data dalam format JSON dan CSV.

## 4. Sumber Data

- **Sumber:** OpenStreetMap (OSM)
- **API:** Overpass API
- **Wilayah:** Kabupaten Badung, Bali, Indonesia
- **Lisensi:** Open Database License (ODbL)

Atribusi: © OpenStreetMap contributors.

## 5. Tools dan Teknologi

- Python
- Google Colab
- Requests
- Pandas
- OpenStreetMap
- Overpass API

## 6. Struktur Folder Proyek

```text
rtm1_2501010203/
│
├── notebooks/
│   └── akuisisi_overpass_badung.ipynb
│
├── data/
│   ├── raw/
│   │   ├── osm_akomodasi_badung.json
│   │   └── osm_akomodasi_badung.csv
│   │
│   └── processed/
│
├── docs/
│   ├── provenance.json
│   └── data_ethics_checklist.csv
│
└── README.md
```

## 7. Metode Pengumpulan Data

1. Menghubungkan Google Colab dengan Google Drive.
2. Mengakses Overpass API.
3. Mengambil data akomodasi wisata Kabupaten Badung.
4. Mengolah data menggunakan Pandas.
5. Menyimpan dataset dalam format JSON dan CSV.
6. Memeriksa kelengkapan dan kualitas data.

## 8. Target Dataset

Dataset ditargetkan memiliki:
- Minimal 100 record.
- Minimal 5 kolom.
- Format penyimpanan JSON dan CSV.

Contoh informasi yang dikumpulkan:
- ID objek
- Nama akomodasi
- Jenis akomodasi
- Latitude
- Longitude
- Alamat atau informasi lokasi (jika tersedia)

## 9. Cara Menjalankan Proyek

1. Buka Google Colab.
2. Buka file `akuisisi_overpass_badung.ipynb`.
3. Hubungkan Google Drive.
4. Jalankan setiap kode secara berurutan.
5. Tunggu proses pengambilan data selesai.
6. Periksa hasil dataset pada folder `data/raw/`.

## 10. Etika dan Lisensi Data

Data diperoleh dari OpenStreetMap yang menggunakan lisensi ODbL.

Penggunaan data harus mencantumkan atribusi kepada OpenStreetMap contributors. Data digunakan untuk keperluan pembelajaran dan penelitian akademik.

## 11. Hasil Akhir

Hasil akhir proyek berupa dataset akomodasi wisata Kabupaten Badung dalam format JSON dan CSV yang dapat digunakan untuk analisis dan pengolahan data lebih lanjut.

---

**Dibuat untuk memenuhi tugas mata kuliah RTM1.**
