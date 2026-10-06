# Praktikum Sistem Operasi (Sisop)
**Semester Ganjil Tahun Ajaran 2026/2027**

## Informasi Mata Kuliah

| Item | Keterangan |
|------|------------|
| **Nama Mata Kuliah** | Sistem Operasi |
| **Program Studi** | S1 Informatika |
| **Fakultas** | Fakultas Informatika |
| **Universitas** | Universitas Telkom |


## Deskripsi

Modul praktikum ini merupakan bagian integral dari mata kuliah Sistem Operasi. Praktikum ini dirancang untuk memberikan pengalaman *hands-on* dalam memahami konsep inti sistem operasi, mulai dari dasar instalasi hingga eksplorasi dan pemahaman terhadap arsitektur kernel Xinu.

Praktikum ini memadukan eksplorasi *source code* kernel Xinu menggunakan *tools* seperti Sourcetrail, serta implementasi langsung melalui *command line* dan *bash scripting* di lingkungan Linux.

## Daftar Modul

### Modul 1: Running Modul
- Pengenalan aturan, sistem pelaksanaan, dan penilaian praktikum.
- Verifikasi *tools* wajib (VirtualBox, Xinu, Ubuntu, Sourcetrail).

### Modul 2: Instalasi Xinu
- Persiapan dan instalasi Oracle VM VirtualBox.
- Import dan konfigurasi *Development-System VM* dan *Backend VM*.
- Memahami arsitektur *cross-development* pada Xinu.

### Modul 3: Eksplorasi Xinu
- Menjalankan Xinu OS pada *Backend VM*.
- Menggunakan *shell* dan perintah-perintah dasar pada Xinu.

### Modul 4: Membaca Source Code Xinu
- Memahami paradigma *embedded* dan organisasi *source code* Xinu.
- Eksplorasi *source code* menggunakan *tool* Sourcetrail.
- Memahami tipe data dan *header files* utama Xinu.

### Modul 5: Eksplorasi Proses
- Memahami *Process Control Block* (PCB) dan struktur `proctab[]`.
- Manajemen proses: `create`, `resume`, dan `kill`.

### Modul 6: Sekuensial dan Konkuren
- Perbedaan konsep pemrograman sekuensial dan konkuren.
- Implementasi *multiprogramming/multitasking* pada Xinu.

### Modul 7: Semaphore
- Operasi Semaphore: Inisiasi, Signal, dan Wait.
- Implementasi pola *Signaling* dan *Mutex* untuk sinkronisasi proses.

### Modul 8: Remedial CLO 2
- Kesempatan perbaikan nilai untuk Capaian Pembelajaran 2.

### Modul 9: Syscall Xinu
- Definisi, fungsi, dan cara kerja *System Call* pada Xinu.
- Membuat dan mengimplementasikan *syscall* baru pada kernel Xinu.

### Modul 10: Shell
- Memahami cara kerja *shell* pada Xinu (`shell.c`).
- Menambahkan perintah (*command*) baru pada *shell* Xinu.

### Modul 11: Memori Xinu
- Struktur *Memory Image* (Text, Data, BSS, Free Space).
- Konsep Stack dan Heap, serta fungsi manajemen memori (`getstk`, `getmem`, `freestk`, `freemem`).

### Modul 12: Linux dan Windows
- Sejarah dan spesifikasi Sistem Operasi Windows dan Linux (Ubuntu).
- Panduan instalasi dasar Ubuntu.

### Modul 13: Perintah Dasar Linux
- Perintah dasar terminal: `ls`, `cd`, `cp`, `rm`, `mv`, `mkdir`, `pwd`, `man`.
- Konsep *Pipeline* (`|`) dan *Redirection* (`>`, `>>`, `<`).
- Kompilasi program C menggunakan GCC.

### Modul 14: Scripting
- Dasar-dasar *Bash scripting*: Variabel, *Command Line Argument*, Input.
- Operasi aritmatika, *If Statement*, *Loop* (for, while, until), dan Fungsi.

### Modul 15: Keamanan Linux
- *Access Control* dan *File Permission* (`chmod`, `umask`).
- Integritas file menggunakan Hash (SHA-256 / GtkHash).
- Kerahasiaan: Enkripsi *File System* (ENCFS) dan Kriptografi Kunci Publik (GPG).

### Modul 16: Remedial CLO 4
- Kesempatan perbaikan nilai untuk Capaian Pembelajaran 4.

## Tools yang Digunakan

### Wajib
1. **Oracle VM VirtualBox** (Versi 6.1 atau yang direkomendasikan)
2. **Xinu OS** (*Virtual Machine Appliance* `.ova`)
3. **Ubuntu** (Dijalankan di dalam VirtualBox)
4. **Sourcetrail** (Untuk eksplorasi *source code* C/C++)

### Opsional / Pendukung
- Text Editor / IDE (VS Code, Vim, dll.)
- GCC (GNU Compiler Collection)
- Minicom (untuk komunikasi *serial port*)

## Peraturan Praktikum

### Kehadiran
- Wajib hadir minimal **75%** dari seluruh pertemuan praktikum di lab.
- Keterlambatan **≤ 5 menit**: diperbolehkan mengikuti praktikum tanpa tambahan.
- Keterlambatan **≥ 30 menit**: **tidak diperbolehkan** mengikuti praktikum.
- Maksimal **2 kali** praktikum susulan per mata kuliah.

### Persyaratan Praktikum Susulan
- Sakit (dibuktikan dengan surat keterangan medis).
- Tugas dari institusi (dibuktikan dengan surat dinas/dispensasi).
- Musibah/kedukaan (menunjukkan surat keterangan dari orangtua/wali).
- *Persyaratan diserahkan sesegera mungkin kepada asisten laboratorium.*

### Tata Tertib
- Wajib membawa modul praktikum, kartu praktikum (KTM), dan alat tulis.
- Wajib menggunakan seragam sesuai aturan institusi.
- Wajib mematikan/mengkondisikan alat komunikasi.
- Dilarang membuka aplikasi yang tidak berhubungan dengan praktikum.
- Dilarang mengubah pengaturan *software* maupun *hardware* komputer tanpa izin.
- Dilarang membawa makanan maupun minuman di ruang praktikum.
- Dilarang menyebarkan soal praktikum.
- **Sanksi:** Lupa menghapus file praktikum = Pengurangan nilai modul **20%**.
- **Sanksi:** Memicu kegaduhan (ditegur 3x oleh asisten) = Pengurangan nilai modul **50%**.

### Integritas Akademik
- Meminta, mendapatkan, dan menyebarluaskan soal/kunci jawaban:
   - **Penyebar:** Pengajuan sanksi kepada Komisi Disiplin Fakultas.
   - **Penerima:** Nilai **0** pada seluruh assessment praktikum.
- Ketidakhadiran tanpa keterangan: Nilai modul = **0**.

## Sistem Penilaian
Komponen penilaian praktikum meliputi:
- Kehadiran dan partisipasi aktif.
- Tugas Pendahuluan (TP) / Kuis.
- Laporan praktikum per modul.
- Penilaian CLO (Capaian Pembelajaran) per modul.
- Ujian / Remedial (jika memenuhi syarat).

**Catatan:** Jika kehadiran < 75%, praktikan tidak diperbolehkan mengikuti penilaian akhir / nilai otomatis tidak memenuhi standar kelulusan.

## Cara Komplain

### Melalui iGracias
1. Login ke [iGracias](https://igracias.telkomuniversity.ac.id/).
2. Pilih Menu **Masukan dan Komplain** → **Input Tiket**.
3. Pilih Fakultas/Bagian: **Bidang Akademik (FIF)**.
4. Pilih Program Studi/Urusan: **Urusan Laboratorium/Bengkel/Studio (FIF)**.
5. Pilih Layanan: **Praktikum**.
6. Pilih Kategori: **Pelaksanaan Praktikum**, lalu pilih Sub Kategori yang sesuai.
7. Isi Deskripsi sesuai komplain yang ingin disampaikan.
8. Lampirkan file bukti jika perlu, lalu klik **Kirim**.

## Referensi
1. Comer, D. (2015). *Operating System Design - The Xinu Approach*, Second Edition. CRC Press.
2. The Xinu Page. Xinu Team. [https://xinu.cs.purdue.edu/](https://xinu.cs.purdue.edu/)
3. Sourcetrail: Free and open-source cross-platform source explorer. [https://www.sourcetrail.com/](https://www.sourcetrail.com/)
4. Dokumentasi Resmi Ubuntu & Linux Command Line.

## Kontak
Untuk pertanyaan lebih lanjut, silakan hubungi:
- Dosen Koordinator Mata Kuliah Sistem Operasi
- Kepala Laboratorium Informatika FIF
- Asisten Laboratorium / Asisten Praktikum yang bertugas

---

**Bandung, 11 September 2025**  
*(Sesuai tanggal pengesahan pada modul)*

**Koordinator Mata Kuliah Sistem Operasi**  
*Febri Dawani, S.T., M.T.*  
NIP. 20850005

---
