# menghitung luas dan keliling lingkaran menggunakan python

Daftar isi :

- [menghitung luas dan keliling lingkaran menggunakan python](#menghitung-luas-dan-keliling-lingkaran-menggunakan-python)
- [flowchart mengeliling luas dan keliling lingkaran](#flowchart-mengeliling-luas-dan-keliling-lingkaran)
- [kode dan hasil program menghitung luas dan keliling lingkaran](#kode-dan-hasil-program-menghitung-luas-dan-keliling-lingkaran)
- [penjelasan](#penjelasan)


# flowchart mengeliling luas dan keliling lingkaran

![image](image/Flowchart-menghitung-luas-keliling-lingkaran-1.png)


# kode dan hasil program menghitung luas dan keliling lingkaran

**kode program menghitung luas dan keliling lingkaran**
![image](image/kode%20luas%20dan%20keliling%20lingkaran.png)

**hasil kode program menghhitung luas dan keliling lingkaran**
![image](image/hasil%20kode%20luas%20dan%20keliling%20lingkaran.png)

# penjelasan 
Program diatas saya mengimport modul math yang sudah di sediakan oleh python. Fungsinya supaya saya dapat menyertakan nilai phi yang sudah tersedia dalam modul tersebut dengan perintah math.pi jika kita coba mencetak fungsi tersebut maka akan menghasilkan nilai 3.14


**import math**
**print (math.pi)**


**Output:**
**3.141592653589793**



Selanjutnya kita memerlukan nilai jari-jari (r) yang nantinya akan di masukan oleh pengguna pada layar console. Kita menggunakan fungsi input() yang nilainya di konversi ke tipe data float (bilangan riil). Ingat bahwa fungsi input() akan menganggap semua nilai inputan bertipe string, sehingga kita perlu melakukan konversi ke tipe yang diinginkan.

Ketika kita sudah mendapat nilai phi dan jari-jari selanjutnya kita bisa menghitung luas dan keliling sesuai dengan rumus-nya masing-masing (lihat pada baris ke 3 & 4).

Selanjutnya kita tampilkan hasilnya dengan fungsi print(). sintak \t merupakan karakter espace yang berfungsi untuk membuat tab. dalam kasus ini agar sejajar karakter sama dengan (=) nya.

Jika dilihat hasil luas dan keliling lingkaran mempunyai angka pecahan yang cukup banyak, untuk mengambil 2 angka pecahan saja kita pakai fungsi format() seperti berikut:

**print ("Luas Lingkaran \t= ",format(luas,'.2f'))**

**print ("Keliling Lingkaran \t= ",format(keliling,'.2f'))**

**Luas Lingkaran          =  40.72**

**Keliling Lingkaran      =  22.62**

Dengan penggunaan fungsi format(luas,’.2f’) akan menghasilkan 2 angka pecahan saja.