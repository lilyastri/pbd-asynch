Callback

Callback function atau callback (biasa disingkat dengan cb) adalah salah satu metode yang paling umum 
yang digunakan untuk menghandle return value dari operasi asynchoronous. Konsep callback dapat dianalogikan 
seperti kita memanggil penjual untuk membeli sesuatu dan sembari menunggu penjual mempersiapkan barangnya, 
kita pergi melakukan hal lain. Lalu, ketika barangnya sudah siap, penjual akan memanggil balik (callback) 
untuk memberitahu kita bahwa barang sudah siap dan kita dapat menentukan tindakan selanjutnya dari pembelian barang tadi.

Callback sendiri adalah sebuah regular function (yang biasanya anonymous) dan ditaruh di argumen paling belakang dari
sebuah asynchronous function. Layaknya function biasa, callback juga dapat menerima parameter dan mengembalikan value. 
Berikut adalah contoh pengaplikasian callback.