# Tugas-Praktikum-5-job-control
<h2>1. Eksekusi seluruh profile yang ada :  
a.  Edit file profile /etc/profile dan tampilkan pesan sebagai berikut :  
echo “Profile dari /etc/profile”  </h2><br/>
<img src = https://github.com/user-attachments/assets/5daecb54-bb69-4a62-b393-25570d33684b width=500/>
<h2>b.  Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :  
/home/stD02001/.bash_profile  
/home/. stD02001/.bash_login  
/home/mahasiswa/.profile  
/home/mahasiswa/.bashrc  
Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap  
file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile :  
echo “Profile dari .bash_profile”  
Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang 
bersangkutan. </h2><br/>
<img src = https://github.com/user-attachments/assets/cebfd902-61ed-4366-9127-35e90edc7ca2 width=500/>
<h2>c.  Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:  
$ su mahasiswa  
$ exit </h2><br/>
<img src = https://github.com/user-attachments/assets/118ba3a7-3b05-4977-b2f1-8b8d429e4901 width=500/>
<h2>kemudian gunakan opsi – sebagai berikut :  
$ su – mahasiswa  
$ exit  <h2/><br/>
<img src = https://github.com/user-attachments/assets/fc0ebc4a-8cbe-451b-b78d-bcef9a563adf width=500/>

<h2>Jelaskan perbedaan kedua utilitas tersebut.  </h2><br/>
<h2>1. su mahasiswa:</h2>
<P>Perintah ini menjalankan su untuk beralih ke user mahasiswa.
Saat menggunakan perintah ini tanpa opsi -, lingkungan (environment) dari user saat ini tetap dipertahankan. Artinya, hanya identitas pengguna yang berubah, tetapi variabel lingkungan seperti PATH tidak akan berubah.</P>
Jadi, variabel lingkungan dan direktori kerja yang sedang aktif tetap sama seperti sebelumnya.<br/>

<h2>2. su - mahasiswa:</h2>
<p>Perintah ini menggunakan opsi - yang dikenal sebagai login shell.
Opsi ini melakukan login penuh sebagai user mahasiswa, sehingga environment yang dimuat adalah environment milik mahasiswa secara lengkap. Ini termasuk mengubah direktori kerja ke home directory user mahasiswa dan memuat variabel lingkungan seperti yang didefinisikan dalam shell milik mahasiswa.</p>
Jadi, ini seperti memulai sesi baru sebagai user mahasiswa.<br/>
