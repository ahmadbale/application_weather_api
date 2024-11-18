# LAPORAN HASIL PENGERJAAN WEATHER

### Nama : Agta Fadjrin Aminullah 
### Kelas / No. Absen : SIB 3E / 03
### Nim : 2241760072

<img src=weather.png>

#### Penjelasan

Ketika aplikasi dijalankan, langkah pertama yang dilakukan adalah menentukan lokasi. Aplikasi menggunakan fitur GPS perangkat untuk mendapatkan koordinat (latitude dan longitude) lokasi pengguna saat ini. Setelah lokasi ditemukan, aplikasi secara otomatis mengambil data cuaca berdasarkan koordinat tersebut dari layanan API OpenWeather.
Data yang diambil adalah Suhu (dalam derajat Celcius), Tekanan udara (dalam hPa), Kelembapan udara (dalam persen), Tingkat tutupan awan (dalam persen), dan nama kota yang sesuai dengan koordinat lokasi.

Ketika data cuaca berhasil diterima dari API, aplikasi akan memperbarui tampilan untuk menampilkan informasi tersebut. Jika data belum tersedia (misalnya, saat memuat), aplikasi akan menampilkan indikator loading berbentuk lingkaran yang berputar.

Fungsi utama aplikasi adalah memberikan kemudahan kepada pengguna untuk mengetahui kondisi cuaca saat ini baik berdasarkan lokasi mereka maupun kota lain yang mereka cari.
