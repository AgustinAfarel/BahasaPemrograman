# BahasaPemrograman
Dibuat Untuk Memenuhi Tugas Bahasa Pemrograman Pertemuan ke 6

Nama   : Agustin Afarel

NIM    : 312010081

Kelas  :TI.20.B.1.

Matkul : Bahasa Pemrograman

Tugas Pertemuan Ke 5

print("Please enter full name : ")
<br>longname = input ()

print ("Please insert your nickname :")
<br>nickname = input ()

print("please enter yout NPM :")
<br>NPM = input()

print("Please insert your age :")
<br>age = int (input())

print("Please enter your Born Place :")
<br>bornplace = input()

print("Please enter your home addres :")
<br>hometown = input()

print("Please enter your phone number :")
<br>phone = input()

print("\n\nAssalamualaikum Wr.Wb")
 
print(f"Let indtroduce my self. My name is {longname}, but you can call me {nickname}.My NPM is {NPM}. i was born in {bornplace} and I am {age} year old. I am very glad if you want to invite my house in {hometown}. so, don`t forget to call me before with the number {phone}")

* Penjelasanya
Variabel adalah sebuah wadah penyimpanan data pada program yang akan digunakan selama program itu berjalan. Yang berfungsi sebagai variable dalam source code.

Fungsi print() seperti dijelaskan pada poin Output diatas Hasil dari source code

Fungsi input() adalah untuk memasukkan nilai dari layar console di command prompt, lalu kemudian mengembalikan nilai saat kita menekan tombol enter (newline)

Fungsi huruf f pada perintah print(f"...") adalah fungsi print atau bisa memudahkan programmer dalam mencetak statement dalam satu baris dibandingkan dengan metode yang lama yaitu memisahkan string dan variable dengan simbol koma ( , ) atau plus ( + )

fungsi {} pada output tersebut adalah untuk menampilkan hasil dari variable

fungsi \n pada source code diatas adalah untuk memberi baris baru / enter / (newline)

* Untuk memasukkan perintah lain seperti Nickname, NPM, Place Of Birth, Date of Birth, Year of Birth, Phone Number, and Address mengikuti perintah yang sama seperti memasukkan fullname

* Untuk menghitung rumus umur saya menggunakan variable DOB yaitu 2020 (Tahun Sekarang) dikurangi dengan Year of Birth.

Hasil Output Tersebet Seperti gambar dibawah ini

![Gambar](:/BahasaPemrograman/Gambarr.PNG)

* LAB 1
<br>#Penggunaan End
<br>print("A", end="")
<br>print("B", end="")
<br>print("C", end="")

<br>print()
<br>print("X")
<br>print("Y")
<br>print("Z")

<br>#Penggunaan Separator
<br>w,x,y,z=10,15,20,25
<br>print(w,x,y,z)
<br>print(w,x,y,z,sep=",")
<br>print(w,x,y,z,sep="")
<br>print(w,x,y,z,sep=":")
<br>print(w,x,y,z,sep="-----")

 
Penggunaan END Penggunaan end digunakan untuk menambahkan karakter yang dicetak di akhir baris. Secara default penggunaan end adalah untuk ganti baris.

Penggunaan Separator Separator adalah pemisah yang berfungsi sebagai tanda pemisah antar objek yang dicetak. Defaultnya adalah tanda spasi.

Pendeklarasian beberapa variable beserta nilainya

w,x,y,z=10,15,20,25
Menampilkan hasil dari variable tiap-tiap variable

print(w,x,y,z)
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah , (koma)

print(w,x,y,z,sep=",")
Menampilkan hasil dari tiap-tiap variable tanpa menggunakan pemisah

print(w,x,y,z,sep="")
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah : (titik dua)

print(w,x,y,z,sep=":")
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah -----

print(w,x,y,z,sep="-----")

Hasil dari syntax berikut 
![Gambar]()

* LAB 1-2

String Format
String formatting atau pemformatan string memungkinkan kita menyuntikkan item kedalam string daripada kita mencoba menggabungkan string menggunakan koma atau string concatenation.

<br>#String Format 1
<br>print(0, 10**0)
<br>print(1, 10**1)
<br>print(2, 10**2)
<br>print(3, 10**3)
<br>print(4, 10**4)
<br>print(5, 10**5)
<br>print(6, 10**6)
<br>print(7, 10**7)
<br>print(8, 10**8)
<br>print(9, 10**9)
<br>print(10, 10**10)

<br>print()
<br>print()

<br>#String Format 2
<br>print('{0:>3} {1:>16}'.format(0, 10**0))
<br>print('{0:>3} {1:>16}'.format(0, 10**1))
<br>print('{0:>3} {1:>16}'.format(0, 10**2))
<br>print('{0:>3} {1:>16}'.format(0, 10**3))
<br>print('{0:>3} {1:>16}'.format(0, 10**4))
<br>print('{0:>3} {1:>16}'.format(0, 10**5))
<br>print('{0:>3} {1:>16}'.format(0, 10**6))
<br>print('{0:>3} {1:>16}'.format(0, 10**7))
<br>print('{0:>3} {1:>16}'.format(0, 10**8))
<br>print('{0:>3} {1:>16}'.format(0, 10**9))
<br>print('{0:>3} {1:>16}'.format(0, 10**10))

String Format 1
Pada syntax / source code string format 1 akan menampilkan output berupa 2 outputan.
Yang pertama (sebelah kiri) akan menampilkan angka Urut dari angka 0 hingga angka 10, sedangkan untuk sebelah kanan akan menampilkan Operasi Aritmatika Pangkat.
Dengan ketentuan sebagai berikut, operasi pangkat dengan angka kiri sebagai pokok (Rumus : ** [bintang dua] )
Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10

String Format 2
Pada syntax atau source code string format 2 akan menampilkan output berupa 2 output'an juga (seperti String Format 1, yaitu kanan dan kiri)

Alignment, padding, dan precesion dengan .format() dalam kurung kurawal kita dapat menetapkan panjang bidang, rata kanan/kiri, parameter pembulatan dan banyak lagi. Contoh lain seperti berikut :

<br>print('{0:8} | {1:9}'.format('Buah','Jumlah'))
<br>print('{0:8} | {1:9}'.format('Apel', 3.))
<br>print('{0:8} | {1:9}'.format('Jeruk',10))

Secara Default, .format() menggunakan rata teks ke kiri, angka ke kanan. Kita dapat menggunakan opsi opsional <, ^, atau > untuk mengatur perataan kiri, tengah, atau kanan. Contoh lain dalam penggunaan .format() sebagai berikut :

<br>print('{:<30}{:^30}{:>30}'.format('Kiri','Tengah','Kanan'))
<br>print('{:<30}{:^30}{:>30}'.format(12,34,56))

*LAB 2

Konversi nilai variable

<br>a=input("Masukkan Nilai A : ")
<br>b=input("Masukkan Nilai B : ")
<br>print("Variable A : ",a)
<br>print("Variable B : ",b)
<br>print("Hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#Konversi nilai variable
<br>a=int(a)
<br>b=int(b)
<br>print("Hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
<br>print("Hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))


