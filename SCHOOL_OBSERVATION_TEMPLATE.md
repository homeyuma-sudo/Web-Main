# Template Observasi Tanaman di Sekolah

Gunakan lembar ini saat survei lapangan. Isi berdasarkan apa yang benar-benar terlihat di sekolah; jangan mengisi data yang belum diamati.

## Identitas

- Nama tanaman:
- Slug:
- Tanggal pengamatan:
- Lokasi di sekolah:
- Jumlah / perkiraan jumlah:

## Kondisi dan ciri

- Kondisi tanaman:
- Ciri daun:
- Ciri batang:
- Ciri bunga:
- Ciri buah:
- Ciri lain yang terlihat:

## Catatan lapangan

- Lingkungan sekitar:
- Hal menarik:
- Catatan tambahan:

## Foto

Ambil foto yang konsisten untuk setiap tanaman:

- Foto lokasi/konteks: menunjukkan posisi tanaman di lingkungan sekolah.
- Foto tanaman utuh: menunjukkan bentuk keseluruhan.
- Foto daun: untuk membantu verifikasi identitas.
- Foto detail: bunga, buah, batang, atau ciri khas lain.

## Data untuk backend

Simpan hasilnya pada objek `observasiSekolah`:

```js
{
  tanggal: "",
  lokasi: "",
  jumlah: "",
  kondisi: "",
  ciriTeramati: [],
  catatan: "",
  fotoLokasi: "",
  fotoTanaman: "",
  fotoDaun: "",
  fotoDetail: ""
}
```

## Botanical Globe

Untuk data globe tetap pisahkan antara:

- `countries`: ID negara yang mewakili asal/persebaran botani.
- `label`: ringkasan wilayah asal/persebaran.
- `focus`: titik awal kamera globe `[latitude, longitude]`.

Observasi sekolah tidak menggantikan data asal botani.
