# Mengenal CSS
# Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}?
Elemen H1 adalah Selektor Tag disbut juga Type Selector. Selektor ini akan memilih elemen berdasarkan nama tag. Selektor ini bersifat tidak kaku yang dapat memungkinkan dapat di gunakan kembali ke pada elemen yang lainnya. 
Sedangkan perintah elemen #intro H1 adalah perintah awalan simbol hash / pagar dimana lebih spesifik di bandingkan H1, memungkinkan kita untuk memberi style pada id. Selector id sesungguhnya bersifat kaku dan tidak memungkinkan untuk digunakan kembali pada element yang lainnya.
# Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser?
Tergantung pada peletakan barisnya, misalnya apabila meletakan deklarasi CSS secara internal terlebih dahulu lalu di baris berikut meletakan deklarasi CSS eksternal maka yang akan di tampilkan pada browser yaitu deklarasi CSS eksternal. Begitupula apabila meletakan deklarasi CSS eksternal terlebih dahulu lalu di baris berikut meletakan deklarasi CSS secara internal maka yang akan di tampilkan pada browser yaitu deklarasi CSS secara Internal. Karena  deklarasi yang di pakai sesudah kita meletakkan deklarasi terlebih dahulu akan menimpa/meoverred deklarasi sebelumnya.
