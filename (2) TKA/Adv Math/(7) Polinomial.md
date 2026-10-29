## Konsep
### Bentuk Umum
| ![[Pasted image 20261029084437.png\|522]] | - Banyak akar persamaan derajat $n$  |
| ----------------------------------------- | ------------------------------------ |
## Operasi
### Penjumlahan dan Pengurangan
1. Kelompokkan suku sejenis
2. Jumlahkan, kurangan koefisien suku tsb
### Perkalian
Kali pelangi
### Pembagian
| <center>Rumus</center>                                  | <center>Keterangan</center>                                                                                                                               |
| ------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| $P(x)=Q(x)\times H(x)+S(x)$                             | $P(x)=$ yg dibagi (derajat $n$)<br>$Q(x)=$ pembagi (derajat $m$ dgn $m\leq n$)<br>$H(x)=$ hasil bagi (derajat $n-m$)<br>$S(x)=$ sisa bagi (derajat $m-1$) |
| $\displaystyle\frac{P(x)}{Q(x)}=H(x)+\frac{S(x)}{Q(x)}$ |                                                                                                                                                           |
#### Cara Pembagian
##### Kesamaan
![[Pasted image 20261027133635.png|397]]
##### Bersusun
![[Pasted image 20261027133715.png|336]]
##### Horner
![[Pasted image 20261029083821.png|320]]
## Teorema
### Teorema Sisa
1. Jika $P(x)$ dibagi $(x-h)$, sisa pembagian adalah $P(h)$
2. Jika $P(x)$ dibagi $(ax-b)$, sisa pembagian adalah $P\displaystyle\left( \frac{b}{a} \right)$
3. Jika $P(x)$ dibagi $(x-a)(x-b)$, sisa pembagian adalah $S(x)=mx+n$
### Teorema Faktor
$(x-h)$ faktor dr $P(x)$ kalo $P(h)=0$