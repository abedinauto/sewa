# Abedin Car Rental – Sistem Perjanjian Sewa

Laman statik (tanpa build) dengan backend Supabase projek **abedinauto's Project** (`abqrgiebeoyzowvxeggj`). Pangkalan data sudah dipasang.

| Fail | Guna |
|---|---|
| `index.html` | Borang Perjanjian Sewa untuk pelanggan |
| `admin.html` | Admin: senarai perjanjian, Edit Dokumen Sewa, stok kereta, harga Customer/Agen, cetak perjanjian, Terma & Syarat |
| `js/sewa.js` | Modul admin (juga digunakan dalam dashboard Abe Din Auto) |
| `V60_SEWA_MIGRATION.sql` | Jadual, storan dokumen dan fungsi Supabase. Jalankan sekali dalam SQL Editor. |

## Pasang
1. Pangkalan data: sudah dipasang (jadual `profiles`, `sewa_*`, bucket `sewa-docs`).
2. GitHub → Settings → Pages → Source: *Deploy from a branch* → `main` / root.
3. Borang: `https://abedinauto.github.io/sewa/` · Admin: `https://abedinauto.github.io/sewa/admin.html`

Login admin: akaun Owner ialah bahaniaga@gmail.com. Staf daftar sendiri di `admin.html`
("Daftar akaun staf baharu"), kemudian Owner aktifkan di tab 👤 Staf.
Owner boleh ubah semua; staf boleh isi butiran admin, status dan nota.
No WhatsApp untuk butang selepas hantar borang ditetapkan di tab ⚙ Tetapan.
