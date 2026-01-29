# 📝 Git Commit Guidelines

Panduan ini mengikuti standar **Conventional Commits** untuk memastikan riwayat perubahan kode (history) tetap bersih, terstruktur, dan mudah dibaca oleh manusia maupun mesin.

## 🏗️ Format Dasar

---

## 🚀 Tipe Commit (Types)

Gunakan salah satu dari tipe berikut sesuai dengan perubahan yang dilakukan:

| Tipe | Keterangan |
| :--- | :--- |
| **feat** | Penambahan fitur baru (New feature). |
| **fix** | Perbaikan bug (Bug fix). |
| **docs** | Perubahan pada dokumentasi (README, Wiki, dll). |
| **style** | Perubahan format kode (Linting, spasi, titik koma) tanpa mengubah logika. |
| **refactor** | Perubahan kode yang bukan fitur maupun perbaikan bug (Optimasi struktur). |
| **perf** | Perubahan kode untuk meningkatkan performa. |
| **test** | Menambah atau memperbaiki unit test. |
| **chore** | Tugas rutin/maintenance (Update library, konfigurasi build, `.gitignore`). |
| **revert** | Membatalkan (revert) commit sebelumnya. |

---

## 📏 Aturan Penulisan

1. **Gunakan Kalimat Perintah (Imperative):** Tulis `feat: add feature`, bukan `feat: added feature`.
2. **Huruf Kecil:** Gunakan huruf kecil untuk tipe dan deskripsi awal.
3. **Tanpa Titik:** Jangan akhiri baris subjek dengan tanda titik.
4. **Batas Karakter:** Usahakan baris pertama tidak lebih dari **50 karakter**.
5. **Deskripsi Detail (Opsional):** Jika perlu penjelasan tambahan, pisahkan dengan satu baris kosong setelah subjek.

---

## 💡 Contoh Penggunaan

### Commit Sederhana
`feat: add dark mode support to settings screen`

### Commit dengan Deskripsi
fix: resolve memory leak in background service

The service was not properly unsubscribing from the location updates, causing a leak when the app was closed.


### Perubahan Konfigurasi
`chore: update dependencies to latest version`
