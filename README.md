# AP_TI1125070_Arfel-Ardiya-Pratama1

nama : Arfel Ardiya Pratama

NIM : TI1125070

Kelas : TI12D

Struktur Program
Program ini mensimulasikan sistem kasir toko sederhana yang terdiri dari tiga bagian utama, yaitu dua prosedur dan satu fungsi main sebagai titik awal eksekusi.

1. Prosedur tampilkanMenu()
Prosedur ini bertipe void yang berarti tidak mengembalikan nilai apapun setelah selesai dijalankan. Tugasnya hanya mencetak daftar produk beserta harganya ke layar menggunakan perintah cout. Karena isi tampilannya sudah tetap dan tidak bergantung pada data dari luar, prosedur ini tidak memiliki parameter sama sekali. Setiap kali dipanggil, outputnya akan selalu sama.

2. Prosedur cetakStruk()
Prosedur ini juga bertipe void, namun berbeda dengan sebelumnya karena membutuhkan tiga parameter input yaitu namaBarang bertipe string, harga bertipe int, dan jumlah bertipe int. Ketiga parameter tersebut digunakan untuk menghitung total harga dengan rumus harga * jumlah, kemudian hasilnya ditampilkan dalam format struk pembelian. Karena menggunakan parameter, prosedur ini bersifat dinamis dan bisa menghasilkan output yang berbeda tergantung data yang dikirimkan saat pemanggilan.

3. Fungsi main()
Fungsi ini adalah titik awal eksekusi program, artinya semua instruksi mulai dijalankan dari sini secara berurutan dari atas ke bawah. Pertama, fungsi main() memanggil tampilkanMenu() untuk menampilkan daftar produk. Setelah itu, tiga variabel dideklarasikan yaitu produk berisi nama barang, hargaSatuan berisi harga per item, dan kuantitas berisi jumlah pembelian. Ketiga variabel tersebut kemudian dikirimkan sebagai argumen ke prosedur cetakStruk(), yang lalu memproses data itu dan mencetak struk dengan total harga Rp 45.000 hasil dari 15.000 dikali 3.

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

Ringkasan Konsep yang Digunakan
KonsepPenjelasanvoidFungsi tidak mengembalikan nilai apapunParameterData yang diterima fungsi dari luar saat dipanggilArgumenNilai aktual yang dikirim ke fungsi saat pemanggilancoutPerintah untuk mencetak output ke layarendlDigunakan untuk pindah ke baris baru
