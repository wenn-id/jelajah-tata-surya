# Jelajah Tata Surya

Website 3D yang menerbangkan kamera dari Matahari melewati delapan planet, tiga planet katai, dan bulan-bulan besarnya, cukup dengan menggulir halaman. Dibuat dengan [Three.js](https://threejs.org) dan shader GLSL prosedural, tanpa satu file gambar atau audio pun.

## Fitur

- **Perjalanan lewat scroll**: Matahari, Merkurius, Venus, Bumi, Mars, Ceres, Jupiter, Saturnus, Uranus, Neptunus, Pluto, Eris, lalu tampilan peta seluruh orbit.
- **Permukaan prosedural**: awan dan lampu kota Bumi, Bintik Merah Raksasa Jupiter, cincin Saturnus lengkap dengan Celah Cassini dan bayangannya, cincin tipis Uranus dan Neptunus, hati Tombaugh Regio di Pluto.
- **Bulan-bulan besar**: Bulan, Io, Europa, Ganymede, Callisto, Titan, Charon, dan Dysnomia.
- **Klik untuk detail**: klik objek mana pun untuk zoom dan membuka panel info. Seret untuk memutar, roda mouse untuk zoom, Esc untuk kembali.
- **Musik ambient**: disintesis langsung dengan Web Audio API, makin gelap makin jauh dari Matahari.
- **Mode skala asli**: ukuran dan jarak berubah ke perbandingan sebenarnya, dengan label untuk menemukan planet yang tinggal berupa titik.

## Menjalankan

Semuanya ada di satu file, `index.html`. Three.js dimuat dari CDN jsDelivr, jadi perlu koneksi internet.

Buka langsung di browser, atau jalankan server lokal:

```bash
npx serve .
```

## Catatan

Jarak dan ukuran pada mode default dipadatkan supaya muat di layar. Angka fakta di setiap bagian memakai nilai rata-rata yang umum dipakai.
