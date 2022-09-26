# PBO_Modul4
*Latihan 1 : Mendeklarasikan dan mencetak variabel

Berikut tampilan yang diharapkan sebagai hasil eksekusi program 
Number = 10
letter = a
result = true
str = hello

--> Disini kita tentukan tipe datanya terlebih dahulu 
number : integer karena inputnya berupa angka dan berada dalam 32-bit
letter : char karena inputnya diwakili oleh karakter single Unicode. Tipe data ini harus memiliki 
          berada dalam tanda single quotes (' ').
result : boolean karena inputnya berupa hello.
str : string mewakili beberapa karakter dan dinyatakan dalam tanda double pute (" ").
Untuk menampilkan nilai dari variabel yang diinginkan kita menggunakan syntax System.out.println() 
atau System.out.print(). Perbedaan dari kedua syntax ini yang pertama menambahkan baris baru pada 
akhir data untuk dikeluarkan, sementara selanjutnya tidak. 


*Latihan 2 : Mendapatkan nilai rata-rata dari tiga angka

Tampilan output yang diharapkan number 1 = 10, number 2 = 20, number 3 = 45, Average is = 25

--> Tentukan tipe data dari 3 angka tersebut. Disini n1, n2, n3 merupakan variabel dari masing-masing number tipe data yang digunakan integer. Untuk average juga dapat digunakan tipe data integer, jika ingin berkoma maka gunakan tipe data double. Untuk mencari average disini menggunakan rumus average = (n1 + n2 + n3) / 3. Lalu kita tampilkan hasil outpunya menggunaan System.out.println. 


*Latihan 3 : Menempatkan nilai terbesar

Program yang akan dihasilkan number 1 = 10, number 2 = 23, number 3 = 5, Nilai tertingginya adalah angka = 23

--> Tipe data yang digunakan integer. Disini kita menggunakan operasi kondisi (?:). Operator kondisi adalah operasi ternary. Operator ini digunakan dalam tiga bentuk pernyataan condisional argumen yang digunakan bersama-sama. Struktus operator kondisi yaitu exp1?exp2:exp3. Dimana nilai exp1 adalah suatu pernyataan boolean yang memiliki hasil yang salah satunya harus berupa nilai true atau false. Jika exp1 bernilai true, exp2 merupakan hasil operasi. Jika brnilai false, kemudian exp3 merupakan hasil operasinya. Untuk hasil = (10 > 23) -> false maka hasilnya 23, dilanjutkan dengan hasil = (5 >= 23) -> false maka nilai tertingginya 23.


*Latihan 4 : Operator precedence

Tulis kembali soal dengan menambahkan tanda kurung pada urutan sesuai dengan bagaimana pernyataan tersebut akan dievaluasi

--> Operator precedence didefinisikan sebagai perintah yang dilakukan compiler ketika melakukan evaluasi terhadap operator, untuk mengajukan perintah dengan hasil yang tidak ambigu/hasil yang jelas. 

1. a / b ^ c ^ d - e + f - g * h + i : Disini a/b kita kurung terlebih dahulu, hasil a/b dipangkatkan dengan c, hasilnya dipangkatkan lagi dengan d. Dilanjut g * h dikurung karena sesuai dengan sistem kabataku. Hasil dari (((a/b)^c) ^d) dikurangi dengan e ditambahkan f dikurang dengan hasil (g * h) dan ditambah dengan i. Maka penulisanny.

2. 3 * 10 * 2 / 15 - 2 + 4 ^ 2 ^ 2 : Disini 3*10*2 dikurung dahulu, lalu hasilnya dibagi dengan 15. Selanjutnya 4^2 kita kerjakan terlebih dahulu lalu hasilnya dipangkatkan 2. Sehingga hasil dari ((3* 10 * 2)/15) dikurang 2 lalu ditambah dengan hasil ((4^2)^2). Maka penulisannya sebagai berikut ((3 * 10 * 2)/15)-2+((4^2)^2).

3. r ^ s * t / u - v + w ^ x - y++ : Disini r^s terlebih dahulu kita beri tanda kurung, lalu hasilnya dikali dengan t, lalu hasilnya dibagi dengan u. Selanjutnya kerjakan terlebih dahulu w * v. Hasil dari ((r ^ s) * t)/u dikurang dengan v lalu ditambahkan dengan hasil (w^x) lalu dikurang y++. Maka penulisannya sebagai berikut (((r^s) * t)/u)-v+(w^x)-y++. y++ merupakan operator increment dan decrement operator yang menambah dan mengurangi nilai yang tersimpan dalam bentuk variabel angka terhadap nilai 1. 
