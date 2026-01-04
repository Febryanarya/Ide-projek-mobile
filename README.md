# Ide-projek-mobile


MerbabuAccess

Aplikasi mobile untuk sistem booking dan manajemen pendakian Gunung Merbabu berbasis Flutter, terinspirasi dari booking.tngunungmerbabu.org.

 Fitur Utama

•Daftar Paket: Lihat paket pendakian (Selo, Suwanting, Wekas) dengan harga & kuota

•Detail & Booking: Pilih tanggal, jumlah orang, isi data anggota

•Keranjang & Bayar: Hitung total, unggah bukti transfer

•Tiket Digital: QR Code untuk check-in di pos pendakian

•Lacak Status: Pantau status booking (pending, confirmed, done)

•Login/Register: Akun pribadi untuk riwayat pendakian

Teknologi

•Flutter + Dart (Frontend)

•Firebase (Auth, Database, Storage)

•Package: qr_flutter, http, intl, provider

Struktur Folder

lib/

├── screens/

│   ├── auth/       # Login, Register

│   ├── home/       # Dashboard, Daftar Paket

│   ├── booking/    # Form booking, Checkout

│   ├── ticket/     # Tiket QR Code

│   └── profile/    # Riwayat, Data Diri

├── models/         # Data class

├── services/       # Firebase, API

└── widgets/        # Komponen UI
