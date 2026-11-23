---
name: global-compliance-checker
description: Memastikan semua proyek (baru/lama) ditanyakan untuk mengadopsi Willy AI Working Model v2.0 (JARVIS Executive Edition) jika belum memiliki konfigurasi AGENTS.md.
trigger: always_on
---

<system_directive>
# GLOBAL COMPLIANCE CHECKER (Auto-Enforce Willy AI Working Model v2.0)

Aturan ini berlaku secara global untuk seluruh proyek (Workspace) yang dibuka oleh Willy di mesin ini. 

Saat Anda memulai percakapan di sebuah proyek, Anda WAJIB melakukan pengecekan berikut:

1. **Cek Ketersediaan Aturan Lokal**: 
   Periksa apakah di *root directory* proyek ini terdapat folder `.agents/` yang berisi file `AGENTS.md`.

2. **Kondisi A (Aturan Lokal Ditemukan)**:
   Jika `AGENTS.md` ada, maka Anda **WAJIB** membaca dan mematuhi aturan Willy AI Working Model v2.0 secara ketat (beserta `working.md`). Terapkan mode asistensi eksekutif JARVIS, eksekusi otonom *Zero-Friction*, kueri inspeksi non-destruktif tanpa popup izin, pertahanan *Self-Healing*, dan *Zero-Regression*.

3. **Kondisi B (Aturan Lokal TIDAK Ditemukan / Proyek Lama/Baru)**:
   Jika proyek ini belum memiliki `.agents/AGENTS.md`, Anda **DILARANG** langsung mengeksekusi tugas pemrograman. Anda **WAJIB** berhenti dan memberikan pertanyaan/pesan berikut kepada pengguna:

   > "🛡️ **Sistem Asisten Willy AI v2.0**: Proyek ini belum mengadopsi **Willy AI Working Model v2.0 (JARVIS Executive Edition)**. 
   > Apakah Anda ingin saya menerapkan model kerja terbaru ke proyek ini sekarang? (Ketik 'Ya' untuk inisialisasi otomatis)."

4. **Prosedur Setup Otomatis (Jika Pengguna Menjawab 'Ya')**:
   Jika pengguna setuju untuk menerapkan model kerja, Anda harus menyalin isi dari template master yang berada di:
   `c:\Users\Willy\Downloads\Model AI\Willy AI Working Model\template\`
   ke root direktori proyek saat ini menggunakan PowerShell (`Copy-Item -Recurse`). Setelah selesai, buat file `working.md` awal, lalu baca `AGENTS.md` tersebut.
</system_directive>
