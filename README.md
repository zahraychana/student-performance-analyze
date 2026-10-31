# Analisis Transisi Nilai G1 → G2 → G3 (Kelompok 4)

Analisis faktor yang memengaruhi perubahan nilai siswa (dataset UCI Student Performance, mata pelajaran Matematika & Portugis).

## Struktur folder

```
data/                    Dataset mentah (UCI Student Performance)
  student-mat.csv        Data siswa mata pelajaran Matematika
  student-por.csv        Data siswa mata pelajaran Portugis
  keterangan_atribut.txt Penjelasan setiap kolom/atribut
  student-merge.R        Skrip R bawaan dataset untuk menggabungkan kedua file

notebooks/
  analisis_transisi_nilai_v2.ipynb      Notebook utama (versi terbaru) — jalankan ini
  analisis_transisi_nilai_v1_lama.ipynb Versi lama, disimpan sebagai arsip

output/                  Hasil dari notebook v2
  gambar/                Grafik (.png)
  tabel/                 Tabel hasil uji (.csv)
  interaktif/            Diagram Sankey interaktif (.html, buka di browser)
  kesimpulan_otomatis.txt Ringkasan kesimpulan
  arsip_v1/              Hasil dari notebook versi lama

docs/
  laporan_midterm_kelompok4.pdf Laporan midterm
```

## Arti awalan nama file output

- **A1–A6**: eksplorasi data (cleaning, distribusi, korelasi, faktor vs G3)
- **B1–B8**: analisis transisi (komposisi kategori, checkpoint G2, uji faktor, konsistensi, profil risiko)
- Akhiran `_mat` = Matematika, `_por` = Portugis

## Cara menjalankan

Buka `notebooks/analisis_transisi_nilai_v2.ipynb` lalu jalankan semua sel.
Dataset dibaca dari `data/`, hasil disimpan otomatis ke `output/`.
