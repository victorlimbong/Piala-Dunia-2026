# PROMPT PREDIKSI PERTANDINGAN PIALA DUNIA 2026

README singkat ini menjelaskan cara menggunakan **Master Prompt Prediksi Pertandingan Piala Dunia** untuk menganalisis pertandingan secara objektif, berbasis data valid, dan tidak mengarang statistik.
Prompt ini dibuat untuk hiburan semata, bukan prediksi valid untuk menentukan pemenang sebuah pertandingan.
---

## Tujuan

Master Prompt ini digunakan untuk memprediksi pertandingan Piala Dunia dengan mempertimbangkan:

* Jadwal dan status resmi pertandingan
* Data 5–10 pertandingan terakhir
* FIFA Ranking
* Elo Rating
* Head-to-head
* Performa serangan dan pertahanan
* xG / xGA jika tersedia
* Cedera dan suspensi
* Prediksi line-up atau line-up resmi
* Analisis taktik
* Konteks fase grup atau knockout
* Probabilitas menang, seri, kalah, atau lolos
* Prediksi skor dan confidence level

---

## Sumber Data yang Direkomendasikan

Gunakan sumber data yang valid dan bisa dipercaya:

* FIFA
* FIFA World Ranking
* World Football Elo Ratings
* FBref
* Opta / Stats Perform
* FotMob
* Sofascore
* ESPN
* BBC Sport
* Reuters
* AP News
* Situs resmi federasi sepakbola nasional

Hindari menggunakan rumor media sosial, prediksi fans, atau data tanpa sumber yang jelas.

---

## Cara Penggunaan di ChatGPT

1. Buka ChatGPT.
2. Aktifkan mode pencarian web jika tersedia.
3. Salin dan tempel **Master Prompt Prediksi Pertandingan Piala Dunia**.
4. Isi data pertandingan, misalnya:

```markdown
Kompetisi: Piala Dunia 2026
Fase: Round of 32
Tim A: Brasil
Tim B: Jepang
Tanggal: 29 Juni 2026
Lokasi: [isi stadion jika tersedia]
```

5. Tambahkan instruksi:

```markdown
Gunakan data terbaru dari sumber resmi dan terpercaya.
Masukkan 5–10 pertandingan terakhir masing-masing tim.
Jangan mengarang data. Jika data tidak tersedia, tulis "data belum terverifikasi".
```

6. Jalankan prompt.
7. Periksa ulang hasil prediksi, terutama bagian cedera, line-up, dan sumber data.

---

## Cara Penggunaan di Gemini

1. Buka Gemini.
2. Tempel Master Prompt ke kolom chat.
3. Aktifkan pencarian atau koneksi ke data terbaru jika tersedia.
4. Jika memiliki file data pertandingan, upload file tersebut.
5. Masukkan data pertandingan yang ingin dianalisis.
6. Minta Gemini menampilkan hasil dalam format tabel.

Contoh tambahan instruksi:

```markdown
Tampilkan data pertandingan terakhir dalam tabel.
Pisahkan fakta, analisis, dan prediksi.
Cantumkan tanggal data terakhir diperiksa.
```

---

## Cara Penggunaan di DeepSeek

### Melalui Web Chat

1. Buka DeepSeek Chat.
2. Tempel Master Prompt.
3. Isi Tim A, Tim B, fase, tanggal, dan lokasi.
4. Jika DeepSeek tidak memiliki akses data terbaru, berikan data pertandingan terakhir secara manual.
5. Minta output ringkas atau lengkap sesuai kebutuhan.

Contoh:

```markdown
Gunakan data berikut sebagai input utama.
Jika ada data yang kurang, beri label "data tidak tersedia".
Jangan membuat asumsi tanpa penjelasan.
```

### Melalui API

Gunakan struktur:

```json
{
  "role": "user",
  "content": "Tempel Master Prompt di sini, lalu isi data pertandingan."
}
```

Jika menggunakan API multi-turn, sertakan kembali konteks penting pada request berikutnya agar analisis tetap konsisten.

---

## Cara Penggunaan di Claude, Copilot, Perplexity, dan AI Lainnya

1. Tempel Master Prompt.
2. Berikan nama kedua tim.
3. Berikan fase pertandingan.
4. Minta AI menggunakan data terbaru.
5. Jika AI tidak bisa browsing, masukkan sendiri data pertandingan terakhir.
6. Minta output dalam format:

```markdown
1. Ringkasan pertandingan
2. Data 5–10 pertandingan terakhir
3. Analisis ranking dan Elo
4. Analisis taktik
5. Cedera dan suspensi
6. Skor berbobot
7. Probabilitas
8. Prediksi skor
9. Risiko prediksi
10. Confidence level
```

---

## Format Input Cepat

Gunakan template ini setiap kali ingin memprediksi pertandingan:

```markdown
Prediksi pertandingan Piala Dunia berikut:

Kompetisi:
Fase:
Tim A:
Tim B:
Tanggal:
Stadion / Kota:
Zona waktu:

Instruksi:
- Gunakan sumber valid dan terbaru.
- Masukkan 5–10 pertandingan terakhir masing-masing tim.
- Gunakan FIFA Ranking, Elo Rating, form terakhir, cedera, suspensi, dan analisis taktik.
- Buat tabel skor berbobot.
- Berikan probabilitas menang, seri, kalah.
- Jika fase gugur, berikan probabilitas lolos.
- Berikan prediksi skor utama dan alternatif.
- Jangan mengarang data.
```

---

## Contoh Penggunaan

```markdown
Prediksi pertandingan Piala Dunia berikut:

Kompetisi: Piala Dunia 2026
Fase: Round of 32
Tim A: Brasil
Tim B: Jepang
Tanggal: 29 Juni 2026
Stadion / Kota: [isi jika tersedia]
Zona waktu: Asia/Jakarta

Gunakan Master Prompt Prediksi Pertandingan Piala Dunia.

Wajib masukkan:
- 10 pertandingan terakhir Brasil
- 10 pertandingan terakhir Jepang
- Ranking FIFA terbaru
- Elo Rating terbaru
- Cedera dan suspensi terbaru
- Analisis taktik
- Prediksi skor
- Confidence level
```

---

## Checklist Sebelum Prediksi

Sebelum menerima hasil prediksi, pastikan AI sudah menampilkan:

* [ ] Jadwal resmi pertandingan
* [ ] Data pertandingan terakhir kedua tim
* [ ] Ranking FIFA
* [ ] Elo Rating
* [ ] Head-to-head
* [ ] Cedera dan suspensi
* [ ] Prediksi line-up atau line-up resmi
* [ ] Analisis taktik
* [ ] Tabel skor berbobot
* [ ] Probabilitas
* [ ] Prediksi skor
* [ ] Risiko prediksi
* [ ] Confidence level
* [ ] Sumber data

---

## Catatan Penting

Prediksi sepakbola adalah estimasi probabilitas, bukan kepastian.

Gunakan istilah:

* Peluang
* Probabilitas
* Indikasi
* Skenario
* Confidence level

Hindari istilah:

* Pasti menang
* Fix menang
* Jaminan hasil
* Tidak mungkin kalah

---

## Rekomendasi Praktis

Untuk hasil terbaik:

1. Jalankan prompt 24 jam sebelum pertandingan.
2. Jalankan ulang 1–2 jam sebelum kick-off.
3. Perbarui data line-up, cedera, suspensi, dan cuaca.
4. Bandingkan hasil dari minimal dua AI.
5. Gunakan hasil sebagai analisis, bukan sebagai kepastian.
