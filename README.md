# Deploy landing page AEGIS ke Vercel

Website ini mengarahkan juri langsung ke aplikasi analisis publik:
https://aegis-jury-demo2-bbhwk9dwpfgqggfvmjptgd.streamlit.app/
Vercel menayangkan landing page dan materi. Streamlit tetap menjadi host aplikasi.
Juri tidak perlu menginstal AEGIS di komputer lokal.

## Deploy melalui GitHub

1. Ekstrak ZIP, lalu unggah isi folder AEGIS-vercel ke repository website.
2. Import repository tersebut di Vercel.
3. Framework Preset: Other; Root Directory: folder berisi vercel.json.
4. Output Directory: public; Build dan Install Command kosong.
5. Deploy, lalu pastikan URL production dapat dibuka tanpa login.

## Deploy melalui CLI

Dari folder berisi vercel.json:

```bash
npx vercel login
npx vercel --prod
```

## Cek sesudah deploy

- Tombol Coba project membuka aplikasi Streamlit publik.
- ZIP lab minimal dapat diunduh dan diimpor pada aplikasi publik.
- Video, screenshot, slides.html dan PDF dapat dibuka.
- Menu paket aplikasi, paket submission, dan panduan instalasi lokal sudah dihapus.

Video MP4 masih perlu diunggah ke YouTube untuk mengisi formulir lomba.
Status: source siap deploy; deployment Vercel dilakukan oleh pemilik akun.
