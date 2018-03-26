Promise

Promise hadir secara native di Javascript semenjak ES6. Promise, seperti namanya 
merupakan janji atau kontrak. Analoginya sama seperti pembelian barang tadi, 
bedanya adalah pembeli sudah menyiapkan kontrak yang berlaku apabila barang sudah siap. 
Kontrak tersebut berisi ketentuan yang yang mengatur apa yang harus dilakukan apabila 
kondisi terpenuhi (resolved) atau tertolak (rejected). 

Implementasi promise berbentuk seperti chain atau rantai, yang lebih mudah untuk dibaca 
daripada struktur nested yang dimiliki oleh callback. Namun promise juga memiliki beberapa aturan
antara lain :

    Scope variable yang ada di dalam sebuah block .then() tidak dapat diakses diluar block tersebut (lihat kode yang dicomment pada contoh di atas).
    Promise hanya dapat mengembalikan 1 return value. Kita tidak dapat mengembalikan multiple return value seperti ini resolve(a, b) ;
    Promise bersifat fail fast yang artinya jika ada satu promise yang di-reject, maka akan langsung dilempar ke block .catch() tanpa mengeksekui rantai .then dibawahnya.