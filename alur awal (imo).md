# Ngalor ngidul alias alur

## Perhitungan kalori harian
* User input gender, BB, TB, usia, aktivitas (5 kategori)
  - **Sangat jarang olahraga**: dikali 1,2
  - **Jarang olahraga (1-3 ali per minggu)**: dikali 1,375
  - **Cukup olahraga (3-5 kali per minggu)**: dikali 1,55
  - **Sering olahraga (6-7 kali per minggu)**: dikali 1,725
  - **Sangat sering olahraga (sekitar 2 kali dalam sehari)**: dikali 1,9
* Hitung kalori harian (by Harris Benedict)
  - **Laki-laki** = 66 + (13,7 x berat badan ) + (5 x tinggi badan) – (6,8 x usia)
  - **Wanita** = 655 + (9,6 x berat badan) + (1,8 x tinggi badan) – (4,7 x usia)
* Ketemu kalori harian, convert ke kebutuhan zat gizi makro (protein, lemak, karbohidrat)
  - **Kebutuhan protein** adalah sebesar 10 – 15% dari kebutuhan kalori total. Setelah menemukan besarnya kalori untuk protein, ubahlah ke dalam gram. Protein sebanyak 1 gram setara dengan 4 kalori.
  - **Kebutuhan lemak** adalah sebesar 10 – 25% dari kebutuhan kalori total. Lemak sebanyak 1 gram setara dengan 9 kalori.
  - **Kebutuhan karbohidrat** adalah sebesar 60 – 75% dari kebutuhan kalori total. Karbohidrat sebanyak 1 gram setara dengan 4 kalori.

  *ps. Kalo tanya apa kebutuhan gizi mikro, ini katanya ga bisa dihitung pake rumus kaya di atas, soalnya banyak gizinya, lengkapnya ada di Peraturan Menteri Kesehatan RI 2019.*

  - Dari rumus diatas, didapatkan kebutuhan gizi makro ideal tiap harinya, lanjut ke sistem rekomendasi

## Sistem rekomendasi makanan
### Data
* [bahan untuk masak](https://www.honestdocs.id/tabel-kalori-makanan-dan-minuman)
* [data fatsecret, bagus bgt](https://www.fatsecret.co.id/kalori-gizi/)
* [data mealcatering](https://www.mymealcatering.com/kesehatan/tabel-kalori-makanan-dan-minuman.html)
* [data repo unisula, makanan indo](https://repository.unissula.ac.id/18072/8/Lampiran.pdf)

## My question
* Kan ini perhitungannya adanya yg harian, nanti kita bisa merekomendasikannya yaudah rekomendasi aja atau kita bagi 3 (makan pagi-siang-malem) or????
* Analisisnya apa ya, ga kebayang

## Reference
* [hitung kalori harian](https://www.mymealcatering.com/kesehatan/cara-menghitung-akg-yang-benar.html)
* [hitung kebutuhan gizi makro](https://hellosehat.com/nutrisi/pengertian-akg/)

