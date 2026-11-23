# Willy AI Working Model v2.0 (JARVIS Executive Edition)

**Willy AI Working Model (v2.0 — Rilis Resmi: 23 November 2026)** | Executive AI Assistant, Autonomous Software Engineering Engine & High-Assurance Architecture

[![User](https://img.shields.io/badge/maintainer-Willy-blue)](https://github.com/Wilyssssss/Model-Kerja-AI-Willy)
[![Version](https://img.shields.io/badge/version-2.0%20JARVIS%20Edition-brightgreen)](https://github.com/Wilyssssss/Model-Kerja-AI-Willy)
[![License](https://img.shields.io/badge/license-Permissive%20with%20Disclaimer-orange)](LICENSE)
[![Engine](https://img.shields.io/badge/engine-Gemini%204%20Argon%20%7C%20Claude%20Opus%2FSonnet-purple)]()
[![Platform](https://img.shields.io/badge/platform-Google%20Antigravity%202.0-blueviolet)]()

---

## 📘 Dokumentasi & Panduan Cepat
- 👉 **[Kitab Panduan Pemula Willy AI v2.0 (Edisi Lengkap Ramah Pemula)](PANDUAN_PEMULA_WILLY_AI_V2.md)**
- 👉 **[Lisensi & Ketentuan Pelepasan Tanggung Jawab](LICENSE)**
- 👉 **[Konstitusi Runtime Agen (`AGENTS.md`)](AGENTS.md)**

---

## 🤖 Apa itu Willy AI Working Model v2.0?

**Willy AI Working Model v2.0** adalah sistem tata kelola model kerja otonom mandiri dan asisten eksekutif cerdas (**JARVIS-Class**) yang dirancang khusus untuk memandu agen kecerdasan buatan (Google Antigravity, Gemini, Claude, OpenRouter) dalam rekayasa perangkat lunak produksi dan riset tingkat lanjut.

Framework ini menyelesaikan 4 masalah kronis AI bawaan:
1. **Pikun Konteks (*Context Drift*)** $\rightarrow$ Diselesaikan dengan Memori Gajah (`working.md` & `task.md`).
2. **Merusak Fitur Lama (*Regression*)** $\rightarrow$ Diselesaikan dengan *Anti-Regression Boundaries* & *Smallest Complete Change*.
3. **Kode Malas & UI Kasar (*AI Slop*)** $\rightarrow$ Dilarang keras memakai placeholder malas; wajib UI responsif sentuhan minimal 48×48px.
4. **Klaim Palsu (*Hallucination*)** $\rightarrow$ Diselesaikan dengan *Evidence Verification Gate* (wajib bukti uji CLI keluaran `0 error`).

---

## ⚡ Pembaruan Utama Versi 2.0 (23 November 2026):

1. **Identitas Mandiri Penuh**:
   - Beroperasi resmi di bawah identitas mandiri **Willy AI**.
   - Model-model terdahulu (seperti Willy AI Framework, PICO v4.2, dan PIOM-SDCM) diposisikan secara terhormat sebagai **fondasi acuan pengembangan historis**, sementara model kerja aktif 100% independen di bawah nama **Willy**.
2. **Mode Asisten Eksekutif JARVIS (`willy-jarvis`)**:
   - Persona komunikatif yang taktis, sopan, proaktif, dan lugas (*executive brevity*).
   - Fitur **Executive Briefing** (`willy briefing` / `willy jarvis`): Langsung merangkum kesehatan Git, fokus misi aktif, radar risiko keamanan, dan 2 opsi langkah berikutnya.
   - Fitur **Perencanaan Taktis** (`willy plan`): Otomatis menyusun peta jalan arsitektur sebelum koding dimulai.
3. **Dukungan Perintah Cepat Dua Awalan (Dual-Prefix)**:
   - Mendukung penuh awalan modern **`willy <perintah>`** maupun awalan klasik **`Willy AI <perintah>`** secara mulus tanpa benturan.
4. **Audit Kode Otomatis & Penilaian Skor PR (`willy review`)**:
   - Pemeriksaan menyeluruh 5 dimensi (Keamanan data, Anti-Slop, Arsitektur MVC, Error Handling, UI HP) dengan skor 0–100.
5. **Pembersihan Bloat & Optimasi Token Konteks**:
   - Menghapus redundansi instruksi yang membebani token window.
   - Path dan repositori disinkronkan langsung ke repo resmi: `https://github.com/Wilyssssss/Model-Kerja-AI-Willy`.

---

## 🎮 Matriks Perintah Eksekutif Willy AI v2.0

| Perintah Modern | Perintah Klasik | Fungsi & Tindakan Otomatis AI |
|---|---|---|
| **`willy jarvis`** / **`willy briefing`** | `Willy AI status` | **Executive Briefing**: Sajikan status menyeluruh sistem (Git, task, keamanan, rekomendasi taktis). |
| **`willy run`** `[tugas]` | `Willy AI run` `[tugas]` | **Eksekusi Otonom**: Lanjutkan task aktif atau eksekusi tugas baru dengan prinsip perubahan terkecil. |
| **`willy review`** `[file]` | `Willy AI review` `[file]` | **Audit Kode Senior**: Periksa `git diff` dan berikan skor kualitas 0–100 beserta saran perbaikan baris demi baris. |
| **`willy fix`** `[error]` | `Willy AI fix` `[error]` | **Self-Healing Loop**: Analisis log error, perbaiki akar masalah secara presisi, dan uji ulang sampai tuntas. |
| **`willy test`** | `Willy AI test` | **Gerbang Verifikasi**: Jalankan pengujian sintaks CLI (`php -l` dll.) pada sesi aktif dan tampilkan buktinya. |
| **`willy health`** | `Willy AI health` | **Medical Check-up Proyek**: Tes sintaks + scan anti-bocor password + kebersihan berkas sampah. |
| **`willy plan`** `[ide]` | `Willy AI plan` `[ide]` | **Perencanaan Arsitektur**: Pecah ide besar menjadi sub-langkah aman tanpa merusak sistem eksisting. |
| **`willy changelog`** | `Willy AI changelog` | **Auto-Changelog**: Susun berkas `CHANGELOG.md` otomatis dari histori komit Git. |
| **`willy sync`** | `Willy AI sync` | **Sinkronisasi Memori**: Perbarui status `working.md` dan `task.md` tanpa membuat file ZIP baru. |
| **`willy pack`** | `Willy AI pack` | **Pengepakan Rilis Bersih**: Kemas file ZIP rilis produksi via `build_upload.ps1` dan catat hash SHA256. |
| **`willy assist`** `[kebutuhan]` | `Willy AI kajian` `[topik]` | **Konsultasi Khusus**: Diskusi strategi arsitektur, riset ilmiah, atau kajian lintas-agen. |

---

## 🏗️ Struktur Modular Repositori

```text
Willy AI Working Model/
├── AGENTS.md                          # Konstitusi runtime resmi (v2.0 JARVIS Edition)
├── README.md                          # Dokumentasi publik resmi repositori
├── LICENSE                            # Lisensi pemakaian bebas dengan pelepasan tanggung jawab
├── PANDUAN_PEMULA_WILLY_AI_V2.md      # Kitab panduan lengkap ramah pemula (Bahasa Manusia)
├── task.md                            # Papan tugas aktif & antrian pengerjaan
├── rules/                             # Konstitusi AI global (always_on)
│   ├── willy-global.md                 # Konstitusi inti Willy AI v2.0
│   └── pico.md                        # Aturan jembatan kolaborasi tamu
├── skills/                            # Kemampuan on-demand
│   ├── willy-jarvis/SKILL.md          # Mode Asisten Eksekutif Cerdas (JARVIS Engine)
│   ├── willy-shortcuts/SKILL.md        # Engine pintasan perintah willy / Willy AI
│   ├── willy-review/SKILL.md           # Senior Code Reviewer otomatis (0-100 poin)
│   └── pico/                          # Standar penulisan ilmiah & format riset akademik
├── template/                          # Template perancah instan untuk proyek baru
│   ├── .agents/AGENTS.md              # Aturan lokal proyek baru
│   ├── working.md                     # Memori state anti-pikun
│   ├── build_upload.ps1               # Pembersih & pembuat paket ZIP rilis live
│   └── RELEASE_MANIFEST.md            # Ledger rilis SHA256 & rollback plan
└── .github/workflows/ci.yml           # Pipeline CI otomatis (Linting + Security Scan)
```

---

## 🏛️ Fondasi & Warisan Arsitektur (Heritage)
Willy AI Working Model v2.0 dibangun dengan mengasimilasi dan menyempurnakan prinsip-prinsip terbaik dari berbagai disiplin engineering:
- **Willy AI Framework & PIOM-SDCM v0.9**: Fondasi pemisahan otorisasi *GATE_CHECK* vs *OWNER GO* dan arsitektur rilis bersih.
- **PICO v4.2 Protocol**: Protokol diplomasi dan pertukaran paket kajian ilmiah lintas-model AI (Claude, Antigravity, ChatGPT).
- **Superpowers (obra) & Karpathy Principles**: Disiplin gerbang verifikasi berbasis bukti nyata dan perubahan terkecil (*Smallest Complete Change*).
- **Unslop Engineering**: Standar penulisan kode tuntas tanpa komentar malas dan antarmuka bersih responsif.

---
*Dikelola dan dikembangkan secara resmi oleh **Willy** — Repositori Resmi: [https://github.com/Wilyssssss/Model-Kerja-AI-Willy](https://github.com/Wilyssssss/Model-Kerja-AI-Willy)*
