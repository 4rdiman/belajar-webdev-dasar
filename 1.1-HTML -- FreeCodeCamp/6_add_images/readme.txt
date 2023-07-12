sesi 6 saya belajar:

1.cara menambahkan file image:
    <img> --> auto close tag

    <img> memiliki:
    1. src --> tempat dimana image berada dan kita mengambilnya
    2. alt --> kalau imagenya tidak loading, ini yang terlihat
    3. title --> title di cursor
    4. widht --> lebar image
    5. height --> panjang image
    6. loading --> untuk tipe loading image, tipe lazy untuk pemrosesan yang lebih cepat

2. menambahkan text dibawah image dan menunjukkan bahwa text ini punya image:
    <figure>
    <img>
    <figcaption>textnya disini</figcaption>
    </figure>

3. contoh:

    <figure>
        <img src="img/image.jpg" alt="Japanese zen garden" title="zen garden, beautiful." width="400" height="250" loading="lazy">
        <figcaption>Japanese Zen Garden</figcaption>
    </figure>

note:
1. figure tidak hanya untuk image.
2. usahakan ukuran image kecil dan masih mantap.
3. untuk download dan mengecilkan image banyak situs-situs yang menyediakannya.

