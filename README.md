# Website Profil Padukuhan Mendak

Website statis (HTML/CSS/JS murni, tanpa build step) untuk profil Padukuhan Mendak,
Kalurahan Girisekar, Kapanewon Panggang, Gunungkidul.

## Cara deploy ke Vercel

**Opsi 1 — lewat GitHub (disarankan)**
1. Buat repo baru di GitHub, upload semua file di folder ini (`index.html`, `vercel.json`).
2. Buka https://vercel.com → New Project → Import repo tersebut.
3. Framework Preset pilih **Other**. Build command & output directory dikosongkan saja.
4. Klik Deploy — selesai dalam ~30 detik.

**Opsi 2 — lewat Vercel CLI (tanpa GitHub)**
```bash
npm i -g vercel
cd mendak-site
vercel login
vercel --prod
```

## Bagian yang WAJIB kamu lengkapi sebelum publish

1. **Foto** — semua kotak abu-abu bergaris putus-putus di bagian Galeri, hero,
   dan kartu potensi adalah placeholder. Ganti dengan foto dokumentasi asli
   (`<img src="foto/nama-file.jpg">`), bukan hasil unduhan dari internet, untuk
   menghindari masalah hak cipta.
2. **Data demografi** — jumlah KK, jumlah penduduk, luas wilayah dusun (bagian "Profil & Sejarah").
3. **Struktur pemerintahan** — nama Kepala Dukuh, RT/RW, dan juru kunci Cupu Panjala.
4. **Kontak** — nomor WhatsApp, email, dan akun media sosial resmi.
5. **Program kerja KKN** — tambahkan sebagai item baru di bagian Berita.

## Struktur konten yang sudah diisi otomatis

Bagian sejarah, tradisi Cupu Kyai Panjala, dan berita sudah diisi berdasarkan
sumber publik (situs resmi desagirisekar.gunungkidulkab.go.id, Wikipedia,
Harian Jogja, Espos.id, KabarJawa). Silakan verifikasi ulang ke perangkat
dusun sebelum dipublikasikan resmi, karena detail tradisi lisan bisa berbeda
versi antarwarga.
