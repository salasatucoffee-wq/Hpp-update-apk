# Salasatu Coffee – HPP & Target Bulanan

Aplikasi HPP satu file (`index.html`). Data tersimpan di browser (localStorage).

## Cara pakai workflow (deploy ke GitHub Pages)

1. Buat repo baru di GitHub, lalu upload semua isi folder ini (termasuk folder `.github`).
2. Buka **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. Push ke branch `main`. Workflow **Deploy ke GitHub Pages** jalan otomatis.
4. Lihat progres di tab **Actions**. Setelah hijau, alamat situs muncul di
   `https://<username>.github.io/<nama-repo>/`.

Bisa juga dijalankan manual: **Actions → Deploy ke GitHub Pages → Run workflow**.

## Isi
- `index.html` – aplikasinya
- `.github/workflows/deploy-pages.yml` – validasi, build, deploy
- `.github/workflows/ci.yml` – cek otomatis untuk pull request
