# Master Prompt Prediksi Pertandingan Piala Dunia 2026 v2.1

## Ringkasan

Repository ini berisi **Master Prompt Prediksi Pertandingan Piala Dunia 2026 v2.1** untuk membantu menganalisis dan memprediksi pertandingan sepakbola secara lebih objektif, berbasis data, dan terstruktur.

Versi v2.1 menambahkan:

> **Repository / File Generation Mode**  
> Mode khusus untuk membuat README, master prompt, examples, templates, dan paket ZIP siap pakai.

Prompt ini dirancang untuk digunakan di:

- ChatGPT
- Gemini
- Claude
- DeepSeek
- Perplexity
- AI chatbot lain yang mendukung analisis berbasis prompt panjang

---

## Tujuan Prompt

Prompt ini dibuat agar prediksi pertandingan tidak hanya berdasarkan opini, fanatisme, atau nama besar tim, tetapi menggunakan pendekatan:

1. Data pertandingan terakhir
2. Ranking FIFA
3. Elo rating
4. Statistik performa
5. Head-to-head
6. Cedera dan suspensi
7. Prediksi atau line-up resmi
8. Analisis taktis
9. Konteks turnamen
10. Faktor eksternal
11. Model skor berbobot
12. Probabilitas hasil
13. Risiko prediksi
14. Evaluasi pasca-pertandingan
15. Dokumentasi repository

---

## Fitur Utama

### 1. Pre-Match Prediction

Digunakan sebelum pertandingan dimulai.

Output utama:

- Prediksi pemenang
- Prediksi skor utama
- Alternatif skor
- Probabilitas menang/seri/kalah
- Peluang lolos untuk fase gugur
- Risiko yang bisa membuat prediksi salah
- Confidence level

---

### 2. Line-Up Update Prediction

Digunakan setelah line-up resmi keluar.

Fungsi:

- Memperbarui prediksi berdasarkan starting XI
- Menilai absensi pemain inti
- Mengevaluasi perubahan formasi
- Menyesuaikan probabilitas dan prediksi skor

---

### 3. Live Context Adjustment

Digunakan saat pertandingan sedang berjalan.

Fungsi:

- Membaca momentum pertandingan
- Menilai dampak gol cepat
- Menilai kartu merah, cedera, VAR, penalti
- Memperbarui probabilitas secara dinamis

---

### 4. Post-Match Learning

Digunakan setelah pertandingan selesai.

Fungsi:

- Membandingkan prediksi vs hasil aktual
- Mengukur skor akurasi prediksi
- Menilai apakah probabilitas terlalu tinggi atau rendah
- Menganalisis penyebab prediksi benar atau salah
- Memberikan rekomendasi penyesuaian bobot
- Membuat learning note untuk prediksi berikutnya

---

### 5. Repository / File Generation Mode

Digunakan jika ingin membuat paket dokumentasi siap pakai.

Fungsi:

- Membuat README
- Membuat master prompt
- Membuat contoh penggunaan
- Membuat template input
- Membuat struktur folder
- Membuat ZIP repository jika tool mendukung

---

## Struktur Folder

```text
world-cup-prediction-prompt/
├── README.md
├── master-prompt-prediksi-piala-dunia-2026-v2.1.md
├── examples/
│   ├── pre-match-brasil-vs-jepang.md
│   ├── line-up-update-brasil-vs-jepang.md
│   └── post-match-learning-brasil-vs-jepang.md
└── templates/
    ├── input-prediksi.md
    └── input-post-match-learning.md
```

---

## Penjelasan Isi File

| File | Fungsi |
|---|---|
| `README.md` | Panduan penggunaan repository |
| `master-prompt-prediksi-piala-dunia-2026-v2.1.md` | Master prompt utama versi 2.1 |
| `examples/pre-match-brasil-vs-jepang.md` | Contoh prediksi sebelum pertandingan |
| `examples/line-up-update-brasil-vs-jepang.md` | Contoh update setelah line-up resmi |
| `examples/post-match-learning-brasil-vs-jepang.md` | Contoh evaluasi setelah pertandingan |
| `templates/input-prediksi.md` | Template kosong untuk prediksi baru |
| `templates/input-post-match-learning.md` | Template kosong untuk evaluasi post-match |

---

## Cara Penggunaan Cepat

### Langkah 1 — Copy Master Prompt

Buka file:

```text
master-prompt-prediksi-piala-dunia-2026-v2.1.md
```

Copy seluruh isi prompt.

---

### Langkah 2 — Paste ke AI Chatbot

Paste prompt ke ChatGPT, Gemini, Claude, DeepSeek, Perplexity, atau AI lain.

Agar hasil lebih baik, gunakan model yang mendukung:

- Web search / browsing
- Analisis data panjang
- Pemahaman tabel
- Reasoning kompleks
- Sitasi sumber

---

### Langkah 3 — Masukkan Data Pertandingan

Gunakan format berikut:

```markdown
Prediksi pertandingan:

- Kompetisi: Piala Dunia
- Tahun: 2026
- Fase: Round of 32
- Tim A: Brasil
- Tim B: Jepang
- Tanggal: 30 Juni 2026
- Lokasi: Houston Stadium, Houston, USA
- Zona waktu analisis: Asia/Jakarta
- Mode analisis: Pre-Match
- Catatan tambahan: prioritaskan data pertandingan terakhir, ranking, Elo, cedera, line-up, dan analisis taktis
```

---

## Template Input Pre-Match

```markdown
Prediksi pertandingan:

- Kompetisi:
- Tahun:
- Fase:
- Tim A:
- Tim B:
- Tanggal:
- Lokasi:
- Zona waktu analisis:
- Mode analisis: Pre-Match
- Catatan tambahan:
```

---

## Template Input Line-Up Update

```markdown
Update prediksi berdasarkan line-up resmi:

- Kompetisi:
- Tahun:
- Fase:
- Tim A:
- Tim B:
- Prediksi awal:
- Line-up resmi Tim A:
- Line-up resmi Tim B:
- Pemain absen:
- Catatan tambahan:
```

---

## Template Input Live Adjustment

```markdown
Update prediksi live:

- Kompetisi:
- Tahun:
- Fase:
- Tim A:
- Tim B:
- Menit pertandingan:
- Skor sementara:
- Kartu merah:
- Cedera penting:
- Statistik sementara:
- Momentum pertandingan:
- Catatan tambahan:
```

---

## Template Input Post-Match Learning

```markdown
Evaluasi post-match:

- Kompetisi:
- Tahun:
- Fase:
- Tim A:
- Tim B:
- Prediksi awal:
- Prediksi alternatif:
- Probabilitas awal:
- Hasil aktual:
- Skor akhir:
- Pemenang:
- Gol:
- Kartu merah:
- Momen penentu:
- Statistik utama:
- Catatan tambahan:
```

---

## Template Input Repository / File Generation

```markdown
Buatkan paket repository Master Prompt Prediksi Piala Dunia 2026.

- Versi: 2.1
- Nama folder: world-cup-prediction-prompt
- Format file: Markdown
- File yang harus dibuat:
  - README.md
  - master-prompt-prediksi-piala-dunia-2026-v2.1.md
  - examples/pre-match-brasil-vs-jepang.md
  - examples/line-up-update-brasil-vs-jepang.md
  - examples/post-match-learning-brasil-vs-jepang.md
  - templates/input-prediksi.md
  - templates/input-post-match-learning.md
- Output:
  - Tampilkan struktur folder
  - Buatkan file
  - Jika memungkinkan, buat ZIP
```

---

## Rekomendasi Penggunaan di ChatGPT

1. Aktifkan web search jika tersedia.
2. Paste Master Prompt v2.1.
3. Masukkan data pertandingan.
4. Minta AI menampilkan:
   - Data faktual
   - Prediksi
   - Probabilitas
   - Risiko
   - Confidence level
5. Setelah pertandingan selesai, gunakan mode Post-Match Learning.
6. Jika ingin membuat paket file, gunakan Repository / File Generation Mode.

---

## Rekomendasi Penggunaan di Gemini

1. Paste Master Prompt v2.1.
2. Minta Gemini melakukan validasi data terbaru.
3. Jika Gemini memberikan data tanpa sumber, minta ulang dengan format:

```markdown
Tampilkan sumber untuk setiap data penting.
Jika data tidak tersedia, tulis "data tidak tersedia / belum terverifikasi".
```

4. Gunakan mode Post-Match Learning setelah hasil pertandingan tersedia.

---

## Rekomendasi Penggunaan di Claude

Claude cocok untuk analisis panjang dan struktur taktis.

Gunakan instruksi tambahan:

```markdown
Jawab dengan struktur lengkap, tabel, dan pisahkan data faktual dari interpretasi.
Jangan ringkas berlebihan.
Gunakan Post-Match Learning jika hasil pertandingan sudah tersedia.
```

---

## Rekomendasi Penggunaan di DeepSeek

DeepSeek dapat digunakan untuk analisis cepat dan perbandingan numerik.

Agar lebih stabil, gunakan instruksi:

```markdown
Ikuti format secara ketat.
Jangan mengarang data.
Jika tidak ada data valid, tulis "data tidak tersedia / belum terverifikasi".
```

---

## Output yang Diharapkan

Untuk Pre-Match Prediction:

```markdown
# Prediksi Akhir: Tim A vs Tim B

## Ringkasan Data Utama
## Tabel Skor Berbobot
## Probabilitas
## Prediksi Skor
## Faktor Penentu
## Risiko Prediksi
## Confidence Level
## Kesimpulan
```

Untuk Post-Match Learning:

```markdown
# Post-Match Learning: Tim A vs Tim B

## Hasil Aktual
## Evaluasi Prediksi
## Skor Akurasi
## Calibration Review
## Error Attribution
## What Worked
## What Failed
## Rekomendasi Model Berikutnya
## Learning Note
## Kesimpulan Post-Match
```

---

## Prinsip Anti-Halusinasi

1. Jangan mengarang statistik.
2. Jangan menyebut data tanpa sumber.
3. Jika data cedera belum pasti, tulis "belum terkonfirmasi".
4. Jika line-up belum resmi, tulis "prediksi line-up".
5. Jangan menggunakan kata "pasti menang".
6. Gunakan istilah "probabilitas", "peluang", "indikasi", dan "skenario".
7. Cantumkan tanggal data terakhir diperiksa.
8. Pisahkan data faktual dan interpretasi.
9. Jika sumber berbeda, jelaskan sumber mana yang lebih dipercaya.
10. Jangan menyesuaikan prediksi setelah hasil diketahui tanpa menandainya sebagai Post-Match Learning.
11. Jika hanya memberi struktur folder, jangan mengklaim file sudah dibuat.
12. Jika membuat examples/templates, isi file harus konsisten dengan master prompt.

---

## Contoh Workflow Lengkap

```text
1. Sebelum pertandingan
   Gunakan Pre-Match Prediction.

2. Setelah line-up keluar
   Gunakan Line-Up Update Prediction.

3. Jika pertandingan berjalan
   Gunakan Live Context Adjustment.

4. Setelah pertandingan selesai
   Gunakan Post-Match Learning.

5. Simpan learning note
   Gunakan untuk memperbaiki prediksi pertandingan berikutnya.

6. Jika ingin paket dokumentasi
   Gunakan Repository / File Generation Mode.
```

---

## Changelog

### v2.1

Penambahan:

- Repository / File Generation Mode
- Instruksi eksplisit membuat README
- Instruksi eksplisit membuat folder `examples/`
- Instruksi eksplisit membuat folder `templates/`
- Instruksi eksplisit membuat 5 file pendukung
- Template input untuk pembuatan repository
- Aturan anti-halusinasi khusus file generation
- Penjelasan bahwa struktur folder rekomendasi belum berarti file sudah dibuat

### v2.0

Penambahan:

- Mode Post-Match Learning
- Calibration Review
- Error Attribution
- What Worked / What Failed
- Parameter Adjustment Recommendation
- Learning Note
- Rule Update
- Template input evaluasi pasca-pertandingan

### v1.0

Fitur awal:

- Pre-match prediction
- Data pertandingan terakhir
- Ranking FIFA
- Elo rating
- Cedera dan suspensi
- Line-up
- Analisis taktis
- Model skor berbobot
- Probabilitas
- Confidence level

---

## Lisensi Penggunaan

Dokumen ini dapat digunakan, dimodifikasi, dan dikembangkan untuk kebutuhan edukasi, analisis sepakbola, riset pribadi, atau pengembangan sistem prediksi internal.

Tidak disarankan digunakan sebagai satu-satunya dasar untuk keputusan finansial, taruhan, atau aktivitas berisiko tinggi.

---

## Penutup

Master Prompt Prediksi Pertandingan Piala Dunia 2026 v2.1 dirancang sebagai sistem analisis berulang:

```text
Data → Prediksi → Hasil Aktual → Evaluasi → Learning → Dokumentasi → Prediksi Lebih Baik
```

Dengan pendekatan ini, setiap pertandingan menjadi bahan pembelajaran untuk meningkatkan kualitas analisis berikutnya.
