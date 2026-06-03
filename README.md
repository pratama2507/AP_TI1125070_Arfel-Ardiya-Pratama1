# AP_TI1125070_Arfel-Ardiya-Pratama1

nama : Arfel Ardiya Pratama

NIM : TI1125070

Kelas : TI12D

Program ini mensimulasikan kasir toko sederhana, terdiri dari 3 bagian utama:

1. Prosedur tampilkanMenu() — Tanpa Parameter
cppvoid tampilkanMenu() { ... }
Prosedur ini bertipe void artinya dia tidak mengembalikan nilai apapun ke pemanggil, tugasnya cuma satu yaitu mencetak daftar menu beserta harganya ke layar. Karena isinya sudah tetap, prosedur ini tidak perlu menerima data dari luar sama sekali.

2. Prosedur cetakStruk() — Dengan Parameter
cppvoid cetakStruk(string namaBarang, int harga, int jumlah) { ... }
Beda dengan yang pertama, prosedur ini butuh 3 data masukan supaya bisa bekerja yaitu nama barang, harga satuan, dan jumlah yang dibeli. Dari ketiga data itu, program menghitung total dengan rumus harga × jumlah, lalu hasilnya ditampilkan sebagai struk pembelian.

3. Fungsi main() — Titik Eksekusi Utama
Program selalu mulai berjalan dari sini, urutannya seperti ini:
main() dimulai
    │
    ├─► tampilkanMenu()       → Cetak daftar menu
    │
    ├─► Deklarasi variabel:
    │       produk       = "Sampo Botol"
    │       hargaSatuan  = 15000
    │       kuantitas    = 3
    │
    └─► cetakStruk(produk, hargaSatuan, kuantitas)
                │
                └─► total = 15000 × 3 = 45.000
                    Cetak struk pembelian

Alur Pengiriman Data ke Fungsi
Variabel yang sudah dideklarasikan di main() dikirimkan sebagai argumen ke prosedur cetakStruk(), lalu di dalam prosedur tersebut data itu diterima lewat parameter dan langsung diproses.
main()                         cetakStruk()
──────                         ────────────
produk       ──────────────►  namaBarang
hargaSatuan  ──────────────►  harga
kuantitas    ──────────────►  jumlah
                                    │
                                    ▼
                              total = 15000 × 3
                              = Rp 45.000

Output yang Dihasilkan
=== APLIKASI KASIR TOKO BARU ===
1. Sabun Mandi  : Rp 5.000
2. Sampo Botol  : Rp 15.000
3. Pasta Gigi   : Rp 7.000
--------------------------------

======= STRUK PEMBELIAN =======
Barang      : Sampo Botol
Harga/item  : Rp 15000
Jumlah Beli : 3
--------------------------------
TOTAL BAYAR : Rp 45000
================================

Ringkasan Konsep
Konsep Penjela sanvoid Fungsi tidak mengembalikan nilai Parameter Data yang diterima fungsi dari luar Argumen Nilai yang dikirim saat fungsi dipanggil cout Perintah cetak ke layar endl Pindah baris
