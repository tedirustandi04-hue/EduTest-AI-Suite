# EduTest AI Suite (Fase 1 - Fase 5)

Platform Asesmen Pendidikan Terpadu berbasis AI (Gemini API), Simulasi Ujian CBT, dan Analisis Psikometri (Classical Test Theory / KR-20).

## Arsitektur Fase
- **Fase 1:** Foundation, Auth, Identitas Sekolah/Guru, Kurikulum CP/TP, Sistem Lisensi.
- **Fase 2:** AI Assessment Generator (Gemini API), Bank Soal, Kisi-kisi, Kartu Soal, Rubrik, Ekspor Word & PDF.
- **Fase 3:** Exam Simulator (CBT), Manajemen Kelas/Siswa, Kode Akses, Penilaian Otomatis.
- **Fase 4:** Analytics & CTT (Impor Excel/CSV, Statistik, KKTP, Remedial, KR-20, Tingkat Kesukaran, Daya Pembeda, Analisis Pengecoh).
- **Fase 5:** Production & Deployment (PWA Offline Sync, Keamanan, Backup DB, CI/CD GitHub Actions).

## Cara Instalasi Lokal
1. Salin `.env.example` menjadi `.env` dan isi kredensial Anda.
2. Jalankan database PostgreSQL: `docker-compose up -d`
3. Install dependencies: `npm install`
4. Sinkronisasi skema database: `npx prisma db push`
5. Jalankan server pengembangan: `npm run dev`
