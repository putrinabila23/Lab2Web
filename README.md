# Mengenal CSS
# Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}?
Elemen H1 adalah Selektor Tag disbut juga Type Selector. Selektor ini akan memilih elemen berdasarkan nama tag. Selektor ini bersifat tidak kaku yang dapat memungkinkan dapat di gunakan kembali ke pada elemen yang lainnya. 
Sedangkan perintah elemen #intro H1 adalah perintah awalan simbol hash / pagar dimana lebih spesifik di bandingkan H1, memungkinkan kita untuk memberi style pada id. Selector id sesungguhnya bersifat kaku dan tidak memungkinkan untuk digunakan kembali pada element yang lainnya.
# Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser?
Tergantung pada peletakan barisnya, misalnya apabila meletakan deklarasi CSS secara internal terlebih dahulu lalu di baris berikut meletakan deklarasi CSS eksternal maka yang akan di tampilkan pada browser yaitu deklarasi CSS eksternal. Begitupula apabila meletakan deklarasi CSS eksternal terlebih dahulu lalu di baris berikut meletakan deklarasi CSS secara internal maka yang akan di tampilkan pada browser yaitu deklarasi CSS secara Internal. Karena  deklarasi yang di pakai sesudah kita meletakkan deklarasi terlebih dahulu akan menimpa/meoverred deklarasi sebelumnya.

Contohnya: Disini saya meletakkan deklarasi CSS eksternal terlebih dahulu yang berisi

![css 1](https://user-images.githubusercontent.com/56376643/113827328-5ff59b00-97ad-11eb-896e-bb2963d8991b.JPG)

Sebagai berikut di mana warna color nya berwarna putih, font-size 60px,front-family Times New roman, aria dan font-variant small-cpas. lalu meletakkan deklarasi CSS secara internal dimama warna color nya berwarna merah , font-size 60px,front-family Times New roman, aria dan font-variant normal

![css 2](https://user-images.githubusercontent.com/56376643/113827548-a21edc80-97ad-11eb-9fd9-0e643f846103.JPG)

Dan hasilnya pada browser di tampilkan CSS secara internal

![css 3](https://user-images.githubusercontent.com/56376643/113827863-f45ffd80-97ad-11eb-9748-557fa276748b.JPG)

# Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf">

Yang akan di tampilkan di awal browser property ID karena pada Id diawali tanda hash/pagar yang lebih spesifik dibandingkan dengan property Class.

![css 4](https://user-images.githubusercontent.com/56376643/113828581-c202d000-97ae-11eb-8d83-d6ed7ddb6329.JPG)

![css 5](https://user-images.githubusercontent.com/56376643/113829709-0347af80-97b0-11eb-8104-ebfcc805ef0a.JPG)

![css 6](https://user-images.githubusercontent.com/56376643/113830189-8ec14080-97b0-11eb-9635-70da3e1c2898.JPG)

# Belajar Menggunakan CSS Pada HTML
1. Tag head digunakan untuk memuat hal-hal seperti import, membutuhkan dan referensi eksternal, sedangkan tag bagian body digunakan untuk menampung tampilan dan informasi grafik seperti header, footer, gambar , dll.

![lat css 1](https://user-images.githubusercontent.com/56376643/113833309-b6fe6e80-97b3-11eb-82c8-501757aa6240.JPG)

2. Divisi – digunakan untuk menyimpan data dalam jumlah yang wajar, membaginya menjadi bagian yang mudah dibaca dan digunakan, serta dapat menyimpan tag HTML lain di dalamnya.
 Hal lain yang perlu Anda ketahui adalah kelas dan ID. Kelas dan ID digunakan dalam CSS untuk memasangkan gaya yang diberikan dengan tempat gaya harus diterapkan dalam file HTML 

![lat css 2](https://user-images.githubusercontent.com/56376643/113834322-e6fa4180-97b4-11eb-9bb4-1c7ba90adac8.JPG)

![lat css 3](https://user-images.githubusercontent.com/56376643/113834325-e82b6e80-97b4-11eb-88d3-a759b32abaec.JPG)

![lat css 4](https://user-images.githubusercontent.com/56376643/113834331-e8c40500-97b4-11eb-8428-4d4fdec32ea9.JPG)

3. dan beginilah hasinya setelah file di drag ke browser.




