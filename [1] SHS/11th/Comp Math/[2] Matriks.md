## Pengenalan
### Konsep
- Dinyatakan dgn huruf kapital, elemen2 nya dgn huruf kecil
- Ordo matriks adalah baris x kolom $\to A_{2x3}=$ matriks A dgn 2 baris, 3 kolom
### Jenis
#### Berdasarkan Baris dan Kolom
- Matriks baris: 1 baris aja
- Matriks kolom: 1 kolom aja
- Matriks persegi panjang; jumlah baris, kolom beda
- Matriks persegi: jumlah baris, kolom sama

| $\begin{bmatrix}1&2&3\\4&5&6\\7&8&9\end{bmatrix}$ | $1, 5, 9=$ diagonal utama<br>$3, 5, 7=$ diagonal sekunder/samping<br>Penjumlahan diagonal utama disebut *trace* |
| ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
#### Berdasarkan Pola Elemen
- Matriks nol: semua elemen 0
- Matriks diagonal: matriks persegi dgn elemen diagonal utama $\neq$ 0, elemen lain 0
  $\begin{bmatrix}1&0&0\\0&2&0\\0&0&3\end{bmatrix}$
- Matriks identitas
	- Matriks persegi dgn elemen diagonal utama 1, elemen lain 0
	- Hasil kali matriks dgn invers nya
      $\begin{bmatrix}1&0&0\\0&1&0\\0&0&1\end{bmatrix}$
- Matriks segitiga
	- Matriks segitiga atas (U)
	  Di bawah diagonal utama bernilai 0
	  $\begin{bmatrix}1&2&3\\0&4&5\\0&0&6\end{bmatrix}$
	- Matriks segitiga bawah (L)
	  Di atas diagonal utama bernilai 0
	  $\begin{bmatrix}1&0&0\\2&3&0\\4&5&6\end{bmatrix}$
### Transpos
Menukar elemen baris dgn kolom
- $A=\begin{bmatrix}1&2&3\\4&5&6\\7&8&9\end{bmatrix}\to A^T=\begin{bmatrix}1&4&7\\2&5&8\\3&6&9\end{bmatrix}$
- $B=\begin{bmatrix}2&1&4\\1&4&5\\4&5&3\end{bmatrix}\to B^T=\begin{bmatrix}2&1&4\\1&4&5\\4&5&3\end{bmatrix}$
Jika $A=A^T\to A=$ <mark style="background:#40a9ff">matriks simetris</mark>
### Kesamaan Dua Matriks
Matriks $A=$ matriks $B$ jika berordo sama dan elemen2 sepetak bernilai sama
$A=\begin{bmatrix}\frac{1}{2} & 0\\5 & 9\end{bmatrix}$ sama dgn $B=\begin{bmatrix}\sin\left(\frac{\pi}{2}\right) & 0\\\sqrt{25} & 3^2\end{bmatrix}$
## Operasi
### Penjumlahan
Jumlahkan elemen sepetak
$\begin{bmatrix}1&4&2\\3&-1&0\end{bmatrix}+\begin{bmatrix}5&2&3\\3&8&0\end{bmatrix}=\begin{bmatrix}-4&6&5\\6&7&0\end{bmatrix}$
### Pengurangan
Kurangkan elemen sepetak
$\begin{bmatrix}1&4&2\\3&-1&0\end{bmatrix}-\begin{bmatrix}5&2&3\\3&8&0\end{bmatrix}=\begin{bmatrix}6&2&-1\\0&-9&0\end{bmatrix}$
### Perkalian Skalar
$A=\begin{bmatrix}1&4&2\\3&-1&0\end{bmatrix}\to3A=3\begin{bmatrix}1&4&2\\3&-1&0\end{bmatrix}=\begin{bmatrix}3&12&6\\9&-3&0\end{bmatrix}$
### Perkalian Matriks
$A_{mxn}*B_{nxp}=(AB)_{mxp}$
$A=\begin{bmatrix}1&2\\3&4\\1&0\end{bmatrix},B=\begin{bmatrix}-1&2&1\\3&2&4\end{bmatrix}$
$\hookrightarrow C=AB=\begin{bmatrix}(1*-1)+(2*3)&(1*2)+(2*2)&(1*1)+(2*4)\\(3*-1)+(4*3)&(3*2)+(4*2)&(3*1)+(4*4)\\(1*-1)+(0*3)&(1*2)+(0*2)&(1*1)+(0*4)\end{bmatrix}$
               $=\begin{bmatrix}-1+6&2+4&1+8\\-3+12&6+8&3+16\\-1+0&2+0&1+0\end{bmatrix}$
               $=\begin{bmatrix}5&6&9\\9&14&19\\-1&2&1\end{bmatrix}$
## Determinan
Determinan matriks $A=|A|$
### Nilai Determinan
#### Ordo 2x2
$|A|=$ hasil kali diagonal utama $-$ hasil kali diagonal sekunder
$A=\begin{bmatrix}3&5\\4&7\end{bmatrix},|A|=(3*7)-(4*5)=1$
#### Ordo 3x3
$B=\begin{bmatrix}1&0&2\\3&1&-2\\1&-1&2\end{bmatrix},|B|=\begin{bmatrix}1&0&2\\3&1&-2\\1&-1&2\end{bmatrix}\begin{matrix}1&0\\3&1\\1&-1\end{matrix}$
							 $=(1*1*2)+(0*-2*1)+(2*3*-1)-(2*1*1)-(1*-2*-1)-(0*3*2)$
							 $=2+0-6-2-2-0$
							 $=-8$
### Jenis
- Jika $|A|=0$, matriks $A$ disebut <mark style="background:#d4b106">matriks singular</mark>
- Jika $|A|\neq0$, matriks $A$ disebut <mark style="background:#d4b106">matriks nonsingular</mark>
### Sifat
- $|A^T|=|A|$
- $|A^{-1}|=\frac{1}{|A|}$
- $|AB|=|A|*|B|$
- $|A^n|=|A|^n$
- $|k*A|=k^n*|A|$ dgn $n$ adalah ordo
## Adjoin
$A=\begin{bmatrix}1&4&3\\2&5&1\\3&4&2\end{bmatrix}$
### Minor
Menutup baris dan kolom, menjadikan sisanya sbg matriks baru, menghitung hasil kali diagonal utama $-$ hasil kali diagonal sekunder

| $M_{11}=\begin{bmatrix}5&1\\4&2\end{bmatrix}=10-4=6$  | $M_{12}\begin{bmatrix}2&1\\3&2\end{bmatrix}=4-3=1$   | $M_{13}=\begin{bmatrix}2&5\\3&4\end{bmatrix}=8-15=-7$ |
| ----------------------------------------------------- | ---------------------------------------------------- | ----------------------------------------------------- |
| $M_{21}=\begin{bmatrix}4&3\\4&2\end{bmatrix}=8-12=-4$ | $M_{22}=\begin{bmatrix}1&3\\3&2\end{bmatrix}=2-9=-7$ | $M_{23}=\begin{bmatrix}1&4\\3&4\end{bmatrix}=4-12=-8$ |
| $M_{31}=\begin{bmatrix}4&3\\5&1\end{bmatrix}4-15=-11$ | $M_{32}=\begin{bmatrix}1&3\\2&1\end{bmatrix}=1-6=-5$ | $M_{33}=\begin{bmatrix}1&4\\2&5\end{bmatrix}=5-8=-3$  |
### Kofaktor
$kof(A)=\begin{bmatrix}M_{11}&-M_{12}&M_{13}\\-M_{21}&M_{22}&-M_{23}\\M_{31}&-M_{32}&M_{33}\end{bmatrix}=\begin{bmatrix}6&-1&-7\\4&-7&8\\-11&5&-3\end{bmatrix}$
### Adjoin
$Adj(A)=(kof(A))^T$
		  $=\begin{bmatrix}6&4&-11\\-1&-7&5\\-7&8&-3\end{bmatrix}$
## Invers
Matriks persegi $A$ dan $B$ dgn ordo sama dikatakan saling invers jika $AB=BA=$ matriks identitas $\to A=B^{-1},B=A^{-1}$
$A^{-1}=\frac{1}{|A|}*Adj(A)$
### Sifat
## Exercises