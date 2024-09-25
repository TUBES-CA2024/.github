
---

# 🎉 Panduan Penggunaan GitHub Organization! 🎉

## Daftar Isi
1. [Cara Membuat Repository di GitHub Organization](#cara-membuat-repository-di-github-organization)
2. [Menambahkan Kolaborator ke Repository](#menambahkan-kolaborator-ke-repository)
3. [Clone Repository ke Lokal](#clone-repository-ke-lokal)
4. [Menggunakan Branch dan Pull Request](#menggunakan-branch-dan-pull-request)
5. [Review dan Merge Pull Request](#review-dan-merge-pull-request)

---

### 💻 Cara Membuat Repository di GitHub Organization
Ikuti langkah-langkah berikut untuk membuat repository di dalam sebuah GitHub Organization:

1. **Login ke GitHub**: Masuk ke akun GitHub kamu.
2. **Navigasi ke Halaman Organization**: 
   - Klik di menu profil kamu di kanan atas, lalu pilih nama organisasi yang ingin kamu buatkan repository.
3. **Membuat Repository**:
   - Di halaman organisasi, klik tab `Repositories`.
   - Klik tombol hijau `New` di sebelah kanan atas.
   - Isi detail repository seperti:
     - **Repository name**: Nama repository (pastikan sesuai dengan project kamu).
     - **Description** (opsional): Deskripsi singkat tentang repository.
     - **Public/Private**: Pilih apakah repository ini bisa dilihat publik atau hanya anggota organisasi.
   - Klik `Create repository` setelah selesai mengisi detail.
4. **Inisialisasi Repository**:
   - Kamu bisa memilih untuk menambahkan file README, `.gitignore`, atau lisensi saat membuat repository, atau bisa menambahkannya nanti.

---

### 👥 Menambahkan Kolaborator ke Repository
Jika kamu ingin mengizinkan orang lain dalam organisasi untuk bekerja di repository yang telah dibuat, ikuti langkah-langkah berikut:

1. **Masuk ke Repository**: Buka repository yang ingin kamu tambahkan kolaborator.
2. **Buka Pengaturan**: Klik tab `Settings` di kanan atas halaman repository.
3. **Kelola Tim**:
   - Di menu sebelah kiri, klik `Manage access`.
   - Klik `Invite a collaborator` dan cari username teman-teman kamu yang ingin kamu tambahkan.
   - Setelah mereka menerima undangan, mereka akan bisa mengakses repository.

---

### 🔄 Clone Repository ke Lokal
Setelah repository dibuat, kamu bisa meng-clone-nya ke komputer lokal untuk memulai pengembangan:

1. **Buka Repository**: Akses halaman repository yang ingin kamu clone.
2. **Klik Tombol `Code`**: Di bagian kanan atas, klik tombol `Code`, lalu salin URL yang muncul (HTTPS, SSH, atau GitHub CLI).
3. **Clone ke Lokal**: Buka terminal atau command prompt, lalu jalankan perintah berikut:
   ```bash
   git clone https://github.com/organization-name/repository-name.git
   ```
   Ini akan menyalin semua isi repository ke komputer lokal.

---

### 🌿 Menggunakan Branch dan Pull Request
Untuk bekerja secara kolaboratif di dalam repository, kamu bisa menggunakan branch dan pull request agar tidak langsung bekerja di branch `main`.

1. **Membuat Branch Baru**:
   - Di terminal, jalankan perintah berikut untuk membuat branch baru:
     ```
     git checkout -b nama-branch-baru
     ```
   - Kamu sekarang berada di branch baru. Mulailah melakukan perubahan di branch ini.

2. **Melakukan Commit**:
   - Setelah melakukan perubahan, jalankan perintah berikut untuk menyimpan perubahan:
     ```
     git add .
     git commit -m "Pesan commit"
     ```

3. **Push Branch ke GitHub**:
   - Kirim branch yang kamu buat ke GitHub dengan menjalankan:
     ```
     git push origin nama-branch-baru
     ```

4. **Membuat Pull Request**:
   - Setelah branch sudah di-push ke GitHub, buka halaman repository di GitHub.
   - Klik tombol `Compare & pull request` yang muncul di halaman repository.
   - Isi detail pull request dan submit pull request untuk ditinjau oleh tim.

---

### 🔍 Review dan Merge Pull Request
Setelah pull request dibuat, penting bagi tim untuk melakukan review dan merge perubahan ke branch utama (`main` atau branch lain yang ditentukan).

1. **Review Pull Request**:
   - Teman-teman tim bisa mengakses pull request melalui tab `Pull requests`.
   - Buka pull request yang ingin direview.
   - **Lakukan review** dengan memeriksa kode yang ditambahkan, diedit, atau dihapus.
   - Jika ada feedback atau perubahan yang perlu dilakukan, kamu bisa menambahkan komentar di baris kode atau meninggalkan pesan di pull request.

2. **Approve Pull Request**:
   - Jika sudah sesuai, teman-teman bisa mengklik tombol `Approve` di bagian review.
   - Pastikan semua feedback telah diperhatikan sebelum pull request di-approve.

3. **Merge Pull Request**:
   - Setelah pull request di-approve, orang yang membuka pull request atau anggota tim dengan akses bisa mengklik tombol `Merge pull request`.
   - Pilih metode merge:
     - **Merge Commit**: Menggabungkan semua commit dari branch ke `main`.
     - **Squash and Merge**: Menggabungkan semua commit menjadi satu commit.
     - **Rebase and Merge**: Menggabungkan branch ke `main` dengan menambahkan commit secara linier.
   - Setelah di-merge, branch bisa dihapus untuk membersihkan repository.

4. **Mengatasi Conflict**:
   - Jika ada conflict (perubahan bertabrakan dengan kode lain), GitHub akan menampilkan pesan conflict. Conflict harus diselesaikan terlebih dahulu sebelum pull request bisa di-merge.

---

### ⚠️ Beberapa Hal Penting:
- Selalu buat **branch baru** untuk fitur atau perubahan yang signifikan agar tidak mengganggu branch `main`.
- **Jangan langsung push ke branch `main`**. Gunakan pull request untuk review sebelum melakukan merge.
- Jika muncul **conflict**, selesaikan dengan bijak, dan pastikan tidak ada kode yang hilang.
- **Selalu komunikasikan** perubahan yang besar dengan tim untuk menghindari kesalahpahaman.

---

🔥 **Semangat kerja tubesnya guys!!!** 🔥

🎉 SEMOGA MAKIN GACOR YAH KAWAN-KAWAN ! 💪

---
