# Quest Hanyu AI v1

Versi ini ialah aplikasi PWA modular, bukan mockup Canva.

## Fungsi tersedia
- profil dan avatar murid
- peta lima dunia
- cerita interaktif
- soalan pilihan jawapan
- aktiviti padanan
- aktiviti susun ayat
- cabaran naga dengan HP
- bintang, kristal dan dunia terkunci
- Pasport Bahasa Cina
- halaman guru dan rekod asas
- penyimpanan kemajuan pada peranti
- pemasangan PWA dan sokongan luar talian

## Kandungan rasmi
Kandungan pembelajaran berada dalam:

`data/content.js`

Fail itu masih menggunakan placeholder. Jangan isi dengan kandungan rekaan.
Gunakan hanya bahan rasmi buku teks Tahun 1 SK Unit 1–5 yang telah disahkan.

## Deploy ke Cloudflare Pages
1. Nyahzip folder.
2. Pastikan `index.html` berada terus di root folder.
3. Di Cloudflare: Workers & Pages → Create → Pages → Upload assets.
4. Seret keseluruhan folder yang telah dinyahzip, bukan fail ZIP.
5. Deploy.
6. Buka URL `.pages.dev`.

## Uji secara tempatan
Gunakan VS Code + Live Server, atau:
`python -m http.server 8000`

Kemudian buka:
`http://localhost:8000`
