# Website Ulang Tahun Pacar LDR 💗

Website statis satu file untuk GitHub Pages. Berisi halaman pembuka, kuis LDR, game tangkap hati, surat cinta, dan halaman penutup.

## Cara mengedit tulisan
1. Buka `index.html` dengan Notepad, VS Code, atau editor teks.
2. Cari bagian `const CONFIG = {` di dekat bagian bawah file.
3. Ubah `namaPacar`, `namaKamu`, `pembuka`, `surat`, `ucapanAkhir`, dan pertanyaan pada `pertanyaanKuis`.
4. Simpan file, lalu upload ulang `index.html` ke repository GitHub.

## Cara memasang musik (opsional)
1. Siapkan file audio yang kamu miliki hak untuk menggunakannya, beri nama `music.mp3`.
2. Upload `music.mp3` ke folder utama repository, sejajar dengan `index.html`.
3. Di `index.html`, cari:
   `<!-- <source src="music.mp3" type="audio/mpeg"> -->`
4. Hapus tanda komentar `<!--` dan `-->`, sehingga menjadi:
   `<source src="music.mp3" type="audio/mpeg">`
5. Simpan dan upload ulang `index.html`.

## Upload ke GitHub
1. Buka repository `Ulang-Tahun-My-Pacar`.
2. Klik **Add file → Upload files**.
3. Upload `index.html` dan `README.md` (serta `music.mp3` jika digunakan).
4. Klik **Commit changes**.
5. Buka **Settings → Pages**.
6. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/(root)`, lalu **Save**.
7. Tunggu publikasi selesai. Alamat website biasanya berbentuk:
   `https://USERNAME.github.io/Ulang-Tahun-My-Pacar/`

## Catatan
- Ganti `USERNAME` dengan username GitHub kamu.
- Website ini tidak membutuhkan database atau server tambahan.
- Tombol WhatsApp membuka WhatsApp dengan pesan yang sudah disiapkan; pengguna masih perlu memilih penerima dan mengirimnya.
