Terakhir adalah async/await. 
Salah satu fitur yang paling ditunggu-tunggu oleh developer Javascript. 
async/await merupakan “coroutine” yang native alias bawaan dari Javascript. 
async/await sendiri dapat digunakan secara native jika kita menggunakan Node mulai dari versi 7.6. 
Untuk versi dibawah itu, kita harus menggunakan babel untuk menerjemahkan sintaks async/await 
ke sintaks yang dimengerti oleh Node.

Penggunaan async/await hampir sama dengan Promise.coroutine bukan ? tidak hanya itu, 
tapi kita dapat menggunakan good ol’ try catch untuk menghandle error di async/await 

Yang perlu kita ingat adalah jangan menggunakan try catch dan .then() .
catch() secara bersamaan untuk menghindari efek yang tidak diinginkan.