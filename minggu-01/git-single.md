Materi RTFM di Repo STMIK Akakom
1.	Instalasi Git
Untuk proses instalasi Git pada perkuliahan semester lalu sebenarnya sudah dilakukan sehingga disini untuk gambarnya mulai dari nomor 13 untuk membuka Git Bash nya.  
1)	Setelah download Git, double click pada file yang di download. Muncullah lisensi Git kemudian klik Next 
2)	Memilih lokasi instalasi secara default C:\Program Files\Git. Lokasi bisa diganti dan dilanjutkan dengan klik Next.
3)	Memilih komponen
4)	Mengisi shortcut untuk menu Start.
5)	Memilih editor yang akan digunakan bersama Git. Disini saya memilih Visual Studio Code.
6)	Memilih antarmuka untuk akses git.
7)	Pilih OpenSSL untuk HTTPS. 
8)	Pilih pilihan pertama untuk konversi akses baris.
9)	Pilih PuTTY untuk terminal yang digunakan untuk mengakses Git Bash
10)	Untuk opsi ekstra, pilih serta aktifkan 1 dan 2.
11)	Kemudian dilakukan proses instalasi.
12)	Muncul dialog pemberitahuan jika proses instalasi telah selesai, klik Finish.
13)	Untuk menjalankannya, klik Start menu dan ketikkan Git. Maka akan muncul seperti berikut.
14)	Tampilan jika akan menggunakan Git Bash
15)	Tampilan jika menggunakan Git GUI
16)	Mencoba dari command prompt. 

2. Konfigurasi Git
Penjelasan : 
Pada semester sebelumya saya sudah melakukan konfigurasi git sehingga tampilan saat sekarang melakukan konfigurasi git hasilnya seperti pada gambar di atas.

3.	Mengelola Repo Sendiri
Membuat Repo 
1)	Klik tanda + pada bagian atas setelah login, kemudian pilih New repository.
2)	Isikan nama, keterangan, serta lisensi. Jika dikehendaki, bisa membuat repo Private
3)	Klik Create repository
 
Clone Repo
Mengelola Repo di Account Sendiri
Mengubah Isi dengan Branching and Merging
Setelah itu, kirim pull request 
Kemudian, dapat di merge :
Setelah itu Confirm merge :
Git pull digunakan untuk melakukan sinkronisasi ke komputer lokal. Perintah git pull dikerjakan pada direktori tempat repo lokal berada. 
Membatalkan Perubahan
Dengan membuat branch saat melakukan perubahan, jika ada perubahan yang sudah kacau maka kekacauan tersebut dapat dihilangkan dan kembali ke kondisi semula
Pada edit-readme-2 ini dilakukan perubahan pengeditan kemudian dilakukan perubahan lagi untuk kembali seperti semula.

Undo Commit Terakhir
Setelah itu, kita akan mengembalikan ke posisi terakhir sebelum commit terakhir dengan perintah git revert HEAD. Perintah tersebut akan membuka editor dan disana kita bisa mengetikkan revert lalu simpan. 
Selanjutnya, push ke repo GitHub.
Jika commit sudah dilakukan, tetapi belum di push ke repo GitHub (masih berada di lokal), cara membatalkannya :
Untuk melakukan perubahan pada saat yang sudah lama, yang perlu dilakukan adalah dengan perintah git revert <posisi> kemudian mengedit secara manual kemudian di push ke repo.
