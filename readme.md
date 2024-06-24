# Dokumentasi untuk REST API yang ada di https://ikad-developer.my.id

## Daftar Isi

- [Data API Jurusan Teknik Elektro dan komputer - UNG](#data-api-jurusan-teknik-elektro-dan-komputer)
- [Dokumentas Google Drive](#google-drive)
- [Penggunaan Whatsapp](#whatsapp-api)
- [Catatan Tambahan](#catatan-tambahan)
    - [konversi tanggal keformat tanggal Indonesia ](#1-konversi-tanggal-ke-format-tanggal-indonesia)
    - [Merubah Angka ke format Rupiah](#2-merubah-angka-ke-format-rupiah)
    - [Mencegah SQL Injection dengan Real Escape String](#3-mencegah-sql-injection-dengan-real-escape-string)
    - [Membangun Web server dengan docker di server Armbian](#4-membangun-web-server-dengan-docker-di-server-armbian)
    - [Menginstall Database MYSQL-Server di ubuntu dan Docker Container](#5-menginstall-database-mysql-server-di-ubuntu-dan-docker-container)
    - [Menginstall Whatsapp Gateway di Docker Container](#6-menginstall-whatsapp-gateway-di-docker-container)
    - [Script Backup data otomatis dengan php (Support server linux atau windows)](#7-script-backup-data-otomatis-dengan-php-support-server-linux-atau-windows)

## Data API Jurusan Teknik Elektro dan Komputer

Pada dasarnya data yang ditampilkan sama dengan data yang di website resmi Jurusan Teknik Elektro dan Komputer (https://elektro.ft.ung.ac.id)

Endpoint ```https://ikad-developer.my.id/elektro``` dengan method GET

|Endpoint | Keterangan | Script Postman |
| ------- | ---------- | -------------- |
| data-publikasi | Menampilkan Data Publikasi seluruh Dosen | ```curl --location 'https://api.ikad-developer.my.id/elektro/data-publikasi'``` | 
| statistik-publikasi | Menampilkan jumlah publikasi berdasarkan tahun| ```curl --location 'https://api.ikad-developer.my.id/elektro/statistik-publikasi'``` |
| list-gambar-beranda | Menampilkan gambar yang ada di beranda | ```curl --location 'https://api.ikad-developer.my.id/elektro/list-gambar-beranda'``` |
| list-berita | Menampilkan berita tentang aktifitas jurusan atau kegiatan mahasiswa | ```curl --location 'https://api.ikad-developer.my.id/elektro/list-berita'``` |
| list-agenda | Menampilkan agenda tentang aktifitas jurusan atau kegiatan mahasiswa | ```curl --location 'https://api.ikad-developer.my.id/elektro/list-berita'``` |
| list-pengumuman | Menampilkan pengumuman | ```curl --location 'https://api.ikad-developer.my.id/elektro/list-pengumuman'``` |
| list-artikel | Menampilkan artikel dosen | ```curl --location 'https://api.ikad-developer.my.id/elektro/list-artikel'``` |
| struktur-organisasi | Menampilkan struktur organisasi jurusan pada saat ini | ```curl --location 'https://api.ikad-developer.my.id/elektro/struktur-organisasi'``` |
| daftar-dosen | Menampilkan seluruh dosen aktif yang ada di jurusan Teknik Elektro dan Komputer - UNG | ```curl --location 'https://api.ikad-developer.my.id/elektro/daftar-dosen'``` |
| program-studi | Menampilkan data program studi dari pengelola program studi sampai pada matakuliah yang ada di program studi | ```curl --location 'https://api.ikad-developer.my.id/elektro/program-studi'``` |
| dokumen-akademik | Menampilkan segala dokumen tentang akademik | ```curl --location 'https://api.ikad-developer.my.id/elektro/dokumen-akademik'``` |
| dokumen-akreditas | Menampilkan segala dokumen tentang akreditas | ```curl --location 'https://api.ikad-developer.my.id/elektro/dokumen-akreditas'``` |
| laporan-kinerja | Menampilkan laporan kinerja pengelolah jurusan atau program studi | ```curl --location 'https://api.ikad-developer.my.id/elektro/laporan-kinerja'``` |
| statistik-mahasiswa | Menampilkan data mahasiswa yang masuk atau keluar 5 tahun terakhir | ```curl --location 'https://api.ikad-developer.my.id/elektro/statistik-mahasiswa'``` |
| data-alumni | Menampilkan data alumni | ```curl --location 'https://api.ikad-developer.my.id/elektro/data-alumni'``` |

## Google Drive

## Whatsapp API

## Catatan tambahan

### 1. Konversi tanggal ke format tanggal Indonesia

### 2. Merubah Angka ke format Rupiah

### 3. Mencegah SQL Injection dengan Real Escape String

### 4. Membangun Web server dengan docker di server Armbian

### 5. Menginstall Database MYSQL-Server di ubuntu dan Docker Container

### 6 Menginstall Whatsapp Gateway di Docker Container

### 7 Script Backup data otomatis dengan php (Support server linux atau windows)
