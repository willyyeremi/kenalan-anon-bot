# Bot Kenalan Anon
## Command yang bisa dipilih di menu
/start
command ini wajib dijalankan pertama kali. ada dua jenis respon:
<ol>
<li>saat user baru datang, tanyakan informasi berikut:
    <ol>
	<li>jenis kelamin
	<li>tanggal lahir
	<li>nama kota/ kab tempat tinggal sekarang
	<li>jenis domisili kota/ kab
    </ol>
<li>jika user lama, maka tanyakan "apa yang ingin anda lakukan"
</ol>

/help
memberikan list dari command apa saja yang bisa digunakan

## Command yang hanya bisa diketik
/edit
berguna untuk merubah informasi user

/post
berguna untuk memposting tulisan dengan foto, video, suara. menu ini perlu detail berikut:
<ol>
<li>hide user: apakah username dari user dicantumkan dalam post atau tidak
<li>hide age: untuk menampilkan umur
<li>hide loc: untuk menampilkan lokasi tinggal	
<li>buat ruang anon: berguna untuk membuat ruang chat khusus bagi responden dan pengirim post. Ruang ini hanya ada untuk waktu 5 menit. Ruang anon ini bisa diatur lebih lanjut:
    <ol>
    <li>show responder: mengharuskan orang yang akan meresponmu terlihat usernamenya. Responder akan diberitau soal ini saat masuk ke ruang chat. secara default, responder dapat meyembunyikan usernamenya. tapi jika opsi show responder dinyalakan maka responder tidak ada opsi menyembunyikan username.
    </ol>
detail cara kerja ruang anon dapat dilihat selanjutnya di bawah
</ol>

/find
Berguna untuk mencari 10 post terakhir yang paling relevan untuk user. Ada beberapa detail yang diperlukan:
<ol>
<li>jenis kelamin
<li>range umur
<li>level jarak. ada lima level:
    <ol>
    <li>satu kota/ kab
    <li>sampai kota/ kab tetangga
    <li>jarak 2-3 kota/ kab tetangga
    <li>satu pulau
    <li>5: random
    </ol>
</ol>

