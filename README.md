# Praktikum-9 
# Nama : Bayu Pratama 
#  Nim : 312210351
# Kelas : TI.22.A3

Disini saya akan menjelaskan tentang latihan yg kemarin
Disini saya akan menjelaskan tentang latihan pada hari selasa 13-12-2022

 #pertama _

<img width="528" alt="prak 9 1" src="https://user-images.githubusercontent.com/115516730/208421053-c5a785de-63bd-44e3-8ceb-d4b298b346f0.png">
Berikut adalah fungsi yang mengubah suhu suhu dari derajat Kelvin ke derajat Fahrenheit. Karena nol derajat Kelvin sedingin yang didapat. Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback...AssertionError artinya terjadi error pada pernyataan pernyataan.
 #Kedua _
<img width="536" alt="prak 9 2" src="https://user-images.githubusercontent.com/115516730/208420939-e6524b52-b93c-4ebe-ad80-a2767dae238c.png">
contoh ini membuka file, menulis konten di file, dan keluar tidak ada masalah, Ini menghasilkan hasil berikut
Konten tertulis dalam file berhasil
Dan kenapa hasilnya begitu? karena else akan dijalankan ketika try adalah True
 #KETIGA _
<img width="530" alt="prak 9 3" src="https://user-images.githubusercontent.com/115516730/208421362-7a3c5205-c93b-44ec-9c74-435a642fc912.png">
Mengapa muncul kesalahan?
Kesalahan: tidak dapat menemukan file atau membaca data
r adalah read - Membuka file untuk membaca, error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya fh = open("testfile", "r") tambahkan print(fh.readline()) dan fh.write dihapus. Setelah dijalankan, coba dan ditampilkan lagi
 #KEempat _
<img width="537" alt="prak 9 4" src="https://user-images.githubusercontent.com/115516730/208421584-cfc7049c-d719-4517-ba92-e98b93501c09.png">
Menghasilkan keluaran:
Kesalahan: tidak dapat menemukan file atau membaca data
Ini bukan error, karena akhirnya dijalankan ketika mencoba dan kecuali dijalankan. Dan berhasil dibuat filenya setelah dijalankan
#Penjelasan  kelima
<img width="474" alt="prak 9 5" src="https://user-images.githubusercontent.com/115516730/208421861-00db8fbd-5371-4041-9ba5-1ebc101fb158.png">
ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di kecuali ValueError, Argument: ganti koma dengan seperti kecuali ValueError sebagai Argument:agar tidak error. Jika dijalankan akan muncul error lagi
Argumen tidak mengandung angka
literal tidak valid untuk int() dengan basis 10: 'xyz'
kenapa? karena parameter def temp_convert harus mengandung angka
#Penjelasan  ke 6
<img width="470" alt="prak 9 6" src="https://user-images.githubusercontent.com/115516730/208422073-506acd12-3d12-4d15-8bd7-f5e30ede3d25.png">
Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada kenaikan "Level tidak valid!", ganti level tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1
