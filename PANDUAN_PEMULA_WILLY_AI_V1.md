# 📘 Kitab Panduan Lengkap Pemula: Mengenal, Memakai & Mengembangkan Willy AI Working Model v1.0

> *Dokumentasi Resmi & Rujukan Pengembangan Masa Depan — Edisi Bahasa Manusia (Ramah Pemula)*  
> **Versi:** 1.0 (Rilis Perdana: 20 November 2026)  
> **Pencipta / Maintainer:** Willy  

---

## 🌟 1. Pengantar Paling Dasar: Mengapa Kita Butuh Model Kerja Ini?

Bayangkan Anda mempekerjakan seorang **asisten robot super jenius** (itulah AI seperti Claude, Gemini, atau ChatGPT). Robot ini bisa mengetik ribuan baris kode pemrograman dalam hitungan detik.

Namun, robot ini memiliki **4 sifat buruk alami**:
1. **Pikun Akut (*Context Drift*)**: Kalau percakapan sudah panjang atau Anda menutup aplikasi dan membukanya besok, dia lupa kemarin sedang mengerjakan apa. Akibatnya dia mengulang dari nol atau membuat kode yang bertabrakan.
2. **Sok Tahu & Ceroboh (*Halusinasi*)**: Seringkali dia mengedit file konfigurasi database penting atau menghapus data tabel tanpa bertanya dulu kepada Anda.
3. **Merusak Barang Lama (*Regression*)**: Saat diminta memperbaiki tombol kecil yang miring, dia malah merusak sistem login yang sebelumnya sudah berjalan lancar.
4. **Suka Malas-malasan (*AI Slop*)**: Dia suka menulis kode setengah-setengah dengan komentar malas seperti `// ... tambahkan sisa kode di sini`, sehingga kodenya error saat dijalankan.

### 🛡️ Solusinya: "Willy AI Working Model v1.0"
Model kerja ini adalah **Buku SOP (Standar Operasional Prosedur) & Konstitusi Mutlak** yang kita pasang di sistem AI. 

Dengan model ini, AI dipaksa menjadi insinyur perangkat lunak profesional yang:
- Selalu membaca buku catatan sebelum mulai bekerja.
- Dilarang keras merusak fitur lama atau menghapus database.
- Wajib mengetes kodenya sendiri dan menunjukkan bukti lulusnya (`0 error`).
- Selalu menjaga keamanan dari hacker (anti bocor password, anti pencurian data).

---

## 🔍 2. Bedah Isi: Apa Saja Benda-Benda di Dalam Model Kerja Ini?

Bagi pemula, melihat banyak folder dan file singkatan bisa membingungkan. Berikut penjelasan **arti dan fungsi setiap benda** dengan perumpamaan sederhana:

### 📄 A. File-File Kunci di Setiap Proyek (Level Folder Proyek)

| Nama File | Perumpamaan Sehari-hari | Fungsi Sebenarnya |
|---|---|---|
| **`AGENTS.md`** | **Undang-Undang Dasar (UUD) Proyek** | Buku peraturan tertinggi. Memuat hak dan kewajiban AI: apa yang boleh dia lakukan sendiri dan kapan dia WAJIB berhenti meminta izin Anda. |
| **`working.md`** | **Buku Diary / Buku Catatan Harian AI** | Tempat AI mencatat: *"Hari ini saya sudah selesai sampai mana, dan besok harus lanjut dari baris berapa"*. Ini obat anti-pikun AI! |
| **`task.md`** | **Papan Tulis To-Do List** | Daftar antrian tugas (TASK-001, TASK-002). AI mengambil tugas dari sini satu per satu secara teratur. |
| **`build_upload.ps1`** | **Tukang Sapu & Pengepakan Koper** | Skrip otomatis untuk membungkus hasil kerja jadi file ZIP bersih siap upload ke hosting/cPanel, sambil otomatis membuang file sampah/catatan AI. |
| **`RELEASE_MANIFEST.md`** | **Buku Sertifikat Garansi Rilis** | Mencatat riwayat setiap kali Anda merilis web (tanggal rilis, nomor kode unik SHA256, dan cara mundur ke versi lama jika ada error). |
| **`MIGRATION_LOG.md`** | **Buku Akta Tanah Database** | Buku catatan resmi setiap kali ada tabel atau kolom baru di database MySQL. Mencegah perubahan database secara diam-diam. |
| **`.htaccess`** | **Pagar & Satpam Keamanan** | Menjaga folder rahasia agar orang luar tidak bisa mengintip file konfigurasi atau menjalankan virus di folder upload. |
| **`.gitignore`** | **Tirai Penutup Privasi** | Daftar file yang dilarang di-upload ke GitHub publik (seperti password database di `.env`). |

---

### ⚙️ B. File-File Otak di Sistem Laptop (`C:\Users\Willy\.gemini\config\`)

File-file inilah yang membuat AI di laptop Anda pintar secara permanen di semua proyek:

#### 1. Folder `rules/` (Aturan yang Selalu Diingat AI)
- **`willy-global.md`**: Otak konstitusi utama. Memuat aturan keamanan OWASP, larangan kode malas (*Anti-Slop*), dan aturan Header/Footer identitas Willy AI.
- **`global-compliance-checker.md`**: Satpam otomatis. Setiap kali Anda membuka folder proyek baru, file ini langsung memeriksa: *"Apakah proyek ini sudah punya AGENTS.md? Kalau belum, tawarkan setup otomatis!"*

#### 2. Folder `skills/` (Jurus Sakti Tambahan yang Dipanggil Saat Butuh)
- **`willy-shortcuts/`**: Kamus pintasan. Menerjemahkan kata pendek seperti `Willy AI run` menjadi tindakan teknis puluhan langkah.
- **`willy-review/`**: Senior Code Reviewer pribadi Anda. AI akan memeriksa perbedaan kode (*git diff*), mencari celah keamanan, dan memberi nilai skor kelayakan 0–100.
- **`willy-research/`**: Gudang ilmu rujukan riset mandiri (standar penulisan ilmiah EYD V, sitasi DOI/Scopus terverifikasi, dan panduan audit pihak ketiga).

---

## 🛡️ 3. Istilah-Istilah Keren yang Wajib Anda Pahami

Di dalam model kerja ini ada beberapa istilah teknis penting. Jangan bingung, ini artinya:

1. **Anti-Regression (Anti-Rusak Barang Lama)**:
   - Aturan di mana AI dilarang merombak alur yang sudah stabil. Fitur baru tidak boleh mengorbankan fitur lama.
2. **Anti-Slop (Anti-Kode Malas & Anti-Tampilan Jelek)**:
   - Dilarang memotong kode (`// rest of code...`).
   - Dilarang membuat tombol kekecilan yang susah dipencet di HP (target sentuh wajib minimal 48×48 pixel).
   - Tampilan web wajib rapi, kontras jelas, dan responsif di layar ponsel.
3. **Zero-Leakage (Nol Kebocoran Rahasia)**:
   - Password database, kunci API, dan token rahasia tidak boleh ditulis langsung di dalam kode, melainkan wajib di file `.env` yang terisolasi.
4. **Anti-IDOR (Anti-Salah Kamar / Anti-Intip Data Orang)**:
   - Setiap kali mengambil data profil atau dokumen, sistem wajib mengecek kepemilikan: *"Apakah user ini benar-benar pemilik data tersebut?"* (mencegah user A melihat data user B hanya dengan mengganti angka ID di URL).
5. **Verification Gate (Gerbang Pembuktian Nyata)**:
   - AI dilarang sekadar mengklaim *"kode sudah berfungsi"*. AI wajib menjalankan perintah tes di terminal komputer Anda dan membuktikan keluaran `0 error`.

---

## ⚡ 4. Daftar Jurus Singkat (Pintasan Perintah di Chat)

Anda cukup mengetik kata singkat ini di chat obrolan Antigravity:

| Perintah Singkat | Maksudnya Apa? | Apa yang Dikerjakan AI? |
|---|---|---|
| **`Willy AI run`** | *"Lanjutkan koding!"* | AI membaca `task.md`, melanjutkan fitur berikutnya, mengetes sintaks, dan mencatat hasilnya. |
| **`Willy AI status`** | *"Bagaimana kondisi proyek sekarang?"* | AI membuat dashboard: branch Git aktif, commit terakhir, berkas sampah yang perlu dibuang, dan task aktif. |
| **`Willy AI review`** | *"Tolong periksa kode saya!"* | AI memeriksa perubahan kode terakhir, mengecek keamanan, dan memberi skor 0–100 apakah aman di-merge. |
| **`Willy AI test`** | *"Coba tes apakah ada error?"* | AI mengetes semua file (`php -l`), memastikan tidak ada variabel rusak, dan menampilkan buktinya. |
| **`Willy AI fix [pesan error]`**| *"Tolong betulkan error ini!"* | AI menganalisis error, mencari baris rusaknya, memperbaiki secara presisi, lalu tes ulang sampai sembuh. |
| **`Willy AI audit`** | *"Cek apakah ada celah keamanan!"* | AI memindai seluruh proyek dari kebocoran password, celah SQL injection, dan celah XSS. |
| **`Willy AI health`** | *"Medical check-up proyek!"* | Audit gabungan: cek error sintaks + cek keamanan + cek file sampah sekaligus. |
| **`Willy AI changelog`** | *"Catat riwayat update!"* | AI membaca log komit Git dan menyusun file `CHANGELOG.md` yang rapi. |
| **`Willy AI pack`** | *"Bungkus untuk hosting!"* | Menjalankan `build_upload.ps1` untuk membuat file ZIP bersih siap upload ke cPanel server. |

---

## 🚀 5. Cara Memulai Proyek Website Baru (Hanya 1 Kalimat!)

Buka chat baru di Antigravity, lalu ketik satu kalimat ini:

> **"Buat proyek website [nama_web] di [folder_tujuan] dan inisialisasi Willy AI Working Model."**

**Contoh nyata:**
> *"Buat proyek website toko_sepatu di D:\Data_web\toko_sepatu dan inisialisasi Willy AI Working Model."*

Dalam hitungan detik, AI akan membuatkan folder lengkap dengan seluruh instrumen di atas. Setelah itu, Anda tinggal ketik `Willy AI run` untuk mulai membuat halaman web!

---

## 🛠️ 6. Cara Mengembangkan atau Merevisi di Masa Depan

Ingin menambah aturan baru atau jurus baru? Sangat mudah karena ini hanya file teks:

- **Ingin Menambah Jurus Chat Baru?**
  Buka file `C:\Users\Willy\.gemini\config\skills\willy-shortcuts\SKILL.md`, tambahkan kata pintasan baru Anda di tabelnya.
- **Ingin Menambah Aturan Desain (misal: Wajib Warna Biru)?**
  Buka file `C:\Users\Willy\.gemini\config\rules\willy-global.md`, tambahkan instruksi desain di bagian *Pilar Kualitas*.
- **Ingin Naik Versi (ke v1.1 atau v2.0)?**
  Cukup ganti tulisan `v1.0` menjadi `v1.1` di file `willy-global.md`, `README.md`, dan `SKILL.md`. AI akan langsung menyapa Anda dengan versi baru tersebut!

---

## 📲 7. Panduan Langkah Demi Langkah Upload ke GitHub (Manual via Aplikasi)

Bagi Anda yang ingin mengunggah folder ini secara visual tanpa mengetik perintah terminal yang rumit, berikut 2 cara paling mudah:

---

### Cara A: Menggunakan Aplikasi "GitHub Desktop" (Sangat Direkomendasikan ⭐)

Aplikasi **GitHub Desktop** adalah aplikasi resmi dari GitHub dengan tampilan tombol visual:

1. **Buka Aplikasi GitHub Desktop**:
   - Jika belum punya, download gratis di [desktop.github.com](https://desktop.github.com) lalu login dengan akun GitHub Anda.
2. **Tambahkan Folder Proyek**:
   - Klik menu **File** di kiri atas $\rightarrow$ pilih **Add Local Repository...** (atau tekan tombol `Ctrl + O`).
   - Klik tombol **Choose...** $\rightarrow$ arahkan ke folder:
     `c:\Users\Willy\Downloads\Model AI\Willy AI Working Model`
   - Klik tombol **Add Repository**.
   *(Jika muncul tulisan "This directory does not appear to be a Git repository", klik link biru bertuliskan **create a repository here** lalu klik Create).*
3. **Simpan Perubahan (Commit)**:
   - Di pojok kiri bawah, Anda akan melihat kotak **Summary**.
   - Ketik judul: `Rilis Perdana Willy AI Working Model v1.0`
   - Klik tombol biru besar: **Commit to main**.
4. **Unggah ke GitHub Server (Publish)**:
   - Di bagian atas layar, klik tombol **Publish repository**.
   - Beri nama (misalnya: `willy-ai-working-model`).
   - Tentukan apakah mau dijadikan **Private** (hanya Anda yang bisa lihat) atau tidak dicentang (bisa dilihat publik).
   - Klik tombol **Publish Repository**.
   - 🎉 **Selesai!** Seluruh folder dan buku panduan Anda sudah resmi live di akun GitHub Anda!

---

### Cara B: Menggunakan Web Browser (Upload Drag-and-Drop)

Jika Anda tidak memasang aplikasi dan ingin langsung lewat website:

1. Buka browser dan buka situs [github.com/new](https://github.com/new).
2. Isi **Repository name**: `willy-ai-working-model`.
3. Pilih **Public** atau **Private**, lalu klik tombol hijau **Create repository**.
4. Di halaman berikutnya yang muncul, klik link kecil bertuliskan: **"uploading an existing file"**.
5. Buka Windows Explorer ke folder: `c:\Users\Willy\Downloads\Model AI\Willy AI Working Model`.
6. Tarik (drag-and-drop) file-file penting Anda ke kotak browser GitHub.
7. Di bagian bawah, klik tombol hijau **Commit changes**.
8. 🎉 Selesai!

---

## 🌈 Kesimpulan untuk Pemula

Anda sekarang memiliki sebuah **sistem AI cerdas berstandar industri** milik Anda sendiri bernama **Willy AI Working Model v1.0**. 

Setiap kali Anda meminta bantuan AI untuk membuat website, aplikasi, atau riset, AI tidak lagi bekerja secara acak, melainkan selalu berada dalam pengawasan aturan yang aman, rapi, dan teruji! 🚀
