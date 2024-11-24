# Aplikasi Perkiraan Cuaca
**Siti Aisyah Nor Fitriani - 2210010043 - UTS**

## Deskripsi Aplikasi
Aplikasi **Perkiraan Cuaca Sederhana** adalah aplikasi berbasis Java Swing yang memungkinkan pengguna untuk mendapatkan informasi cuaca terkini dari berbagai kota di dunia menggunakan API dari OpenWeatherMap. Aplikasi ini juga mendukung fitur pengelolaan data, seperti menyimpan ke file CSV, memuat data dari file CSV, dan menambahkan lokasi favorit.

---

## Fitur Utama

- **Cek Cuaca:**
  - Memeriksa kondisi cuaca terkini untuk kota tertentu menggunakan API OpenWeatherMap.
  - Menampilkan suhu, kelembapan, deskripsi kondisi cuaca, dan ikon cuaca.

- **Lokasi Favorit:**
  - Menyimpan kota favorit pengguna untuk akses cepat.
  - Memilih lokasi favorit akan secara otomatis memperbarui data cuaca untuk kota tersebut.

- **Kelola Data:**
  - Menampilkan data cuaca dalam tabel.
  - Menyimpan data cuaca ke file CSV.
  - Memuat data cuaca dari file CSV.

- **Hapus Data:**
  - Menghapus baris tertentu dari tabel data cuaca.

---

## Cara Menggunakan Aplikasi

### 1. Cek Cuaca
1. Masukkan nama kota di **input lokasi**.
2. Klik tombol **Cek Cuaca** untuk mendapatkan informasi cuaca.
3. Informasi akan ditampilkan di tabel, termasuk:
   - Tanggal
   - Lokasi
   - Kondisi cuaca
   - Suhu (°C)
   - Kelembapan (%)

### 2. Tambah Lokasi Favorit
1. Masukkan nama kota di **input lokasi**.
2. Klik tombol **Tambah Favorit** untuk menambahkannya ke daftar favorit.
3. Kota favorit akan muncul di dropdown **Lokasi Favorit**.

### 3. Pilih Lokasi Favorit
1. Pilih kota dari dropdown **Lokasi Favorit**.
2. Informasi cuaca akan otomatis diperbarui untuk kota tersebut.

### 4. Hapus Data
1. Pilih baris data cuaca di tabel.
2. Klik tombol **Hapus** untuk menghapus baris yang dipilih.

### 5. Simpan Data
1. Klik tombol **Simpan** untuk menyimpan data cuaca di tabel ke file CSV.
2. Pilih lokasi penyimpanan file melalui dialog file.

### 6. Muat Data
1. Klik tombol **Muat Data** untuk memuat data cuaca dari file CSV.
2. Data dari file akan dimuat ke tabel.

### 7. Keluar
1. Klik tombol **Keluar** untuk menutup aplikasi.
2. Akan muncul dialog konfirmasi sebelum aplikasi keluar.

---

### DEMO


## Format File CSV
File CSV yang dihasilkan atau dimuat harus memiliki format berikut:

| Tanggal       | Kota       | Kondisi       | Suhu    | Kelembapan |
|---------------|------------|---------------|---------|------------|
| yyyy-mm-dd    | Nama Kota  | Deskripsi     | °C      | %          |

---

## Teknologi yang Digunakan
- **Bahasa Pemrograman:** Java
- **GUI Framework:** Java Swing
- **API Cuaca:** OpenWeatherMap
- **Penyimpanan File:** CSV

---

## API OpenWeatherMap
Untuk menggunakan aplikasi ini, pastikan Anda memiliki **API Key** dari [OpenWeatherMap](https://openweathermap.org/). Ganti nilai `apiKey` di dalam kode dengan API Key Anda.

```java
private String apiKey = "your_api_key_here";
