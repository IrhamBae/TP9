# TP9

Test Case ID | Test Suite Name | Description | Steps | Test Data | Expected Result | Actual Result | Pass/Fail | Remarks
TC_01 | ABC | Validasi nama pengguna | 1. Buka form registrasi2. Isi nama < 3 karakter3. Klik submit | Nama: "Al" | Error: "Nama harus 3–30 karakter" | Error ditampilkan sesuai | Pass | 
TC_02 | ABC | Validasi format email pengguna | 1. Buka form registrasi2. Isi email tidak valid (misal: abc123)3. Klik submit | Email: abc123 | Error: "Format email tidak valid" | Error ditampilkan sesuai | Pass | 
TC_03 | ABC | Validasi nomor HP | 1. Buka form registrasi2. Isi nomor HP dengan huruf3. Klik submit | Nomor HP: 08123abc456 | Error: "Nomor HP harus 10–13 digit angka" | Error ditampilkan sesuai | Pass | 
TC_04 | ABC | Validasi panjang password | 1. Buka form registrasi2. Isi password < 8 karakter3. Klik submit | Password: 12345 | Error: "Password harus 8–20 karakter" | Error ditampilkan sesuai | Pass | 
TC_05 | ABC | Validasi harga barang | 1. Buka form tambah barang2. Isi harga < Rp1.0003. Klik submit | Harga: 500 | Error: "Harga harus antara Rp1.000–Rp5.000.000" | Error ditampilkan sesuai | Pass | 
TC_06 | ABC | Validasi panjang deskripsi barang | 1. Buka form tambah barang2. Isi deskripsi < 10 karakter3. Klik submit | Deskripsi: "Bagus" | Error: "Deskripsi harus 10–500 karakter" | Error ditampilkan sesuai | Pass | 
TC_07 | ABC | Validasi stok barang | 1. Buka form tambah barang2. Isi stok = 03. Klik submit | Stok: 0 | Error: "Stok harus antara 1–100" | Error ditampilkan sesuai | Pass | 
TC_08 | ABC | Validasi jumlah gambar barang | 1. Buka form tambah barang2. Upload 6 gambar3. Klik submit | Gambar: 6 file | Error: "Maksimal 5 gambar dapat diunggah" | Error ditampilkan sesuai | Pass | 
TC_09 | ABC | Validasi panjang judul barang | 1. Buka form tambah barang2. Isi judul < 5 karakter3. Klik submit | Judul: "Buku" | Error: "Judul harus 5–50 karakter" | Error ditampilkan sesuai | Pass | 
TC_10 | ABC | Validasi pemilihan kategori barang | 1. Buka form tambah barang2. Biarkan kategori kosong3. Klik submit | Kategori: kosong | Error: "Kategori wajib dipilih dari daftar yang tersedia" | Error ditampilkan sesuai | Pass | 
