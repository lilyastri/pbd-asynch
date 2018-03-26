Apa bedanya synchronous dan asynchronous ? 

1. Pengertian

a.      Transmisi Synchronous
Merupakan suatu pengiriman data yang dikirim dengan kecepatan tinggi dan data yang dikirim pada block, 
dimana setiap block data akan dicek ulang oleh : Block Check Character (BCC). Transmisi ini digunakan 
untuk transmisi data dengan kecepatan yang tinggi.

b.      Transmisi Asynchronous
Transmisi asinkron digunakan apabila pengiriman data dilakukan satu karakter setiap kali pengiriman. 
Transmisinya dilakukan dengan cara memberikan bit awal (start bit)pada setiap awal pengiriman karakter 
dan diakhiri dengan bit akhir (stop bit).

1. Perbedaan
 
Synchronous
proses pengirim dan penerima yang diatur sedemikian rupa sehingga memiliki pengaturan yang sama, 
sehingga dapat diterima dan dikirim dengan baik. umumnya pengaturan ini didasarkan pada waktu dalam 
mengirimkan sinyal.  waktu ini diatur oleh denyut listrik secara periodik yang disebut clock . 
dengan kata lain synchronous adalah sistem operasi untuk kejadian yang terjadi pada waktu bersamaan, 
berkelanjutan dan dapat diprediksi. contoh: chating.

Asynchronous
proses komunikasi data yang tidak tergantung dengan waktu yang tetap. proses transformasi data kecepatanya, 
cukup relatif dan tidak tetap. metode komunikasi serial dari satu perangkat ke perangkat lainnya. 
data dikirimkan perbit persatuan waktu. tiap simbol yang dikirimkan mempunyai start bit dan stop bit, 
untuk melakukan sinkronisasi dari suatu device pengirim dan penerima. interval yang terjadi antar satu 
karakter dengan karakter lainnya dapat bervariasi.  asynchronous merupakan operasi yang tidak bergantung waktu.

Link Direktori Promise : https://github.com/lilyastri/pbd-asynch/tree/master/promise
Link Direktori callback : https://github.com/lilyastri/pbd-asynch/tree/master/callback
Link Direktori async-await : https://github.com/lilyastri/pbd-asynch/tree/master/async-await
