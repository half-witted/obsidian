## Konsep
### Bentuk Umum
| ![[Pasted image 20261029084437.png\|522]] | - Nilai $x$ yg memenuhi persamaan disebut akar2<br>- Banyak akar derajat $n$ adalah $n$ buah<br>- Misal $p$ adalah akarnya, kemungkinan nilainya adalah hasil bagi dr faktor $a_{0}$ dgn $a_{n}$ |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
### Akar Persamaan
#### Menentukan Akar
| ![[Pasted image 20261029090259.png\|298]] | ![[Pasted image 20261029090346.png\|329]] | ![[Pasted image 20261029090411.png\|266]] |
| ----------------------------------------- | ----------------------------------------- | ----------------------------------------- |
#### Rumus
| <center>Rumus</center>        | <center>Perumusan</center>                                                                       |
| ----------------------------- | ------------------------------------------------------------------------------------------------ |
| Jumlah akar2                  | $x_{1}+x_{2}+\dots+x_{n}=\displaystyle-\frac{a_{n-1}}{a_{n}}$                                    |
| Jumlah hasil kali tiap 2 akar | $x_{1}x_{2}+x_{1}x_{3}+x_{2}x_{3}+\dots+x_{n-1}x_{n}=\displaystyle \frac{a_{n-2}}{a_{n}}$        |
| Jumlah hasil kali tiap 3 akar | $x_{1}x_{2}x_{3}+x_{1}x_{2}x_{4}+\dots+x_{n-2}x_{n-1}x_{n}=\displaystyle -\frac{a_{n-3}}{a_{n}}$ |
| Jumlah hasil kali semua akar  | $x_{1}x_{2}x_{3}\dots x_{n}=(-1)^2\times \displaystyle \frac{a_{0}}{a_{n}}$                      |
## Operasi
### Penjumlahan dan Pengurangan
1. Kelompokkan suku sejenis
2. Jumlahkan, kurangan koefisien suku tsb
### Perkalian
Kali pelangi
### Pembagian
| <center>Rumus</center>                                  | <center>Keterangan</center>                                                                                                                                    |
| ------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| $P(x)=Q(x)\times H(x)+S(x)$                             | $P(x)=$ yg dibagi (derajat $n$)<br>$Q(x)=$ pembagi (derajat $m$ dgn $m\leq n$)<br>$H(x)=$ hasil bagi (derajat $n-m$)<br>$S(x)=$ sisa bagi (derajat maks $m-1$) |
| $\displaystyle\frac{P(x)}{Q(x)}=H(x)+\frac{S(x)}{Q(x)}$ |                                                                                                                                                                |
#### Cara Pembagian
##### Kesamaan
![[Pasted image 20261027133635.png|397]]
##### Bersusun
![[Pasted image 20261027133715.png|336]]
##### Horner
| <center>Pembagi</center> | <center>Penyelesaian</center>             |
| ------------------------ | ----------------------------------------- |
| $(x-h)$                  | Tinggal horner                            |
| $(ax+b)$                 | ![[Pasted image 20261029111545.png\|276]] |
## Teorema
### Teorema Sisa
1. Jika $P(x)$ dibagi $(x-h)$, sisa pembagian adalah $P(h)$
2. Jika $P(x)$ dibagi $(ax-b)$, sisa pembagian adalah $P\displaystyle\left( \frac{b}{a} \right)$
3. Jika $P(x)$ dibagi $(x-a)(x-b)$, sisa pembagian adalah $S(x)=mx+n$
### Teorema Faktor
$(x-h)$ faktor dr $P(x)$ kalo $P(h)=0$