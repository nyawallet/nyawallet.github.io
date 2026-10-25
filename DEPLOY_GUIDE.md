# 🚀 Panduan Publikasi Website Developer & app-ads.txt NyaWallet

Folder `website/` ini telah disiapkan secara lengkap dan memenuhi **IAB Tech Lab Specification** serta standar kebijakan **Google Play Developer & Apple App Store**.

---

## Berkas yang Tersedia di Folder Ini:
1. `app-ads.txt`: Berisi baris otorisasi resmi Google AdMob:
   ```text
   google.com, pub-8338019036731602, DIRECT, f08c47fec0942fa0
   ```
2. `index.html`: Landing page modern bertema pastel hangat khas NyaWallet dengan showcase fitur, badge download, dan identitas developer HooQii.
3. `privacy.html`: Kebijakan Privasi resmi (*Zero Data Collection & Offline-First Architecture*) wajib untuk Google Play Console & App Store Connect.
4. `terms.html`: Syarat & Ketentuan Layanan (*Terms of Service*).
5. `assets/`: Berkas logo dan maskot NyaWallet.

---

## Cara 1 (Paling Direkomendasikan & 100% Gratis Selamanya): GitHub Pages Root Domain

> **Mengapa ini yang terbaik?**  
> Google AdMob **wajib** mengakses `app-ads.txt` di *Root Domain* (`https://username.github.io/app-ads.txt`). Jika diletakkan di subfolder repositori biasa, AdMob crawler akan gagal memverifikasi.

### Langkah-langkah (Hanya 3 Menit):
1. Buka akun GitHub Anda: [github.com/new](https://github.com/new).
2. Buat repositori baru dengan nama persis:
   ```text
   hooqii.github.io
   ```
   *(Harus `public`)*
3. Unggah seluruh isi di dalam folder `website/` ini (bukan foldernya, tapi file di dalamnya: `app-ads.txt`, `index.html`, `privacy.html`, `terms.html`, dan folder `assets/`) ke repositori `hooqii.github.io` tersebut.
4. Tunggu 1 menit. Situs Anda akan langsung aktif secara otomatis di:
   - 🌐 **Website**: `https://hooqii.github.io`
   - 📄 **app-ads.txt**: `https://hooqii.github.io/app-ads.txt`
   - 📜 **Privacy Policy**: `https://hooqii.github.io/privacy.html`

---

## Langkah Setelah Website Aktif:

### 1. Hubungkan ke Google Play Console
1. Buka [Google Play Console](https://play.google.com/console).
2. Pilih aplikasi **NyaWallet**.
3. Di menu sebelah kiri, buka:  
   **Keberadaan di Store (Store presence)** ➔ **Setelan Store (Store settings)**.
4. Pada bagian **Detail kontak developer (Developer contact details)**:
   - Kolom **Situs web**: Masukkan `https://hooqii.github.io`
   - Kolom **Email**: `hooqii.me@gmail.com`
5. Pada bagian **Kebijakan Privasi (Privacy Policy)**:
   - Masukkan `https://hooqii.github.io/privacy.html`
6. Klik **Simpan (Save)**.

### 2. Verifikasi di Google AdMob
1. Buka kembali halaman AdMob tempat munculnya pesan verifikasi.
2. Klik tombol **[Check for updates]**.
3. Robot AdMob akan membaca `https://hooqii.github.io/app-ads.txt` dan status verifikasi akan berubah menjadi **Hijau (Verified)** dalam 24 jam.

