# Estimasi Parameter Regresi Linear Menggunakan Teknik Resampling Jackknife
### Studi Kasus: Indeks Pembangunan Manusia (IPM) Provinsi Lampung 2024

---

## Deskripsi Project
Project ini menganalisis faktor-faktor yang memengaruhi Indeks Pembangunan Manusia (IPM) 
di 15 kabupaten/kota Provinsi Lampung menggunakan regresi linear berganda yang divalidasi 
dengan teknik resampling Jackknife.

---

## Tujuan
- Mengidentifikasi variabel yang berpengaruh signifikan terhadap IPM Provinsi Lampung
- Menguji stabilitas dan keandalan parameter model menggunakan metode Jackknife
- Menghasilkan model regresi yang reliabel pada dataset kecil

---

## Metode
| Tahap | Metode |
|---|---|
| Pemodelan | Regresi Linear Berganda (OLS) |
| Validasi | Resampling Jackknife |
| Tools | Python (statsmodels, numpy, pandas) |

---

## Hasil Utama
- **R² = 0,9944** — model menjelaskan 99,4% variasi IPM
- Ketiga variabel prediktor terbukti **signifikan** (p-value ≪ 0,05)
- Jackknife menghasilkan **15 estimasi koefisien** per variabel dengan stabilitas tinggi

### Variabel Prediktor:
- **X1** — Pengeluaran Per Kapita (PP)
- **X2** — Rata-rata Lama Sekolah (RLS)
- **X3** — Angka Harapan Hidup (AHH)

---

## Infografis
![Infografis Project](Infografis-Jackknife.jpg)

---

## Anggota Kelompok
| Nama | NIM |
|---|---|
| Rahmah Gustriana Deka | 123450102 |
| Givaro Ananta | 123450078 |
| Gusti Putu Ferazka Dhiyamika | 123450046 |
| Kevin Antoni Junior | 123450109 |

**Dosen Pengampu:**
Mika Alvionita Sitinjak, S.M.Si | Linda Rassiyanti, S.Si., M.Si.

---

## 🏫 Institut Teknologi Sumatera
S1 Sains Data — 2024
