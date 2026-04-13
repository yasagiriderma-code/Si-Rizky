# Si Rizky — Game Download Page

Halaman download APK game **Si Rizky** yang siap di-deploy ke GitHub Pages.

## Struktur Repo

```
si-rizky-game/
├── index.html              ← halaman utama
└── assets/
    ├── preview1.jpeg       ← screenshot game
    ├── preview2.jpeg       ← screenshot game
    ├── videopreview.mp4    ← video gameplay
    └── SiRisky-v1_0_0.apk ← file APK
```

## Deploy ke GitHub Pages

1. Upload semua file ini ke repo GitHub kamu
2. Buka **Settings → Pages**
3. Pilih **Source: Deploy from a branch → main → / (root)**
4. Simpan → tunggu beberapa menit
5. Situsmu live di: `https://username.github.io/nama-repo/`

## Cara Update APK

Ganti file di `assets/` dan update baris ini di `index.html`:

```html
<a class="dlbtn" href="assets/NamaFile.apk" download="NamaFile.apk" onclick="showToast('v2.0.0')">Unduh</a>
```

Dan update info versi:
```html
<div class="ver">v2.0.0</div>
<div class="inf">XX MB · Android 6.0+ · 2025</div>
```
