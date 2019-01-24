latihan 1
Langkah-langkah Install Git di Windows
Baiklah, mari kita mulai ritual instalnya. Silahkan klik 2x file instaler Git yang sudah diunduh.
Buka file instalator Git
![image](https://user-images.githubusercontent.com/46734744/51678971-39a21580-2010-11e9-9676-2257e8cc33e6.png)

Maka akan muncul infomasi lisensi Git, klik Next > untuk melanjutkan.
Informasi tentang Git
![image](https://user-images.githubusercontent.com/46734744/51679146-b1704000-2010-11e9-88cc-988372f02dc4.png)

Selanjutnya menentukan lokasi instalasi. Biarkan saja apa adanya, kemudian klik Next >.
Lokasi instalasi Git
![image](https://user-images.githubusercontent.com/46734744/51679241-f8f6cc00-2010-11e9-9cb5-db616c765512.png)

Selanjutnya pemilihan komoponen, biarkan saja seperti ini kemudian klik Next >.
Pemilihan Komponen untuk diinstal
![image](https://user-images.githubusercontent.com/46734744/51679317-30657880-2011-11e9-9127-c13a4601f1e0.png)

Selanjutnya pemlilihan direktori start menu, klik Next >.
Pembuatan start menu
![image](https://user-images.githubusercontent.com/46734744/51679360-5854dc00-2011-11e9-8901-aff5ddd3ce91.png)

Selanjutnya pengaturan PATH Environment. Pilih yang tengah agar perintah git dapat di kenali di Command Prompt (CMD). Setelah itu klik Next >.
Menentukan Path Environment
![image](https://user-images.githubusercontent.com/46734744/51679441-905c1f00-2011-11e9-9a5b-5de500cb3bfd.png)

Selanjutnya konversi line ending. Biarkan saja seperti ini, kemudian klik Next >.
Konversi line ending yang akan digunakan
![image](https://user-images.githubusercontent.com/46734744/51679505-b1bd0b00-2011-11e9-942a-d00457269c27.png)

Selanjutnya pemilihan emulator terminal. Pilih saja yang bawah, kemudian klik Next >.
Pemilihan Terminal Emulator
![image](https://user-images.githubusercontent.com/46734744/51679644-09f40d00-2012-11e9-89f4-259c4232200a.png)

Selanjutnya pemilihan opsi ekstra. Klik saja Next >.
Pemilihan Opsi Ekstra
![image](https://user-images.githubusercontent.com/46734744/51679699-314ada00-2012-11e9-91f4-fb560c1b4542.png)

Selanjutnya pemilihan opsi ekspreimental, langsung saja klik Install untuk memaulai instalasi.
Opsi Eksperimental
![image](https://user-images.githubusercontent.com/46734744/51679724-40ca2300-2012-11e9-8426-372d8d227a66.png)

Tunggu beberapa saat, instalasi sedang dilakukan.
Sedang Menginstall Git
![image](https://user-images.githubusercontent.com/46734744/51679738-4b84b800-2012-11e9-9e80-e929c2b62261.png)

Setelah selesai, kita bisa langsung klik Finish.
Instalasi Git Selesai
![image](https://user-images.githubusercontent.com/46734744/51679757-58091080-2012-11e9-8197-4acba028d4f1.png)

Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah git --version.
Perbobaan Perintah Git
![image](https://user-images.githubusercontent.com/46734744/51680461-6a844980-2014-11e9-81ef-14eec4ad5c01.png)

cara upload file ke repository GitHub yang kita miliki di windows

Perangkat yang di gunakan
*Akun GitHub, Untuk upload project ke GitHub tentunya kita harus memilki akaun GitHub, caranya langsung buat akun di websitenya https://github.com kemudian daftar.
*Sofware Git, Untuk sofware ini anda bisa download secara gratis di http://git-scm.com/ , kalo sudah di download silahkan anda install.

Setelah kita mempunya akun GitHub dan mengistall software git maka kita bisa langsung meng upload project kita.
*Buatlah repository di GitHub dengan mengklik icon repo "Create new repository".

*Kemudian beri nama repository nya lalu beri deskripsi untuk repository yang kita buat jika perlu, kemudian setting public/private, kalau public berarti bisa di akses oleh semua orang, kemudian centang "initialize this repository with a README" dan tambahkan kategori repository jila perlu.

*kemudian klik "create repository".

*Jika repository berhasil dibuat, anda akan di berikan kunci akases berupa HTTP/SSH, ini yang akan kita gunakan untuk remote repository dari software GIT. Misal saya punya kunci HTTP http://github.com/acchoblues/APeK.git

*Setelah anda berhasil membiat repository sekarang klik kanan pada folder project yang akan di upload.

*Klik kanan pada project klik "Git Bash".

*Kemudian akan muncul command prompt / CMD

*Jika anda baru pertama kali meggunakan software GIT, sebaiknya konfigurasi username dan email dulu.

*Ketik
 Git config --global user.name "Widianggraeni15" 
 Git config --global user.email "widiapsptsr@mhs.pelitabangsa.ac.id
 
*Setelah melakukan konfigurasi username dan email, sekarang kita lakukan inisiasi, ketikan
 Git init 

*Kemudian kita tambahkan semua file yang ada dalam folder project kita, ketikan
 Git add * 

*Kemudian kita buat commit project nya, misal disini saya kasih commit “versi 1.0.0” , ketikan
 Git commit –m "versi 1.0.0" 

*Setelah kita buat commit untuk project nya, sekarang kita remote repository yang kita buat tadi, tentunya kita menggunakan kunci HTTP yang ada pada repository tadi, kalo ane kan tadi contoh nya http://github.com/acchoblues/APeK.git , ketikan
 Git remote add origin http://github.com/acchoblues/APeK.git 

*Setelah me-remote repository kita tadi, sekarang kita pull project nya, ketikan
 Git pull origin master 

*Terakhir kita kirim project kita ke repository kita, ketikan
 Git push origin master
 
Tampilan project github

 ![latihan1](https://user-images.githubusercontent.com/46734744/51681778-3f9bf480-2018-11e9-8b9f-3e1ffa03b9ca.png)

 
Biasanya ketika kita ketikan perintah push ini, kita akan diminta username dan password kita dan perlu di perhatikan untuk password nya biasa nya ketika kita mengetikan password maka pada command prompt nya tidak ditampilkan karakter apapun.


Sekian penjelasan penggunaan Git dari saya, mohon maaf apabila ada kesalahan penulisan atau penjelasan yang kurang tepat dan jelas.
