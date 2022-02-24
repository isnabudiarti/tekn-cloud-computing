Git untuk Kolaborasi
Disini saya berkolaborasi dengan teman saya yaitu Arawidhi.
Dalam pembahasan ini :
1.	Upstream author adalah Arawidhi.
2.	Contributor adalah isnabudiarti.
3.	Repo dari upstream author adalah Praktikum01 
 

Fork 
1.	Login ke GitHub.
2.	Akses repo yang akan di fork
3.	Pada sisi kanan atas, klik Fork :
4.	Pilih akan ditempatkan di account mana. Karena disini saya hanya memiliki satu account maka langsung ke account isnabudiarti.
5.	Setelah itu, repo dari upstream author sudah berada di account GitHub kita (kontributor).
6.	Kemudian clone di komputer lokal :
7.	Konfigurasi repo upstream 
8.	Tambahkan remote upstream
9.	Hasilnya : 
Origin : menunjuk ke repo milik contributor di GitHub, hasil dari fork.
Upstream : menunjuk ke repo milik upstream author (repo asli) di account Arawidhi. 

Membuat Perubahan di Repo Lokal
Pastikan :
1.	Sudah ada koordinasi secara manual tentang perubahan-perubahan yang akan dilakukan.
2.	Setelah melakukan perubahan-perubahan, pastikan bahwa isi repo lokal tersinkronisasi dengan repo dari upstream author. 
3.	Cara melakukan sinkronisasi :

4.	Lakukan perubahan-perubahan, setelah itu push ke origin (milik kontributor)
 Penggunaan -f pada akhir git push digunakan untuk melakukan push secara paksa karena saat tidak menggunakannya terjadi error atau muncul kesalahan.

5.	Setelah itu, buka halaman web dari repo contributor. Pada halaman tersebut akan ditampilkan isi yang kita push
6.	Pilih compare and pull request, kemudian isikan deskripsi PR dan klik pada Create pull request :
7.	Pada repo upstream author, muncul angka 1 (artinya jumlahnya 1) pada Pull requests di bagian atas.
8.	Upstream author bisa menyetujui setelah melakukan review: klik pada Pull request, akan muncul PR dengan message seperti yang ditulis oleh contributor . klik pada PR tersebut, review kemudian klik Merge pull request diikuti dengan Confirm merge. Setelah itu, status akan berubah menjadi Merged.
9.	Sinkronkan semua repo (lokal maupun GitHub kontributor).
