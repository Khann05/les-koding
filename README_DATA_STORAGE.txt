# Penyimpanan Data

Data website ini sudah dipisah dari file tampilan.

## Data murid, absen, progress, kode parent
Tersimpan di:
data/les-koding.db

## File upload PPT, cover, sertifikat
Tersimpan di:
uploads/

## File tampilan/kode
Tersimpan di:
public/
server.js
database.js

Artinya:
- Kalau kamu ubah style.css, parent.html, atau app.js, data di database tidak ikut hilang.
- Data hilang hanya kalau folder data/ atau uploads/ ikut terhapus, atau hosting gratis mereset storage.
- Untuk Railway free, storage bisa tidak permanen jika redeploy/restart tertentu.
- Untuk aman jangka panjang, pakai VPS atau database/cloud storage permanen.
