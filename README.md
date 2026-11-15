# 📝 CRUD To-Do List App (React Native & Firebase)

Aplikasi *To-Do List* sederhana berbasis mobile yang dibangun menggunakan **React Native**, **Expo**, dan **Firebase Firestore** untuk mendukung fungsionalitas CRUD (*Create, Read, Update, Delete*) secara *real-time*.

---

## 📱 Fitur Utama
* **Create (Tambah Tugas):** Menambahkan daftar kegiatan atau tugas baru dengan mudah.
* **Read (Tampilkan Data):** Menampilkan daftar tugas secara *real-time* dari database Firestore yang diurutkan berdasarkan waktu pembuatan terbaru.
* **Update (Ubah/Edit Tugas):** Memperbarui isi teks tugas yang sudah ada melalui halaman detail terpisah.
* **Delete (Hapus Tugas):** Menghapus tugas dari daftar dan database secara instan.
* **Navigasi Stack:** Menggunakan `@react-navigation/native` untuk perpindahan antar halaman (*Home* dan *Detail*).

---

## 🛠️ Teknologi yang Digunakan
* **React Native / Expo** (Framework Pengembangan Mobile)
* **Firebase Firestore** (Basis Data Cloud NoSQL *Real-time*)
* **React Navigation** (Manajemen Navigasi Layar)
* **Vector Icons (@expo/vector-icons)** (Ikon antarmuka)

---

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
