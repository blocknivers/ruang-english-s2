# Ruang English — Road to Master's Abroad

Website belajar bahasa Inggris statis, siap di-host di Netlify, untuk pelajar yang mulai dari A1 dan ingin mempersiapkan IELTS Academic atau TOEFL iBT versi 2026.

## Isi

- 60 modul (12 A1 + 12 A2 + 12 B1 + 12 B2 + 12 C1) dengan penjelasan bahasa Indonesia, pola, contoh, pronunciation browser, vocabulary, kuis, dan pembahasan.
- Kurikulum A1 memuat materi lebih terperinci; modul A2–C1 adalah fondasi topikal dan perlu dilengkapi latihan lebih lanjut untuk penguasaan penuh setiap level.
- Reading: 2 teks dengan total 6 soal. Listening: 2 audio berbasis browser text-to-speech dan total 6 soal.
- Writing Workshop: 6 latihan termasuk gaya IELTS Academic Writing 1/2 dan TOEFL iBT 2026 Write an Email / Academic Discussion.
- Speaking Studio: 7 prompt termasuk gaya IELTS dan TOEFL 2026. Transkripsi browser opsional, bukan skor pelafalan.
- Mini mock: 8 soal / 10 menit per format. Latihan parsial, bukan simulasi lengkap, adaptif, atau prediksi skor.
- Study planner, progress dashboard, flashcards, writing journal, eksport/import JSON.

## Deploy ke Netlify (gratis)

1. Ekstrak file ZIP.
2. Masuk ke https://app.netlify.com/drop .
3. Seret folder `ruang-english-s2` (yang memuat `index.html`) ke Netlify Drop.
4. Buka URL `.netlify.app` yang disediakan Netlify.
5. Tidak ada npm install, build, API key, atau server yang diperlukan.

## Privasi dan teknis

Data tersimpan di `localStorage` per browser/perangkat. Gunakan Pengaturan → Ekspor data JSON untuk backup, dan Impor di perangkat lain. Browser speech synthesis dan speech recognition mungkin berbeda antar-browser; fitur transkripsi mungkin memerlukan HTTPS dan izin mikrofon. TTS menggunakan suara sintetis sistem/browser, bukan rekaman native speaker resmi. Tidak ada akun, database, sinkronisasi otomatis, analisis AI, atau penilaian IELTS/TOEFL tervalidasi.

## Sumber resmi untuk format dan persiapan ujian (diverifikasi November 2026)

IELTS Academic: https://ielts.org/take-a-test/test-types/ielts-academic-test

IELTS official sample: https://ielts.org/take-a-test/preparation-resources/sample-test-questions/academic-test

TOEFL iBT updated format: https://www.ets.org/toefl/test-takers/ibt/about/content.html?version=after-jan-2026

TOEFL official preparation: https://www.ets.org/toefl/test-takers/ibt/prepare.html

Penting: TOEFL iBT memakai format dan skala skor baru mulai 21 Januari 2026. Syarat tiap program S2/beasiswa dapat berbeda; cek ketentuan universitas tujuan, minimum keseluruhan dan minimum per skill, serta persyaratan tes yang diterima.

## Cara mengubah konten

- `lessons-a1.js`: 12 modul A1 dan soal.
- `advanced.js`: 48 modul A2–C1 dan soal.
- `app.js`: layout dinamis, latihan keterampilan, simulasi, planner, dan penyimpanan.
- `style.css`: tema visual.
- `index.html`: kerangka navigasi.

Semua materi latihan merupakan materi orisinal yang dibuat untuk pembelajaran mandiri, bukan konten atau soal resmi penyelenggara tes.
