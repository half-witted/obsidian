## Unsur
| <center>Unsur</center> | <center>Penjelasan</center>                                                                   | <center>Contoh</center>         |
| ---------------------- | --------------------------------------------------------------------------------------------- | ------------------------------- |
| Percobaan              | <mark style="background:#40a9ff">Kegiatan</mark> utk memperoleh hasil tertentu                | Melempar 1 dadu                 |
| Titik sampel           | <mark style="background:#40a9ff">Hasil</mark> percobaan 1 waktu                               | 1, 2, 3, 4, 5, 6                |
| Ruang sampel $(S)$     | <mark style="background:#40a9ff">Himpunan</mark> dr [[#Titik Sampel\|titik sampel]] (semesta) | $S=\{1,2,3,4,5,6\}$<br>$n(S)=6$ |
### Titik Sampel
| <center>Objek</center> | <center>Rumus</center>                                    | <center>Keterangan</center>                                                              |
| ---------------------- | --------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| $n$ objek sama         | $n(S)=n(S_{1})^n$                                         | $n(S)=$ total titik sampel<br>$n(S_{1})=$ banyak titik sampel objek<br>$n=$ banyak objek |
| Beberapa objek beda    | $n(S)=n(S_{1})\times n(S_{2})\times\dots \times n(S_{x})$ | $n(S_{x})=$ banyak titik sampel objek ke$-n$                                             |
### Kejadian
Himpunan bagian dr ruang sampel $(S)\to A \subseteq S$
![[Pasted image 20261101133012.png|171]]

| <center>Jenis</center> | <center>Penjelasan</center>                         | <center>Contoh</center>                                                                                                         | <center>Visualisasi</center>                                                                 |
| ---------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| Tunggal                | 1 kejadian                                          | Kejadian muncul mata dadu ganjil                                                                                                | ![[Pasted image 20261101133520.png\|168]]                                                    |
| Majemuk                | - > 1 kejadian<br>- Biasanya ditandai "dan", "atau" | 1. Kejadian muncul mata dadu ganjil <u>dan</u> $(\cap)$ prima<br>2. Kejadian muncul mata dadu ganjil <u>atau</u> $(\cup)$ prima | 1. ![[Pasted image 20261101133733.png\|166]]<br>2. ![[Pasted image 20261101133956.png\|164]] |
## Peluang
![[Pasted image 20261101162341.png|168]]
- Jika $P(A)=0\to$ peluang kemustahilan
- Jika $P(A)=1\to$ peluang kepastian
### Empiris
- Berdasarkan banyak <mark style="background:#d4b106">percobaan yg dilakukan</mark>
- <mark style="background:#d4b106">Makin banyak</mark> percobaan, makin stabil ke nilai tertentu, <mark style="background:#d4b106">makin akurat</mark>

| $P(A)=\displaystyle\frac{f(A)}{n}$ | $P(A)=$ peluang kejadian $A$<br>$f(A)=$ frekuensi kejadian $A$<br>$n=$ banyak percobaan |
| ---------------------------------- | --------------------------------------------------------------------------------------- |
### Teoretis
Berdasarkan perhitungan matematis <mark style="background:#d4b106">tanpa percobaan</mark>

| $P(A)=\displaystyle\frac{n(A)}{n(S)}$ | $P(A)=$ peluang kejadian $A$<br>$n(A)=$ banyak [[#Titik Sampel\|titik sampel]] kejadian $A$<br>$n(S)=$ total [[#Titik Sampel\|titik sampel]] |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
- Pastikan <mark style="background:#d4b106">peluang tiap titik sampel sama</mark>
### Komplemen
$P(A^C)=$ peluang semua kejadian yg bukan $A$
![[Pasted image 20261101163135.png|225]]

| <center>Rumus</center>                                                                    | <center>Keterangan</center>                                                                                                                                                             |
| ----------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| $n(A)+n(A^C)=n(S)$                                                                        | $n(A)=$ banyak [[#Titik Sampel\|titik sampel]] kejadian $A$<br>$n(A^C)=$ banyak [[#Titik Sampel\|titik sampel]] kejadian komplemen $A$<br>$n(S)=$ total [[#Titik Sampel\|titik sampel]] |
| $P(A)+P(A^C)=1$<br>$\displaystyle\frac{n(A)}{n(S)}+\frac{n(A^C)}{n(S)}=\frac{n(S)}{n(S)}$ | $P(A)=$ peluang kejadian $A$<br>$P(A^C)=$ peluang kejadian komplemen $A$                                                                                                                |
## Frekuensi Harapan
| $F_{h}(A)=n\times P(A)$ | $F_{h}(A)=$ frekuensi harapan kejadian $A$<br>$n=$ banyak percobaan<br>$P(A)=$ peluang kejadian $A$ |
| ----------------------- | --------------------------------------------------------------------------------------------------- |
## Peluang Kejadian
### Gabungan
- Dpt terjadi bersamaan
- Ditandai dgn <mark style="background:#d4b106">"atau"</mark>

| <center>Kejadian</center> | <center>Rumus</center>                                                                                                                               |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| <center>2</center>        | $P(A\cup B)=P(A)+P(B)-P(A\cap B)$<br>$P(A\cup B)=\displaystyle\frac{n(A\cup B)}{n(S)}$                                                               |
| <center>3</center>        | $P(A\cup B\cup C)=P(A)+P(B)+P(C)-P(A\cap B)-P(A\cap C)-P(B\cap C)+P(A\cap B\cap C)$<br>$P(A\cup B\cup C)=\displaystyle\frac{n(A\cup B\cup C)}{n(S)}$ |
![[Pasted image 20261101164542.png|224]]
### Saling Lepas
Himpunan saling asing, tk dpt terjadi bersamaan

| $P(A\cup B)=P(A)+P(B)$ | $P(A\cup B)=\displaystyle\frac{n(A\cup B)}{n(S)}$ |
| ---------------------- | ------------------------------------------------- |
![[Pasted image 20261101174806.png|224]]
### Saling Bebas
- Kejadian $A$ dan $B$ <mark style="background:#d4b106">saling bebas</mark> jika kejadian $A$ <mark style="background:#d4b106">tk memengaruhi terjadi tidaknya</mark> kejadian $B$, sebaliknya
- Ditandai dgn <mark style="background:#d4b106">"dan"</mark>

| $P(A\cap B)=P(A)\times P(B)$ | $P(A\cap B)=\displaystyle\frac{n(A\cap B)}{n(S)}$ | $P(A)\times P(B)\neq\displaystyle\frac{n(A\cap B)}{n(S)}\to$ bukan kejadian saling bebas |
| ---------------------------- | ------------------------------------------------- | ---------------------------------------------------------------------------------------- |
