# Abedin Car Rental – Sistem Perjanjian Sewa

Laman statik (tanpa build) dengan backend Supabase (projek yang sama dengan sistem Abe Din Auto).

| Fail | Guna |
|---|---|
| `index.html` | Borang Perjanjian Sewa untuk pelanggan |
| `admin.html` | Admin: senarai perjanjian, Edit Dokumen Sewa, stok kereta, harga Customer/Agen, cetak perjanjian, Terma & Syarat |
| `js/sewa.js` | Modul admin (juga digunakan dalam dashboard Abe Din Auto) |
| `V60_SEWA_MIGRATION.sql` | Jadual, storan dokumen dan fungsi Supabase. Jalankan sekali dalam SQL Editor. |

## Pasang
1. Supabase → SQL Editor → jalankan `V60_SEWA_MIGRATION.sql`.
2. GitHub → Settings → Pages → Source: *Deploy from a branch* → `main` / root.
3. Borang: `https://abedinauto.github.io/sewa/` · Admin: `https://abedinauto.github.io/sewa/admin.html`

Login admin guna akaun staf Abe Din Auto (jadual `profiles`, mesti `enabled`).
Owner boleh ubah semua; staf lain boleh isi butiran admin, status dan nota.
