# Lab5Web
Nama : Muhammad sidik ghozali
Nim : 312310763
Kelas : TI 23 A1

Pemrograman Web 1
<!DOCTYPE html>
<html lang="en">
<head>
<title>Mengenal JavaScript</title>
</head>
<body>
<h1>Pengenalan JavaScript</h1>
<h3>Contoh document.write dan console.log</h3>
<script>
document.write("Hello World");
console.log("Hello World");
</script>
</body>
</html>

![Screenshot 2024-10-28 080343](https://github.com/user-attachments/assets/87ca22c3-cdc6-41d2-8b2a-82108757a0ad)
 
Penjelasan Kode
•	document.write("Hello World"); menampilkan teks "Hello World" langsung di halaman HTML.
•	console.log("Hello World"); menampilkan teks "Hello World" di konsol browser (bisa dilihat dengan membuka DevTools di browser).

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alert Box</title>
</head>
<body>
    <script type="text/javascript">
        window.alert("Ini merupakan pesan untuk Anda");
    </script>
</body>
</html>
 
 ![Screenshot 2024-10-28 081421](https://github.com/user-attachments/assets/68737a1b-3839-41b7-b58e-8f8f9a877f88)

Penjelasanya :
•	<!DOCTYPE html>:

•	Ini adalah deklarasi untuk menunjukkan bahwa dokumen ini menggunakan HTML5. DOCTYPE memberikan instruksi kepada browser tentang versi HTML yang digunakan, memastikan halaman dirender dengan benar.
•	<html lang="en">:

•	Tag pembuka <html> adalah akar dari seluruh dokumen HTML. Atribut lang="en" menunjukkan bahwa bahasa utama konten dalam dokumen ini adalah bahasa Inggris. Ini membantu mesin pencari dan teknologi pembaca layar memahami bahasa yang digunakan.
•	<head>:

•	Bagian <head> berisi informasi meta-data tentang dokumen, termasuk pengaturan karakter, judul halaman, dan tautan ke file CSS atau JavaScript eksternal.
•	<meta charset="UTF-8">:

•	Tag meta ini menetapkan set karakter yang digunakan di halaman ini sebagai UTF-8, yang mendukung hampir semua karakter dari berbagai bahasa. Ini memastikan bahwa teks dan simbol ditampilkan dengan benar.
•	<meta name="viewport" content="width=device-width, initial-scale=1.0">:

•	Meta tag ini digunakan untuk membuat halaman lebih responsif di perangkat mobile. width=device-width memastikan tampilan halaman disesuaikan dengan lebar layar perangkat, dan initial-scale=1.0 memastikan halaman tidak di-zoom secara otomatis saat pertama kali dibuka.
•	<title>Alert Box</title>:

•	Tag <title> menetapkan judul halaman yang ditampilkan di tab browser atau sebagai judul bookmark. Dalam hal ini, judulnya adalah "Alert Box".
•	<body>:

•	Tag <body> adalah tempat semua konten utama halaman ditempatkan. Konten di dalam <body> akan terlihat oleh pengguna di browser.
•	<script type="text/javascript">:

•	Tag <script> digunakan untuk menyematkan atau menulis kode JavaScript di halaman HTML. Atribut type="text/javascript" menunjukkan bahwa kode di dalam tag ini adalah JavaScript. Meskipun sekarang tidak lagi diperlukan, tetap bisa dituliskan untuk kompatibilitas.
•	window.alert("Ini merupakan pesan untuk Anda");:

•	Kode JavaScript ini menjalankan fungsi alert(), yang menampilkan kotak pesan (alert box) dengan teks "Ini merupakan pesan untuk Anda". Kotak ini muncul saat halaman dibuka, dan pengguna harus menutupnya sebelum dapat berinteraksi dengan halaman.
•	</body>:

•	Tag penutup </body> menandakan akhir dari konten utama halaman.
•	</html>:

•	Tag penutup </html> menandakan akhir dari dokumen HTML.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skrip JavaScript</title>
</head>
<body>
    <p>Percobaan memakai JavaScript:</p>
    <script type="text/javascript">
        document.write("Selamat mencoba JavaScript<br>");
        document.write("Semoga sukses!");
    </script>
</body>
</html>

![Screenshot 2024-10-28 081903](https://github.com/user-attachments/assets/3642222b-374d-4e26-991f-b492561d6ae5)

 Penjelasnya :
•	<!DOCTYPE html>: Menandakan bahwa dokumen ini adalah HTML5, memberi tahu browser tentang versi HTML yang digunakan.

•	<html lang="en">: Akar dari dokumen HTML. Atribut lang="en" menunjukkan bahwa bahasa utama adalah bahasa Inggris.

•	<head>: Berisi meta-data dokumen, termasuk pengaturan karakter dan judul halaman.

•	<meta charset="UTF-8">: Menetapkan set karakter ke UTF-8 untuk mendukung berbagai karakter.

•	<meta name="viewport" content="width=device-width, initial-scale=1.0">: Membuat halaman responsif di perangkat mobile, menyesuaikan lebar tampilan dengan lebar layar perangkat.

•	<title>Skrip JavaScript</title>: Menetapkan judul halaman yang ditampilkan di tab browser.

•	<body>: Tempat konten utama halaman yang terlihat oleh pengguna.

•	<p>Percobaan memakai JavaScript:</p>: Paragraf yang menampilkan teks pengantar.

•	<script type="text/javascript">: Memuat kode JavaScript.

•	document.write("Selamat mencoba JavaScript<br>");: Menulis teks "Selamat mencoba JavaScript" ke dalam halaman.

•	document.write("Semoga sukses!");: Menulis teks "Semoga sukses!" ke dalam halaman setelah teks sebelumnya.

•	</script>: Menandakan akhir kode JavaScript.

•	</body>: Menandakan akhir dari konten halaman.

•	</html>: Menandakan akhir dari dokumen HTML.



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemasukan Data</title>
</head>
<body>
    <script type="text/javascript">
        var nama = prompt("Siapa nama Anda?", "Masukkan nama Anda");
        document.write("Hai, " + nama);
    </script>
</body>
</html>
 
 ![Screenshot 2024-10-28 082102](https://github.com/user-attachments/assets/41b7ff0f-9057-413e-a914-bde15648e25f)

Penjelasanya :
•	<!DOCTYPE html>: Menandakan dokumen ini adalah HTML5, memberi tahu browser tentang versi HTML yang digunakan.

•	<html lang="en">: Akar dari dokumen HTML. Atribut lang="en" menunjukkan bahwa bahasa utama adalah bahasa Inggris.

•	<head>: Berisi meta-data dokumen, termasuk pengaturan karakter dan judul halaman.

•	<meta charset="UTF-8">: Menetapkan set karakter ke UTF-8 untuk mendukung berbagai karakter.

•	<meta name="viewport" content="width=device-width, initial-scale=1.0">: Membuat halaman responsif di perangkat mobile, menyesuaikan lebar tampilan dengan lebar layar perangkat.

•	<title>Pemasukan Data</title>: Menetapkan judul halaman yang ditampilkan di tab browser.

•	<body>: Tempat konten utama halaman yang terlihat oleh pengguna.

•	<script type="text/javascript">: Memuat kode JavaScript.

•	var nama = prompt("Siapa nama Anda?", "Masukkan nama Anda");: Menggunakan fungsi prompt() untuk meminta pengguna memasukkan namanya, dengan teks pertanyaan dan placeholder.

•	document.write("Hai, " + nama);: Menulis pesan "Hai, " diikuti oleh nama yang dimasukkan pengguna ke dalam dokumen HTML.

•	</script>: Menandakan akhir kode JavaScript.

•	</body>: Menandakan akhir dari konten halaman.

•	</html>: Menandakan akhir dari dokumen HTML.



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program JavaScript</title>
    <script type="text/javascript">
        function pesan() {
            alert("Memanggil JavaScript lewat body onload");
        }
    </script>
</head>
<body onload="pesan()">
</body>
</html>

![Screenshot 2024-10-28 082501](https://github.com/user-attachments/assets/0b4688f3-c842-460c-bb8c-2315900cb3cb)

 Penjelasannya :
•	<!DOCTYPE html>: Menandakan bahwa dokumen ini adalah dokumen HTML5, memberikan instruksi kepada browser tentang versi HTML yang digunakan.

•	<html lang="en">: Akar dari dokumen HTML. Atribut lang="en" menunjukkan bahwa bahasa utama adalah bahasa Inggris.

•	<head>: Bagian ini berisi informasi meta-data tentang dokumen, termasuk pengaturan karakter, judul halaman, dan kode JavaScript.

•	<meta charset="UTF-8">: Menetapkan set karakter ke UTF-8 untuk mendukung berbagai karakter dan simbol.

•	<meta name="viewport" content="width=device-width, initial-scale=1.0">: Membuat halaman responsif di perangkat mobile, menyesuaikan lebar tampilan dengan lebar layar perangkat.

•	<title>Contoh Program JavaScript</title>: Menetapkan judul halaman yang akan ditampilkan di tab browser.

•	<script type="text/javascript">: Memuat kode JavaScript. Di dalam tag ini, terdapat fungsi bernama pesan().

•	function pesan() { alert("Memanggil JavaScript lewat body onload"); }: Fungsi pesan() akan menampilkan kotak dialog (alert) dengan pesan "Memanggil JavaScript lewat body onload" ketika dipanggil.

•	</script>: Menandakan akhir dari blok kode JavaScript.

•	<body onload="pesan()">: Bagian ini adalah tempat konten utama halaman. Atribut onload="pesan()" mengindikasikan bahwa fungsi pesan() akan dipanggil secara otomatis saat halaman selesai dimuat.

•	</body>: Menandakan akhir dari konten halaman.

•	</html>: Menandakan akhir dari dokumen HTML.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program JavaScript</title>
    <script type="text/javascript">
        function test(val1, val2) {
            document.write("<br>Perkalian: " + (val1 * val2) + "<br>");
            document.write("Pembagian: " + (val1 / val2) + "<br>");
            document.write("Penjumlahan: " + (val1 + val2) + "<br>");
            document.write("Pengurangan: " + (val1 - val2) + "<br>");
            document.write("Modulus: " + (val1 % val2) + "<br>");
        }
    </script>
</head>
<body>
    <input type="button" name="button" value="Arithmetic" onclick="test(9, 4)">
</body>
</html>
 
 ![Screenshot 2024-10-28 082802](https://github.com/user-attachments/assets/d1992061-d6ae-4977-99f3-36004a4bde97)

Penjelasanya :
•	<!DOCTYPE html>: Menandakan bahwa dokumen ini adalah dokumen HTML5, memberi tahu browser tentang versi HTML yang digunakan.

•	<html lang="en">: Akar dari dokumen HTML. Atribut lang="en" menunjukkan bahwa bahasa utama adalah bahasa Inggris.

•	<head>: Bagian ini berisi informasi meta-data tentang dokumen, termasuk pengaturan karakter, judul halaman, dan kode JavaScript.

•	<meta charset="UTF-8">: Menetapkan set karakter ke UTF-8 untuk mendukung berbagai karakter dan simbol.

•	<meta name="viewport" content="width=device-width, initial-scale=1.0">: Membuat halaman responsif di perangkat mobile, menyesuaikan lebar tampilan dengan lebar layar perangkat.

•	<title>Contoh Program JavaScript</title>: Menetapkan judul halaman yang akan ditampilkan di tab browser.

•	<script type="text/javascript">: Memuat kode JavaScript. Di dalam tag ini, terdapat fungsi bernama test(val1, val2).

•	function test(val1, val2) { ... }: Fungsi ini menerima dua parameter, val1 dan val2, dan melakukan beberapa operasi aritmatika (perkalian, pembagian, penjumlahan, pengurangan, dan modulus) terhadap kedua nilai tersebut. Hasil dari setiap operasi ditampilkan di halaman menggunakan document.write().

•	</script>: Menandakan akhir dari blok kode JavaScript.

•	<body>: Tempat konten utama halaman yang terlihat oleh pengguna.

•	<input type="button" name="button" value="Arithmetic" onclick="test(9, 4)">: Elemen input tombol yang, ketika diklik, akan memanggil fungsi test(9, 4) dengan argumen 9 dan 4. Hasil dari fungsi ini akan ditampilkan di halaman.

•	</body>: Menandakan akhir dari konten halaman.

•	</html>: Menandakan akhir dari dokumen HTML.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh If-Else</title>
</head>
<body>
    <script type="text/javascript">
        var nilai = prompt("Masukkan nilai (0-100): ", 0);
        var hasil = "";
        if (nilai >= 60) {
            hasil = "lulus";
        } else {
            hasil = "tidak lulus";
        }
        document.write("Hasil: " + hasil);
    </script>
</body>
</html>
 
 ![Screenshot 2024-10-28 083014](https://github.com/user-attachments/assets/a29fe948-edad-4326-bb5e-b791789a6025)

Penjelasanya :
•	<!DOCTYPE html>: Menandakan bahwa dokumen ini adalah dokumen HTML5, memberikan instruksi kepada browser tentang versi HTML yang digunakan.

•	<html lang="en">: Akar dari dokumen HTML. Atribut lang="en" menunjukkan bahwa bahasa utama dari konten adalah bahasa Inggris.

•	<head>: Bagian ini berisi informasi meta-data tentang dokumen, termasuk pengaturan karakter dan judul halaman.

•	<meta charset="UTF-8">: Menetapkan set karakter ke UTF-8 untuk mendukung berbagai karakter dan simbol.

•	<meta name="viewport" content="width=device-width, initial-scale=1.0">: Membuat halaman responsif di perangkat mobile, menyesuaikan lebar tampilan dengan lebar layar perangkat.

•	<title>Contoh If-Else</title>: Menetapkan judul halaman yang akan ditampilkan di tab browser.

•	<body>: Tempat konten utama halaman yang terlihat oleh pengguna.

•	<script type="text/javascript">: Memuat kode JavaScript di dalam halaman HTML.

•	var nilai = prompt("Masukkan nilai (0-100): ", 0);: Mendeklarasikan variabel nilai dan menggunakan fungsi prompt() untuk meminta pengguna memasukkan nilai antara 0 hingga 100. Nilai default yang ditampilkan di dalam prompt adalah 0.

•	var hasil = "";: Mendeklarasikan variabel hasil yang akan menyimpan status kelulusan.

•	if (nilai >= 60) { ... }: Struktur kondisi if-else. Jika nilai yang dimasukkan pengguna 60 atau lebih, maka variabel hasil akan diatur ke "lulus".

•	else { hasil = "tidak lulus"; }: Jika kondisi sebelumnya tidak terpenuhi, maka hasil akan diatur ke "tidak lulus".

•	document.write("Hasil: " + hasil);: Menggunakan document.write() untuk menampilkan hasil kelulusan di halaman dengan format "Hasil: " diikuti oleh nilai dari variabel hasil.

•	</script>: Menandakan akhir dari blok kode JavaScript.

•	</body>: Menandakan akhir dari konten halaman.

•	</html>: Menandakan akhir dari dokumen HTML.


<html>
<head>
    <title>Contoh Program JavaScript</title>
    <script language="javascript">
        function test() {
            var vall = window.prompt("Input nilai (1-5):"); // Corrected 'vall' variable declaration
            switch (vall) {
                case "1":
                    document.write("Bilangan satu");
                    break;
                case "2":
                    document.write("Bilangan dua");
                    break;
                case "3":
                    document.write("Bilangan tiga");
                    break;
                case "4":
                    document.write("Bilangan empat");
                    break;
                case "5": // Changed this to a string for consistency
                    document.write("Bilangan lima");
                    break;
                default:
                    document.write("Bilangan lainnya");
            }
        }
    </script>
</head>
<body>
    <input type="button" name="button" value="Switch" onclick="test()">
</body>
</html>
 
 ![Screenshot 2024-10-28 090814](https://github.com/user-attachments/assets/cb6662d2-2c00-4be7-8403-3a65d48ede39)

Penjelasanya :
Program ini meminta pengguna memasukkan angka antara 1 hingga 5 dan menampilkan pesan sesuai dengan angka yang dimasukkan.

<html>
<head>
    <script language="javascript">
        function test() {
            var val1 = document.kirim.T1.value; // Menggunakan nama yang benar untuk input
            val1 = parseInt(val1); // Mengonversi string input menjadi integer
            
            if (val1 % 2 == 0) {
                document.kirim.T2.value = "bilangan genap"; // Menampilkan hasil jika genap
            } else {
                document.kirim.T2.value = "bilangan ganjil"; // Menampilkan hasil jika ganjil
            }
        }
    </script>
</head>
<body>
    <form method="POST" name="kirim">
        <p>BILANGAN <input type="text" name="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" size="20" readonly></p>
        <p><input type="button" value="TEBAK" name="B1" onclick="test()"></p>
    </form>
</body>
</html>

![Screenshot 2024-10-28 091832](https://github.com/user-attachments/assets/14b79b61-0472-4eff-a6ff-207da8c42380)

Penjelasan Perubahan:
Program ini digunakan untuk menentukan apakah sebuah bilangan yang dimasukkan oleh pengguna adalah genap atau ganjil.

<html>
<head>
    <title>Objek Document</title>
    <script language="javascript">
        function ubahWarnaLB(warna) {
            document.body.style.backgroundColor = warna; // Mengubah warna latar belakang
        }

        function ubahWarnaLD(warna) {
            document.body.style.color = warna; // Mengubah warna teks
        }
    </script>
</head>
<body>
    <h1>Tes</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onClick="ubahWarnaLB('GREEN')"> 
        <input type="button" value="Latar Belakang Putih" onClick="ubahWarnaLB('WHITE')"> 
        <input type="button" value="Teks Kuning" onClick="ubahWarnaLD('YELLOW')"> 
        <input type="button" value="Teks Biru" onClick="ubahWarnaLD('BLUE')">
    </form>
    <script language="javascript">
        document.write("Dimodifikasi terakhir pada: " + document.lastModified); // Memperbaiki sintaks
    </script>
</body>
</html>

![Screenshot 2024-10-28 092121](https://github.com/user-attachments/assets/90e624f1-3ebf-4ce1-95eb-afb32c70ef73)

Penjelasnya :
Program ini memungkinkan pengguna untuk mengubah warna latar belakang dan teks halaman web melalui tombol.

<html>
<head>
    <title>Daftar Menu</title>
    <script>
        function hitung(ele) {
            var total = document.getElementById("total").value; // Ambil nilai total dari input
            total = (total ? parseInt(total) : 0); // Konversi total ke integer, jika ada

            var harga;
            if (ele.checked) {
                harga = parseInt(ele.value); // Ambil harga dari checkbox yang dipilih
                total += harga; // Tambahkan harga ke total
            } else {
                harga = parseInt(ele.value); // Ambil harga jika checkbox tidak dipilih
                if (total) {
                    total -= harga; // Kurangi harga dari total
                }
            }

            document.getElementById("total").value = total; // Tampilkan total yang diperbarui
        }
    </script>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5600" onclick="hitung(this);" /> Ayam Goreng Rp. 5.600</label><br />
    <label><input type="checkbox" value="500" onclick="hitung(this);" /> Tempe Goreng Rp. 500</label><br />
    <label><input type="checkbox" value="2500" onclick="hitung(this);" /> Telur Dadar Rp. 2.500</label><hr />
    <strong>Total Bayar: Rp. <input id="total" type="text" value="0" readonly /></strong>
</body>
</html>

![Screenshot 2024-10-28 092626](https://github.com/user-attachments/assets/c57601fc-6dfd-4db0-a315-ff7dcf775e93)

Penjelasan Kode:
Fungsi hitung(ele):

Input: Menerima elemen checkbox (ele) yang dipilih.
Pengambilan Total: Mengambil nilai total saat ini dari elemen input dengan ID total dan mengonversinya menjadi integer. Jika tidak ada nilai, maka diinisialisasi menjadi 0.
Cek Status Checkbox: Jika checkbox dipilih (ele.checked), maka harga dari checkbox ditambahkan ke total. Jika checkbox tidak dipilih, harga akan dikurangi dari total.
Menampilkan Total: Mengupdate elemen input total dengan nilai total yang baru.
HTML Struktur:

Terdapat judul "Daftar Menu Makanan".
Tiga checkbox yang masing-masing mewakili menu makanan dengan harga.
Total pembayaran ditampilkan dalam input readonly agar tidak bisa diubah langsung oleh pengguna.


Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form.
==========================================================================================


<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Validasi Form</title>
    <script>
        function validateForm() {
            // Ambil nilai dari input
            var nama = document.getElementById("nama").value;
            var email = document.getElementById("email").value;
            var pesan = document.getElementById("pesan").value;
            var errorMsg = "";

            // Validasi nama
            if (nama === "") {
                errorMsg += "sidik.\n";
            }

            // Validasi email
            var emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/; // Pola email yang sederhana
            if (email === "" || !emailPattern.test(email)) {
                errorMsg += "Email tidak valid.\n";
            }

            // Validasi pesan
            if (pesan === "") {
                errorMsg += "tetap semangatt.\n";
            }

            // Tampilkan pesan error jika ada
            if (errorMsg) {
                alert(errorMsg);
                return false; // Cegah pengiriman form
            }
            return true; // Izinkan pengiriman form
        }
    </script>
</head>
<body>
    <h1>Form Kontak</h1>
    <form onsubmit="return validateForm();">
        <label for="nama">Nama:</label>
        <input type="text" id="nama" name="nama"><br><br>
        
        <label for="email">Email:</label>
        <input type="text" id="email" name="email"><br><br>
        
        <label for="pesan">Pesan:</label><br>
        <textarea id="pesan" name="pesan"></textarea><br><br>
        
        <input type="submit" value="Kirim">
    </form>
</body>
</html>

![Screenshot 2024-10-28 093130](https://github.com/user-attachments/assets/6230c391-4147-4cb8-8182-8d688a14f6b4)

Penjelasan Script Validasi Form:
HTML Structure:

Terdapat form dengan tiga input: nama, email, dan pesan.
Form dilengkapi dengan label dan area untuk memasukkan pesan.
Fungsi validateForm():

Fungsi ini dipanggil saat form disubmit.
Mengambil nilai dari masing-masing input menggunakan document.getElementById().
Melakukan validasi:
Validasi Nama: Memeriksa apakah input nama kosong.
Validasi Email: Menggunakan regex (pola ekspresi reguler) untuk memvalidasi format email. Jika email kosong atau tidak sesuai pola, maka akan menghasilkan pesan error.
Validasi Pesan: Memastikan input pesan tidak kosong.
Jika ada kesalahan, pesan error ditampilkan menggunakan alert() dan pengiriman form dicegah dengan return false.
Jika semua validasi lulus, maka fungsi mengembalikan true, yang mengizinkan form untuk dikirim.
Cara Kerja Program:
Pengguna mengisi form dan menekan tombol "Kirim".
Fungsi validasi dijalankan untuk memastikan semua field diisi dengan benar.
Jika ada field yang tidak valid, pengguna akan menerima pesan error yang sesuai dan tidak dapat mengirimkan form sampai semua kesalahan diperbaiki.
