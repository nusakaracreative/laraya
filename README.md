# LARAYA — Dashboard Operasional

Status: prototype/demo, belum siap untuk operasional nyata.

Dashboard dan katalog produk saat ini menggunakan data contoh di frontend. Filter laporan belum menghitung ulang data dari sumber produksi. Tambah/edit produk, pengaturan stok, impor, notifikasi, autentikasi, otorisasi, dan database belum terbukti terintegrasi pada repository ini.

Jangan gunakan angka contoh untuk keputusan bisnis atau memasukkan data pelanggan dan transaksi nyata.

Sebelum produksi: audit backend dan database, tentukan sumber kebenaran untuk transaksi/stok/HPP/pembayaran/cabang, integrasikan API, tambahkan audit trail dan hak akses, lalu uji regresi dan responsivitas.

Branch `fix/dashboard-audit-remediation` memperjelas status demo pada dashboard dan katalog serta memperbaiki feedback antarmuka. Perubahan ini tidak mengklaim backend sudah tersedia.