## Pengenalan
### Konsep
- Dinyatakan dgn huruf kapital, elemen2 dgn huruf kecil
- Ordo: banyak baris $(m)$ $\times$ banyak kolom $(n)$
### Transpose
Matriks dr perpindahan elemen2 baris dgn kolom
![[Pasted image 20261023010729.png|352]]
Jika $A=A^T\to A=$ <mark style="background:#d4b106">matriks simetris</mark>
### Jenis
#### Berdasarkan Baris dan Kolom
| <center>Jenis</center>  | <center>Penjelasan</center>     | <center>Contoh</center>                   |
| ----------------------- | ------------------------------- | ----------------------------------------- |
| Matriks baris           | 1 baris aja                     | ![[Pasted image 20261023011111.png\|218]] |
| Matriks kolom           | 1 kolom aja                     | ![[Pasted image 20261023011143.png\|125]] |
| Matriks persegi         | baris $=$ kolom<br>$m=n$        | ![[Pasted image 20261023011205.png\|214]] |
| Matriks persegi panjang | baris $\neq$ kolom<br>$m\neq n$ | ![[Pasted image 20261023011225.png\|167]] |
#### Berdasarkan Pola Elemen
| <center>Jenis</center> | <center>Penjelasan</center>                                                                        | <center>Contoh</center>                                                                                |
| ---------------------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| Matriks nol            | Semua elemen $=0$                                                                                  | ![[Pasted image 20261023011525.png\|91]]                                                               |
| Matriks diagonal       | Elemen diagonal utama $\neq 0$, elemen lain $=0$                                                   | $\begin{pmatrix}a&0&0\\0&b&0\\0&0&c\end{pmatrix}$                                                      |
| Matriks identitas      | - Elemen diagonal utama $=1$, elemen lain $=0$<br>- Misalkan matriks $A\to A\times I=A$            | $\begin{pmatrix}1&0&0\\0&1&0\\0&0&1\end{pmatrix}$                                                      |
| Matriks segitiga       | - Atas (U): elemen di bawah diagonal utama $=0$<br>- Bawah (L): elemen di atas diagonal utama $=0$ | $\begin{pmatrix}a&b&c\\0&d&e\\0&0&f\end{pmatrix}$<br>$\begin{pmatrix}a&0&0\\b&c&0\\d&e&f\end{pmatrix}$ |
### Kesamaan
$>1$ matriks dikatakan sama jika:
- Ordo sama
- Elemen2 sepetak sama
## Operasi
### Penjumlahan dan Pengurangan
Menjumlahkan atau mengurangkan elemen sepetak
![[Pasted image 20261023012520.png|381]]
### Perkalian Skalar
![[Pasted image 20261023012625.png|228]]
### Perkalian
| ![[Pasted image 20261023012728.png\|187]] | ![[Pasted image 20261023012746.png\|267]] |
| ----------------------------------------- | ----------------------------------------- |
## Determinan
### Nilai
#### Ordo 2x2
![[Pasted image 20261023013430.png|358]]
#### Ordo 3x3
Pake sarrus:
1. Tulis ulang
	![[Pasted image 20261023013642.png|162]]
2.  Kalikan elemen2 diagonal kanan, jumlahkan
	![[Pasted image 20261023013934.png|181]]
3. Kalikan elemen2 diagonal kiri, jumlahkan
	![[Pasted image 20261023014102.png|181]]
4. Hitung determinan
	![[Pasted image 20261023014133.png|359]]
### SPL
![[Pasted image 20261023014305.png|165]]
![[Pasted image 20261023014251.png|542]]
### Sifat
| <center>Sifat</center>                          | <center>Penjelasan Tambahan</center>                   |
| ----------------------------------------------- | ------------------------------------------------------ |
| $\lvert A\rvert = \lvert A^T\rvert$             |                                                        |
| $\lvert AB\rvert=\lvert A\rvert*\lvert B\rvert$ |                                                        |
| $\lvert A\rvert=\lvert B\rvert$                 | Jika $A=\begin{pmatrix}c&d\\e&f\end{pmatrix}$ dan $B=$ |
