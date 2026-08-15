# 💵 Tip Calculator App - Jetpack Compose

Aplikasi Android sederhana berbasis **Jetpack Compose** untuk menghitung persentase tip kustom secara otomatis dan reaktif. Proyek ini disusun sebagai pemenuhan **Tugas 4 Praktikum Google Developer Codelab**.

---

## 📌 Deskripsi Aplikasi
Aplikasi ini memungkinkan pengguna untuk memasukkan jumlah total tagihan (*Bill Amount*) dan menentukan persentase tip (*Tip Percentage*). Hasil kalkulasi tip dihitung secara otomatis saat pengguna mengetik angka tanpa memerlukan tombol konfirmasi tambahan.

---

## 🚀 Fitur & Konsep Utama
* **State Hoisting & Reusability:** Penggunaan komponen `EditNumberField` reusable yang dikontrol menggunakan `remember` dan `mutableStateOf`.
* **Dynamic & Reactive UI:** Menggunakan `TextField` yang langsung merender ulang nilai kalkulasi tip (*re-composition*) saat nilai input berubah.
* **Safe Input Processing:** Menghindari aplikasi *crash* dari input kosong atau karakter non-angka dengan implementasi `toDoubleOrNull() ?: 0.0`.
* **Format Mata Uang:** Menampilkan hasil nominal tip terformat rapi sesuai mata uang Rupiah (`NumberFormat.getCurrencyInstance`).

---

## 🛠️ Teknologi & Tools
* **Language:** Kotlin
* **UI Framework:** Jetpack Compose (Material 3)
* **Minimum SDK:** 24 (Android 7.0)
* **Target SDK:** 35
* **IDE:** Android Studio

---

## 👤 Identitas Mahasiswa
* **Nama:** Naufal Aqilla Falih Fadlurahman
* **Kelas:** TI-A2
* **NIM:** 452024611048
