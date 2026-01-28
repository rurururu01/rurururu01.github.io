# 🌐 Portfolio Website - Seperti hafidzrdwn.my.id

Portfolio website modern dengan desain minimalis & profesional, siap di-publish ke internet!

## ✨ Fitur

- ✅ Desain modern minimalis (seperti hafidzrdwn.my.id)
- ✅ Dark theme hero section
- ✅ Timeline experiences
- ✅ Animasi smooth & interaktif
- ✅ Mobile-friendly
- ✅ Loading cepat
- ✅ SEO friendly

## 🚀 2 CARA PUBLISH WEBSITE:

### OPSI 1: Domain Kustom .my.id (Seperti Teman Anda!) 🔥

Kalau mau punya domain sendiri seperti `namakamu.my.id` (Rp 15.000/tahun):

#### Step 1: Beli Domain .my.id
1. **Buka Pandi.id**: https://pandi.id/
2. **Klik "Daftar Domain"**
3. **Cek ketersediaan**: `namakamu.my.id`
4. **Beli domain** (~Rp 15.000 - 20.000 per tahun)
5. Alternatif registrar: Niagahoster, Domainesia, Rumahweb

#### Step 2: Deploy ke Netlify (GRATIS!)
1. **Kunjungi**: https://www.netlify.com/
2. **Klik "Sign Up"** (gratis, pakai email/GitHub)
3. **Klik "Add new site" → "Deploy manually"**
4. **Drag & drop folder Porto** Anda (yang berisi index.html, style.css, script.js)
5. Tunggu 1 menit → Website online di `namakamu.netlify.app`

#### Step 3: Connect Domain .my.id ke Netlify
1. Di Netlify, masuk ke **Site settings → Domain management**
2. Klik **"Add custom domain"**
3. Masukkan domain Anda: `namakamu.my.id`
4. Netlify akan kasih DNS records yang harus diset
5. Login ke dashboard domain Anda (Pandi/Niagahoster)
6. Tambahkan DNS records dari Netlify:
   - Type: **A** → Value: `75.2.60.5`
   - Type: **CNAME** → Name: `www` → Value: `namakamu.netlify.app`
7. Tunggu 10-60 menit → Website live di `namakamu.my.id` ✨

### OPSI 2: GitHub Pages - 100% GRATIS (Tanpa Domain Kustom)

### OPSI 2: GitHub Pages - 100% GRATIS (Tanpa Domain Kustom)

Website akan online di `username.github.io`

### Langkah 1: Buat Akun GitHub
1. Kunjungi [github.com](https://github.com)
2. Klik "Sign Up" dan buat akun gratis
3. Verifikasi email Anda

### Langkah 2: Buat Repository Baru
1. Setelah login, klik tombol **"+"** di kanan atas
2. Pilih **"New repository"**
3. Beri nama repository: `username.github.io` (ganti `username` dengan username GitHub Anda)
   - Contoh: jika username Anda `adity`, buat repo `adity.github.io`
4. Centang **"Public"**
5. Klik **"Create repository"**

### Langkah 3: Upload File Portfolio
**Cara Termudah - Upload via Website:**
1. Di halaman repository, klik **"uploading an existing file"** atau **"Add file" > "Upload files"**
2. Drag & drop ketiga file ini dari folder Porto:
   - `index.html`
   - `style.css`
   - `script.js`
3. Scroll ke bawah, tulis commit message: "Initial portfolio"
4. Klik **"Commit changes"**

### Langkah 4: Aktifkan GitHub Pages
1. Di repository, klik **"Settings"** (tab di atas)
2. Scroll ke bawah, klik **"Pages"** di menu kiri
3. Di bagian **"Source"**, pilih:
   - Branch: **main** (atau master)
   - Folder: **/ (root)**
4. Klik **"Save"**

### Langkah 5: Website Live! 🎉
1. Tunggu 2-5 menit
2. Website Anda akan online di: `https://username.github.io`
3. SELESAI!

**BONUS: Hubungkan Domain Kustom ke GitHub Pages**

Kalau sudah punya domain .my.id, bisa dihubungkan ke GitHub Pages juga:
1. Di GitHub repo → Settings → Pages
2. Di "Custom domain", masukkan: `namakamu.my.id`
3. Centang "Enforce HTTPS"
4. Di dashboard domain, tambahkan DNS:
   - Type: **A** → Value: 
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - Type: **CNAME** → Name: `www` → Value: `username.github.io`
5. Tunggu 10-60 menit → Done!

## 🌟 REKOMENDASI:

**Untuk Hasil Terbaik (Seperti hafidzrdwn.my.id):**
- ✅ **Domain .my.id** (murah, cuma Rp 15rb/tahun)
- ✅ **Deploy ke Netlify** (gratis, unlimited bandwidth, SSL otomatis)
- ✅ **Benefit**: Domain profesional, cepat, auto-deploy

**Untuk 100% Gratis:**
- ✅ **GitHub Pages** (domain: username.github.io)
- ✅ **Benefit**: Totally free, terintegrasi dengan Git

## 🎨 Cara Customize Portfolio

### Edit Informasi Pribadi
Buka `index.html` dan edit bagian-bagian ini:

1. **Nama & Judul:**
   ```html
   <h1>Halo, Saya <span class="highlight">Nama Anda</span></h1>
   <p>Web Developer | Designer | Creator</p>
   ```

2. **Tentang Saya:**
   Ganti teks di section `#about`

3. **Skills:**
   Edit atau tambah skills di section `#skills`

4. **Proyek:**
   Tambah/edit proyek di section `#projects`

5. **Kontak:**
   Edit link sosial media di bagian `social-links`:
   ```html
   <a href="https://github.com/username" class="social-link">
   <a href="https://linkedin.com/in/username" class="social-link">
   ```

### Ganti Warna Theme
Buka `style.css` dan edit warna di bagian `:root`:
```css
:root {
    --primary-color: #6366f1;  /* Warna utama */
    --secondary-color: #8b5cf6;  /* Warna kedua */
    /* Edit sesuai selera! */
}
```

### Tambah Foto Profil
1. Upload foto ke repository (misalnya `profile.jpg`)
2. Di `index.html`, ganti bagian ini:
   ```html
   <div class="image-placeholder">
       <i class="fas fa-user"></i>
   </div>
   ```
   Menjadi:
   ```html
   <img src="profile.jpg" alt="Profile">
   ```

## 📱 Hosting Alternatif GRATIS Lainnya

### 1. **Netlify** ⭐ REKOMENDED (Seperti yang dipakai profesional)
- **Website**: [netlify.com](https://netlify.com)
- **Cara**: Drag & drop folder Porto
- **Domain gratis**: `namakamu.netlify.app`
- **Kelebihan**: 
  - SSL gratis otomatis (HTTPS)
  - Deploy otomatis dari GitHub
  - Custom domain gratis
  - Unlimited bandwidth
  - Form handling
- **Perfect untuk**: Production-ready website

### 2. **Vercel** (Bagus untuk Next.js/React)
- **Website**: [vercel.com](https://vercel.com)
- **Cara**: Connect dengan GitHub, deploy otomatis
- **Domain gratis**: `namakamu.vercel.app`
- **Kelebihan**: Super cepat, edge network global

### 3. **Cloudflare Pages**
- **Website**: [pages.cloudflare.com](https://pages.cloudflare.com)
- **Domain gratis**: `namakamu.pages.dev`
- **Kelebihan**: CDN terbaik di dunia, unlimited bandwidth

### 4. **Render**
- **Website**: [render.com](https://render.com)
- **Domain gratis**: `namakamu.onrender.com`
- **Kelebihan**: Free static site hosting

### 5. **GitHub Pages** (Paling populer untuk portfolio)
- **Domain gratis**: `username.github.io`
- **Kelebihan**: Terintegrasi dengan Git, gratis selamanya

## 💰 Harga Domain Indonesia:

| Domain | Harga/Tahun | Registrar |
|--------|-------------|-----------|
| **.my.id** | Rp 15.000 - 20.000 | Pandi.id, Niagahoster |
| **.id** | Rp 200.000 - 250.000 | Niagahoster, Rumahweb |
| **.com** | Rp 150.000 - 180.000 | Niagahoster, Namecheap |
| **.dev** | Rp 180.000 - 200.000 | Google Domains, Namecheap |

**Rekomendasi**: Kalau budget terbatas, ambil **.my.id** dulu. Murah tapi tetap profesional!

## 🎯 Tips & Trik

### 1. **Dapat Domain Gratis** (Untuk Belajar)
- **Freenom**: Domain gratis .tk, .ml, .ga (tapi kurang profesional)
- **InfinityFree**: Free hosting + subdomain
- **GitHub Student Pack**: Domain .me gratis 1 tahun (kalau mahasiswa)

### 2. **Domain Kustom di Netlify** (Paling Mudah!)
Setelah beli domain .my.id:
1. Login Netlify → Site settings → Domain management
2. Add custom domain → Masukkan `namakamu.my.id`
3. Netlify kasih DNS records
4. Copy DNS ke dashboard domain Anda
5. Tunggu 10-30 menit → DONE! ✨

### 3. **Optimasi SEO**
- Edit meta description di `<head>` index.html
- Tambahkan keywords yang relevan
- Isi semua tag alt pada gambar (ganti icon dengan foto real)
- Submit ke Google Search Console

### 4. **Google Analytics (Gratis)**
Track pengunjung website:
1. Daftar di [analytics.google.com](https://analytics.google.com)
2. Buat property baru
3. Copy tracking code
4. Paste di `<head>` index.html sebelum `</head>`
5. Pantau visitor, pageviews, dll

### 5. **Custom Email dengan Domain**
Kalau mau email profesional (`halo@namakamu.my.id`):
- **Zoho Mail**: Gratis untuk 1 user
- **ImprovMX**: Forward email ke Gmail gratis
- **Cloudflare Email Routing**: Gratis unlimited

### 6. **SSL Certificate (HTTPS)**
Semua platform modern (Netlify, Vercel, Cloudflare Pages, GitHub Pages) sudah auto-enable HTTPS gratis. Tinggal klik satu tombol!

### 7. **Tambahkan Foto Profile Real**
Ganti placeholder di hero & about:
1. Siapkan foto (rekomendasi: 500x500px, format .webp untuk loading cepat)
2. Upload foto ke folder Porto, misal `profile.webp`
3. Edit di index.html:
```html
<!-- Ganti ini -->
<div class="profile-placeholder">
    <i class="fas fa-user"></i>
</div>

<!-- Jadi ini -->
<img src="profile.webp" alt="Profile" style="width: 350px; height: 350px; border-radius: 20px; object-fit: cover;">
```

## 🛠️ Troubleshooting

**Website tidak muncul setelah 5 menit?**
- Cek apakah file `index.html` ada di root folder (bukan di subfolder)
- Pastikan repository bersifat Public
- Cek Settings > Pages apakah sudah di-enable

**Tampilan berantakan?**
- Pastikan ketiga file (HTML, CSS, JS) ada di folder yang sama
- Cek apakah nama file sudah benar (huruf kecil semua)

**Error 404?**
- Tunggu lebih lama (kadang butuh 10-15 menit)
- Clear cache browser (Ctrl + Shift + Del)

## 📞 Support

Jika ada pertanyaan atau kendala:
1. Cek dokumentasi GitHub Pages: [docs.github.com/pages](https://docs.github.com/pages)
2. Tonton tutorial YouTube tentang GitHub Pages

## 📄 Lisensi

Silakan gunakan dan modifikasi template ini sesuka hati! Free 100% 🎉

---

## 🎓 RINGKASAN: Cara Tercepat Publish Seperti Teman Anda

**Pilihan A - Pakai Domain Sendiri (namakamu.my.id):**
1. ✅ Beli domain .my.id di Pandi.id (~Rp 15rb)
2. ✅ Sign up Netlify (gratis)
3. ✅ Drag & drop folder Porto ke Netlify
4. ✅ Connect domain .my.id ke Netlify (copy DNS)
5. ✅ Tunggu 30 menit → Website live! 🎉

**Pilihan B - 100% Gratis (username.github.io):**
1. ✅ Buat akun GitHub
2. ✅ Buat repo: username.github.io
3. ✅ Upload 3 file (index.html, style.css, script.js)
4. ✅ Enable GitHub Pages di Settings
5. ✅ Website live di username.github.io! 🎉

**Rekomendasi Saya:** 
Mulai dengan **GitHub Pages** (gratis) untuk belajar. Kalau nanti mau lebih profesional, tinggal beli domain .my.id (Rp 15rb) dan connect ke **Netlify**. Upgrade kapan aja!

**Selamat membuat portfolio! 🚀**

Website Anda akan segera online seperti: `https://hafidzrdwn.my.id` ✨
