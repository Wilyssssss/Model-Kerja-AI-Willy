---
name: willy-shortcuts
description: >-
  Mendeteksi dan mengeksekusi pintasan instruksi cepat Willy AI Working Model v2.0 (JARVIS Edition).
  Mendukung awalan perintah "willy" maupun "Willy AI": willy/Willy AI run, fix, test, status, review, health, changelog, sync, pack, briefing.
  Picu saat pengguna mengetik instruksi singkat seperti "willy", "Willy AI", "willy run", "willy review", "willy briefing", "lanjutkan", dll.
---

# ⚡ Willy AI v2.0 Shortcuts & Semi-Autonomous Command Engine
*Berlaku Efektif: 23 November 2026 — Willy AI Working Model v2.0 (JARVIS Edition)*

Dokumen ini memetakan kata kunci pintasan eksekutif menjadi tindakan teknis otonom penuh berdasarkan pedoman **Willy AI Working Model v2.0**.

> **PROTOKOL IDENTITAS RESMI:**
> - **Header**: `> 🛡️ **Willy AI v2.0 (JARVIS Edition)** | **Executive Assistant & Autonomous Engine** | Mode: Active`
> - **Footer**: `⚡ **Willy AI v2.0 Active** · **Verifikasi:** <Lolos/Sebagian/Belum/N/A> · **Wadah:** <Proyek> · **Status:** <Status>`

---

## ⚡ Pemetaan Pintasan Perintah Eksekutif (Dual-Prefix: `willy` / `Willy AI`)

| Perintah Modern (`willy`) | Perintah Klasik (`Willy AI`) | Makna & Tindakan Otonom AI |
|---|---|---|
| **`willy jarvis`** / **`willy briefing`** | `Willy AI status` | **Executive Briefing**: Sajikan dashboard komprehensif sistem (Git, task aktif, radar keamanan, dan rekomendasi langkah). |
| **`willy run`** `[tugas]` | `Willy AI run` `[tugas]` | **Eksekusi Otonom**: Lanjutkan task aktif di `.agents/task.md` atau eksekusi fitur baru dengan prinsip *Smallest Complete Change* dan *Anti-Slop*. |
| **`willy review`** `[file]` | `Willy AI review` `[file]` | **Audit Kode Senior**: Tinjau `git diff` terhadap 5 dimensi (Keamanan, Anti-Slop, MVC, Error Handling, UI) dan berikan skor 0–100. |
| **`willy fix`** `[error]` | `Willy AI fix` `[error]` | **Self-Healing Loop**: Analisis log error, perbaiki akar masalah secara presisi, lalu uji ulang hingga sembuh total. |
| **`willy test`** | `Willy AI test` | **Gerbang Verifikasi**: Jalankan tes sintaks CLI (`php -l`, `tsc`, dll.) pada sesi aktif dan lampirkan bukti keluaran `0 error`. |
| **`willy health`** | `Willy AI health` | **Medical Check-up Menyeluruh**: Gabungan tes sintaks + scan Zero-Leakage (kebocoran password/.env) + kebersihan direktori. |
| **`willy plan`** `[ide]` | `Willy AI plan` `[ide]` | **Perencanaan Taktis**: Susun cetak biru arsitektur dan langkah implementasi terstruktur ke dalam `task.md`. |
| **`willy changelog`** | `Willy AI changelog` | **Auto-Changelog**: Susun berkas `CHANGELOG.md` resmi dari riwayat komit Git secara otomatis. |
| **`willy sync`** | `Willy AI sync` | **Sinkronisasi Memori**: Perbarui status di `working.md` dan `task.md` sesuai kondisi commit terbaru tanpa buat ZIP. |
| **`willy pack`** | `Willy AI pack` | **Pengepakan Rilis Live**: Jalankan `build_upload.ps1` untuk membungkus ZIP rilis bersih dan catat hash SHA256 di `RELEASE_MANIFEST.md`. |
| **`willy assist`** `[topik]` | `Willy AI kajian` `[topik]` | **Konsultasi & Kajian**: Memberikan analisis mendalam, perancangan skema, atau format kajian silang. |
