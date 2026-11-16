# 📱 CRUD To-Do List App (React Native & Firebase)

[![Platform](https://img.shields.io/badge/platform-React%20Native%20%7C%20Expo-blue)](https://reactnative.dev/)
[![Database](https://img.shields.io/badge/database-Firebase%20Firestore-orange)](https://firebase.google.com/)
[![Status](https://img.shields.io/badge/status-Active%20%2F%20Completed-success)](https://github.com/jannfth/CrudToDoList)

Dokumentasi dan kode sumber aplikasi *To-Do List* berbasis mobile yang dikembangkan menggunakan **React Native**, **Expo**, dan **Firebase Firestore**.

---

## 📖 Tentang Repositori

Repositori ini berisi kode sumber aplikasi manajemen tugas (*To-Do List*) sederhana yang menerapkan fungsi CRUD (*Create, Read, Update, Delete*) secara *real-time*. Di dalamnya terdapat struktur kode navigasi, integrasi basis data awan (*cloud database*), serta antarmuka pengguna yang bersih.

---

## 📂 Isi Repositori

Struktur direktori utama dari proyek ini:

* **`Screens/`** — Berisi komponen halaman utama (*Home.js*) untuk daftar tugas & form input, serta halaman detail (*Detail.js*) untuk memperbarui tugas.
* **`TodosApp/`** — Berisi aset atau modul pendukung aplikasi.
* **`App.js`** — Berisi konfigurasi utama dan sistem navigasi tipe *Stack*.
* **`config.js`** — Berisi file konfigurasi koneksi ke Firebase Firestore.

---

## 🛠️ Fitur Utama

* **Create (Tambah Tugas):** Menambahkan daftar kegiatan atau tugas baru secara instan.
* **Read (Tampilkan Data):** Menampilkan daftar tugas *real-time* dari Firestore yang diurutkan dari waktu terbaru.
* **Update (Ubah Tugas):** Memperbarui teks tugas yang sudah ada melalui halaman khusus.
* **Delete (Hapus Tugas):** Menghapus tugas dari daftar aplikasi dan basis data.

---

## 🚀 Panduan Instalasi & Menjalankan Proyek

1. **Clone repositori ini:**
   ```bash
   git clone [https://github.com/jannfth/CrudToDoList.git](https://github.com/jannfth/CrudToDoList.git)

---

## 📸 Galeri Pengujian

> 💡 *Tips: Ganti nama file gambar di bawah ini sesuai dengan nama file screenshot yang kamu upload ke repositori agar gambarnya langsung muncul di halaman depan GitHub!*

| Pembuatan Website (Designer / Blocks) | Pengujian di Perangkat (Mobile App) |
| :---: | :---: |
| <img src="Tes.png" width="350" alt="Web Test"> |

## 📂 Struktur Proyek
```text
CrudToDoList/
│
├── Screens/
│   ├── Home.js       # Halaman utama (Daftar tugas, form input, hapus, navigasi)
│   └── Detail.js     # Halaman edit/pembaruan tugas
│
├── config.js         # Konfigurasi koneksi Firebase Firestore
├── App.js            # Titik awal aplikasi & Stack Navigator
└── package.json      # Daftar dependencies proyek
