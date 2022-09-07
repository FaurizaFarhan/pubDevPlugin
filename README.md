Praktikum 

![ss] (images/ss.png)

Pertanyaan 
1. jelaskan maksud dari langkah 2!
    - langkah 2 berarti kita menambahkan package auto_size_text kedalam project
2. jelaskan maksud dari langkaah 5 pada praktikum tersebut
    - membuat tambahan konstruktor berbentuk text yang kita memanggil class RedTextWidget() maka kita harus memberikan parameter berupa text saat pemanggilan
3. pada langkah 6 terdapat dua widget yang ditambahkan, jelaskan fungsi dan perbedaannya
    - untuk widget atas adalah menggunakan AutoSizeText package sehingga text akan terbungkus menyesuaikan dengan ketentuan wadah penampung yang kita buat, yang menyebabkan text seperti readmore. sedangkan widget bawah dapat ddilihat tidak menggunakan package apapun yang menyebabkan text menjadi tidak rapi dan meninggalkan sisa ruang (padding) yang banyak
4. Jelaskan maksud dari tiap parameter yang ada di dalam plugin auto_size_text berdasarkan tautan   pada dokumentasi ini !
key = mengkontrol bagaimana widget menumpuk widget lain di tree
textKey = memberikan id unik untuk Text widget
style = memberikan styling terhadap widget
minFontSize = memberikan nilai minimum untuk kecil huruf
maxFontSize = memberikan nilai maximum untuk besar huruf
stepGranularity = ukuran jarak saat font size di adaptasi ke constraints.
presetFontSizes = mendefinisikan diawal kemungkinan ukuran font.
group = mensinkronisasi ukuran dari multiple AutoSizeText.
textAlign = merubah bagaimana text di alignkan (left,right,center).
textDirection = arah dari sebuah text. Menentukan bagaimana param textAlign di intepretasikan.
locale = digunakkan untuk memilih font saat memiliki Unicode character yang sama bisa di render secara berbeda.
softWrap = mengatur apakah text di break saat soft line breaks.
wrapWords = mengatur apakah kalimat yang tidak fit terhadap 1 baris akan dibungkus.
overflow = mengatur bagaimana tampilan text yang berlebih akan di handle.
overflowReplacement = mengatur jika text berlebih dan tidak cukup terhadap batas maka widget yang akan ditampilkan.
textScaleFactor = angka untuk font pixels dari setiap logical pixel. Mempengaruhi minFontSize, maxFontSize dan presetFontSizes
maxLines = memberikan nilai maximum baris untuk kalimat.
semanticsLabel = alternatif untuk memberikan semantics label terhadap text