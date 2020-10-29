# Problem

## Gambar Tidak Muncul

Permasalahan
- Gambar tidak ada
- Folder Permission
- Penamaan File mengandung symbol terlarang

Solusi 1

apa bila gambar tidak ada bisa diupload ulang

Solusi 2

Rubah permission menjadi 755. [Ganti Permission di Hostinger.co.id](https://www.hostinger.com/tutorials/how-to-use-hostinger-file-manager/#File-Management-Area)


![Alt Text](https://raw.githubusercontent.com/gazz96/furnioo/master/images/01.%20change-permission.PNG "Change Permission 1")

1. Pilih Folder yang mau di rubah permissionnya

2. Pilih icon gembok sesuai gambar diatas

maka akan muncul gambar seperti berikut 

![Alt Text](https://raw.githubusercontent.com/gazz96/furnioo/master/images/02.%20change-permission.PNG "Change Permission 2")  

3. Setting Seperti gambar diatas

4. Pastikan angka 755

5. Klik simpan untuk menyimpan perubahan

Solusi 3

Penamaan file pada wordpress di usahakan tidak lebih dari 100 character untuk penamaan file disarankan hanya menggunakan huruf, angka, simbol dash(-), symbol underscore (_), contoh: 
- nama-file.jpg
- nama-file-1.jpg
- nama_file_1.jpg

## Setting Tampilan Home

Masuk ke admin

![Alt Text](https://raw.githubusercontent.com/gazz96/furnioo/master/images/01.%20setting-tampilan-home.PNG "Setting Tampilan Home")  

1. Pilih menu Appearance
2. Pilih menu widgets
3. Untuk menambah atau mengurangi element pada home, bisa settings di box Front Page

## Memindahkan deskripsi halaman category

1. Buka file archive-product.php yang berada di "wp-content/themes/decorist/woocommerce/archive-product.php"

2. Untuk kode tambahan berada di baris 115 - 123

![Alt Text](https://raw.githubusercontent.com/gazz96/furnioo/master/images/01.%20category%20description.PNG "Memindahkan deskripsi halaman category")  
