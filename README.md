# Massachusetts Soldiers & Sailors of the Revolutionary War

In the late 19th century, the Commonwealth of Massachusetts produced a 17-volume compilation of those who served in the American Revolutionary War.

Those tomes appear to be in the public domain (both as a work of the government and as having long exceeded a copyright term), but are frustratingly hard to access. This is my attempt at making it easier.

The 17 volumes are organized by last name. Here is a table showing the distribution:

| Volume | Surname                  | IA link | Local text | S3 PDF |
| ------ | ------------------------ | ------- | ---------- | ------ |
|  1 | Aacher&mdash;Bery            | [here][1] | [volume1.txt](text/volume1.txt) | [76.9 MB][pdf01] |
|  2 | Bese&mdash;Byxbe             | [here][2] | [volume2.txt](text/volume2.txt) | [72.3 MB][pdf02] |
|  3 | Caal&mdash;Cory              | [here][3] | [volume3.txt](text/volume3.txt) | [71.6 MB][pdf03] |
|  4 | Cose&mdash;Dryer             | [here][4] | [volume4.txt](text/volume4.txt) | [73.3 MB][pdf04] |
|  5 | Duarell&mdash;Foys           | [here][5] | [volume5.txt](text/volume5.txt) | [68.4 MB][pdf05] |
|  6 | Fracer&mdash;Gypson          | [here][6] | [volume6.txt](text/volume6.txt) | [69.8 MB][pdf06] |
|  7 | Haaoo&mdash;Hixson           | ? | [volume7.txt](text/volume7.txt)         | [66.5 MB][pdf07] |
|  8 | Hmelen&mdash;Jypson          | ? | [volume8.txt](text/volume8.txt)         | [72.5 MB][pdf08] |
|  9 | Kable&mdash;Lsubon           | [here][9] | [volume9.txt](text/volume9.txt) | [70.3 MB][pdf09] |
| 10 | Ltaas&mdash;Mopsy            | [here][10] | [volume10.txt](text/volume10.txt) | [66.7 MB][pdf10] |
| 11 | Mor&mdash;Pazel             | [here][11] | [volume11.txt](text/volume11.txt) | [77.8 MB][pdf11] |
| 12 | Pea&mdash;Razey              | [here][12] | [volume12.txt](text/volume12.txt) | [74.1 MB][pdf12] |
| 13 | Rea&mdash;Seymr              | [here][13] | [volume13.txt](text/volume13.txt) | [76.0 MB][pdf13] |
| 14 | Sha&mdash;Sthenfield         | [here][14] | [volume14.txt](text/volume14.txt) | [76.4 MB][pdf14] |
| 15 | Stibbens&mdash;Tozer         | [here][15] | [volume15.txt](text/volume15.txt) | [68.6 MB][pdf15] |
| 16 | Tracey&mdash;Wheylon         | [here][16] | [volume16.txt](text/volume16.txt) | [74.8 MB][pdf16] |
| 17 | Whicher&mdash;Zwear/Ztranius | [here][17] | [volume17.txt](text/volume17.txt) | [76.5 MB][pdf17] |

## Other Sources

The State Library of Massachusetts has [this listing](https://archives.lib.state.ma.us/handle/2452/122025?show=full)
which permits downloading PDFs of each volume. I have these mirrored to S3 if necessary.

The Internet Archive's [Open Library](https://openlibrary.org/books/OL7028060M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.)
has some of these made available, including OCR text copies. I've committed these where available.

Google Books also has some of these available, but I haven't tried to organize links to all of them.

## The goal

I would like to eventually transform these into HTML files, perhaps one per letter, to make these more easily accessible. The OCR process seems rather less than perfect; this seems normal in the best of cases, but working with very old books has got to exacerbate it. I'd love to try to at least correct some of the common errors.

[1]: https://openlibrary.org/books/OL13489927M/Massachusetts_soldiers_and_sailors_of_the_revolutionary_war._Vol._1_AACHER_-_BERY
[2]: https://openlibrary.org/books/OL7145838M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[3]: https://openlibrary.org/books/OL7241622M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[4]: https://openlibrary.org/books/OL13489922M/Massachusetts_soldiers_and_sailors_of_the_revolutionary_war._Vol._4_COSE_-_DRYER
[5]: https://openlibrary.org/books/OL13489919M/Massachusetts_soldiers_and_sailors_of_the_revolutionary_war._Vol.5_DUARELL_-_FOYS
[6]: https://openlibrary.org/books/OL13489918M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[9]: https://openlibrary.org/books/OL7109135M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[10]: https://openlibrary.org/books/OL7064934M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[11]: https://openlibrary.org/books/OL7160297M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[12]: https://openlibrary.org/books/OL7020914M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[13]: https://openlibrary.org/books/OL7116220M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[14]: https://openlibrary.org/books/OL13489910M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[15]: https://openlibrary.org/books/OL13489909M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[16]: https://openlibrary.org/books/OL7167370M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[17]: https://openlibrary.org/books/OL7028060M/Massachusetts_soldiers_and_sailors_of_the_revoluntionary_war.
[pdf01]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1896-v.1.pdf
[pdf02]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1896-v.2.pdf
[pdf03]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1897-v.3.pdf
[pdf04]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1898-v.4.pdf
[pdf05]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1899-v.5.pdf
[pdf06]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1899-v.6.pdf
[pdf07]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1900-v.7.pdf
[pdf08]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1901-v.8.pdf
[pdf09]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1902-v.9.pdf
[pdf10]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1902-v.10.pdf
[pdf11]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1903-v.11.pdf
[pdf12]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1904-v.12.pdf
[pdf13]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1905-v.13.pdf
[pdf14]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1906-v.14.pdf
[pdf15]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1907-v.15.pdf
[pdf16]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1907-v.16.pdf
[pdf17]: https://n1zyy.s3.amazonaws.com/mssrw/ocm12601336-1908-v.17.pdf
