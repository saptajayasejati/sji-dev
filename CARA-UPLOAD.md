# Upload ke GitHub Pages

1. Buka github.com → **New repository** → nama: `sji-dev` → **Public** → Create.
2. Klik **uploading an existing file** → seret semua file di folder ini (index.html, terms.html, privacy.html, style.css, icon.png) → **Commit changes**. File CARA-UPLOAD.md ini tidak perlu ikut diunggah.
3. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → **Save**.
4. Tunggu 1-2 menit. Alamatnya: `https://USERNAME.github.io/sji-dev/`

## Isi di TikTok (Basic information)
- Terms of Service URL: `https://USERNAME.github.io/sji-dev/terms.html`
- Privacy Policy URL: `https://USERNAME.github.io/sji-dev/privacy.html`
- Platforms → Web → Website URL: `https://USERNAME.github.io/sji-dev/`

## Verifikasi URL (saat mau ke Production)
1. Di app TikTok → **URL properties** → mode **Production** → **Verify properties** → pilih **URL prefix**.
2. Isi `https://USERNAME.github.io/sji-dev/` → **Verify** → unduh file signature (nama seperti `tiktokXXXX.txt`).
3. Unggah file itu ke repo yang sama (folder root, jangan diganti namanya) → tunggu 1-2 menit → kembali ke TikTok dan klik **Verify**.
4. Satu verifikasi prefix ini mencakup ketiga URL di atas.
