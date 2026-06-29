# Example — Post-Match Learning
## Brasil vs Jepang — Piala Dunia 2026 Round of 32

> File ini adalah contoh evaluasi setelah pertandingan selesai.

---

## Input

```markdown
Evaluasi post-match:

- Kompetisi: Piala Dunia
- Tahun: 2026
- Fase: Round of 32
- Tim A: Brasil
- Tim B: Jepang
- Prediksi awal: Brasil menang 2-1
- Prediksi alternatif: Brasil 2-0, Brasil 1-0, 1-1 extra time
- Probabilitas awal: Brasil 60%, Seri 22%, Jepang 18%
- Hasil aktual: Brasil menang
- Skor akhir: Brasil 2-1 Jepang
- Pemenang: Brasil
- Gol: data gol belum diisi
- Kartu merah: data tidak tersedia / belum diisi
- Momen penentu: data tidak tersedia / belum diisi
- Catatan tambahan: evaluasi akurasi dan perbaiki model
```

---

# Post-Match Learning: Brasil vs Jepang

## Hasil Aktual

- **Skor akhir:** Brasil 2-1 Jepang
- **Pemenang:** Brasil
- **Tim lolos:** Brasil
- **Extra time:** Tidak
- **Penalti:** Tidak
- **Gol:** data tidak tersedia / belum diisi
- **Kartu merah:** data tidak tersedia / belum diisi
- **Momen penentu:** data tidak tersedia / belum diisi

---

## Evaluasi Prediksi

| Komponen | Prediksi | Hasil Aktual | Status |
|---|---|---|---|
| Pemenang | Brasil | Brasil | Benar |
| Skor utama | Brasil 2-1 Jepang | Brasil 2-1 Jepang | Tepat |
| Skor alternatif | Brasil 2-0 / 1-0 / 1-1 ET | Brasil 2-1 | Tidak diperlukan |
| Over/Under 2.5 | Over 2.5 cukup mungkin | 3 gol | Benar |
| Kedua tim mencetak gol | Ya / sedang-tinggi | Ya | Benar |
| Clean sheet | Clean sheet Brasil mungkin tetapi tidak dominan | Tidak clean sheet | Benar secara risiko |
| Tim lolos | Brasil | Brasil | Benar |
| Extra time | Tidak sebagai skenario utama | Tidak | Benar |
| Penalti | Rendah | Tidak | Benar |

---

## Skor Akurasi Prediksi

| Aspek | Bobot | Status | Skor |
|---|---:|---|---:|
| Pemenang benar | 35% | Benar | 35 |
| Skor tepat | 25% | Tepat | 25 |
| Margin gol benar | 15% | Benar | 15 |
| Pola pertandingan benar | 10% | Cukup benar | 8 |
| Risiko utama terbukti | 10% | Jepang bisa mencetak gol | 8 |
| Confidence sesuai | 5% | Sesuai | 5 |

**Skor Akurasi Total:** 96 / 100  
**Kategori:** Sangat baik

---

## Calibration Review

| Probabilitas Awal | Hasil Aktual | Evaluasi Kalibrasi |
|---|---|---|
| Brasil menang: 60% | Brasil menang | Tepat / sedikit konservatif |
| Seri: 22% | Tidak seri | Masuk akal sebagai risiko |
| Jepang menang: 18% | Jepang kalah | Tidak berlebihan |
| Over 2.5 | Terjadi | Tepat |
| BTTS | Terjadi | Tepat |

---

## Error Attribution

| Penyebab | Jenis Error | Dampak | Perlu Koreksi Bobot? |
|---|---|---|---|
| Detail gol belum dianalisis | Data gap | Membatasi learning taktis | Ya, jika data gol tersedia |
| Statistik detail belum dimasukkan | Data gap | Membatasi evaluasi xG/shot quality | Ya |
| Prediksi ulang sempat condong 2-0 | Model adjustment error kecil | Terlalu menurunkan peluang Jepang mencetak gol | Sedikit |

---

## What Worked

| Hal yang Berhasil Diprediksi | Bukti dari Pertandingan | Implikasi ke Model |
|---|---|---|
| Brasil menang | Hasil akhir Brasil 2-1 | Bobot kekuatan dasar dan skuad tepat |
| Jepang mencetak gol | Skor akhir 2-1 | Risiko transisi Jepang tepat dihitung |
| Skor utama 2-1 | Sama dengan hasil aktual | Model skor cukup baik |
| Tidak extra time | Brasil menang 90 menit | Probabilitas Brasil 90 menit valid |
| BTTS | Kedua tim mencetak gol | Analisis Jepang sebagai underdog berbahaya tepat |

---

## What Failed / What Was Missed

| Hal yang Meleset | Penyebab | Perbaikan untuk Prediksi Berikutnya |
|---|---|---|
| Prediksi ulang sempat mengutamakan 2-0 | Terlalu besar dampak absensi/line-up terhadap serangan Jepang | Jangan menurunkan BTTS terlalu besar hanya karena satu kreator absen |
| Detail momen penentu belum tersedia | Data belum lengkap | Tambahkan statistik post-match resmi |
| Belum ada analisis shot map/xG | Data lanjutan belum dimasukkan | Gunakan xG jika tersedia setelah laga |

---

## Parameter Adjustment Recommendation

| Parameter | Bobot Lama | Rekomendasi Bobot Baru | Alasan |
|---|---:|---:|---|
| Matchup taktis | 12% | 13% | Jepang tetap bisa mencetak gol meski underdog |
| Cedera/suspensi | 6% | 6% | Tetap, jangan dinaikkan berlebihan tanpa bukti |
| Kekuatan dasar tim | 13% | 13% | Sudah tepat |
| Kualitas serangan | 10% | 10% | Sudah tepat |
| Risiko BTTS underdog | Tidak eksplisit | Tambahkan indikator khusus | Berguna untuk laga favorit vs underdog taktis |

---

## Learning Note

1. Jika favorit unggul ranking dan Elo, prediksi pemenang bisa kuat, tetapi jangan otomatis memberi clean sheet.
2. Underdog dengan struktur taktis rapi tetap punya peluang mencetak gol, terutama lewat transisi dan set-piece.
3. Absensi satu kreator tidak selalu menghapus ancaman gol jika tim punya struktur kolektif kuat.
4. Prediksi utama 2-1 lebih seimbang dibanding prediksi ulang 2-0 karena lebih menghargai risiko Jepang.
5. Untuk fase gugur, skor tipis lebih realistis dibanding kemenangan besar, kecuali ada ketimpangan kualitas ekstrem.

---

## Rule Update

- Jika tim favorit menghadapi underdog yang punya organisasi taktik kuat dan form stabil, jangan terlalu cepat menaikkan peluang clean sheet favorit meskipun underdog kehilangan satu pemain kreatif.
- Untuk fase gugur, jika model memprediksi favorit menang tetapi underdog punya transisi kuat, skor 2-1 sering lebih rasional daripada 2-0.

---

## Kesimpulan Post-Match

Berdasarkan hasil aktual dan perbandingan dengan prediksi awal, pembelajaran utama untuk prediksi berikutnya adalah: **model sudah tepat membaca Brasil sebagai favorit dan Jepang sebagai underdog berbahaya. Untuk pertandingan berikutnya, bobot tactical resilience dan peluang BTTS underdog perlu tetap diperhatikan, terutama pada fase gugur.**
