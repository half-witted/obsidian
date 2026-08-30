## Pengenalan
### Unsur-Unsur
- Kelas interval
  Kelompok nilai data
	- Kelas 1 = 31-40
	- Kelas 2 = 41-50
	- etc
- Batas kelas
	- $B_{b}=$ batas ujung bawah kelas
	- $B_{a}=$ batas ujung atas kelas
	^batas-kelas
- Tepi kelas
	- $T_{b}=B_{b}-$ ketelitian data (0,5 di contoh)
	- $T_{a}=B_{a}-$ ketelitian data
- Panjang kelas
  $p=T_{a}=T_{b}$
  ^panjang-kelas
- Titik tengah kelas
  $X_{i}=\frac{1}{2}(B_{a}+B_{b})$
### Penyajian Data
1. Tentukan jangkauan
   $J=$ data terbesar $-$ data terkecil
2. Tentukan banyak kelas interval (aturan Sturges)
   $K=1+3.3 \log n$
3. Tentukan panjang kelas
   $P=\frac{J}{K}$
## Pemusatan Data
### Mean
#### Data Tunggal
- Bentuk 1
  Jika data $x_{1},x_{2},\dots,x_{n}$
  $\bar{x}=\frac{{x_{1}+x_{2}+\dots+x_{n}}}{n}=\frac{{\sum x}}{n}$
- Bentuk 2
  Jika data $x_{1},x_{2},\dots,x_{n}$ punya frekuensi $f_{1},f_{2},\dots,f_{n}$
  $\bar{x}=\frac{{f_{1}x_{1}+f_{2}x_{2}+\dots+f_{n}x_{n}}}{f_{1}+f_{2}+\dots+f_{n}}$
- Bentuk 3
  Jika $f_{1}$ bilangan bermean $m_{1}$, $f_{2}$ bilangan bermean $m_{2}$, ... , dan $f_{n}$ bilangan bermean $m_{n}$
  $\bar{x}=\frac{{f_{1}m_{1}+f_{2}m_{2}+\dots+f_{n}m_{n}}}{f_{1}+f_{2}+\dots+f_{n}}$
#### Data Kelompok
$\bar{x}=\frac{{\sum f_{1}}x_{i}}{\sum f_{i}}$
### Median
#### Data Tunggal
Urutkan, bagi langsung
#### Data Kelompok
| $Me=Tb_{Me}+\left( \frac{{\frac{2}{4}n-\sum f_{-Me}}}{f_{Me}} \right)p$ | $M_{e}=$ median<br>$Tb_{Me}=$ tepi bawah kelas median<br>$n=$ jumlah semua frekuensi<br>$\sum f_{-Me}=$ jumlah frekuensi sebelum kelas median<br>$f_{Me}=$ frekuensi kelas median<br>$p=$ [[#^panjang-kelas\|panjang kelas]] |
| ----------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
### Modus
#### Data Tunggal
Cari langsung: bisa gk ada, 1 doang, lebih dari 1
#### Data Kelompok
| $Mo=Tb_{Mo}+\left( \frac{d_{1}}{d_{1}+2_{2}} \right)p$ | $Mo=$ modus<br>$Tb_{Mo}=$ tepi bawah kelas modus<br>$d_{1}=$ selisih frekuensi kelas modus dgn kelas sebelum<br>$d_{2}=$ dgn kelas setelah<br>$p=$ [[#^panjang-kelas\|panjang kelas]] |
| ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
## Penyebaran Data
### Jangkauan *(range)*
Ukuran penyebaran paling sederhana
$J=$ data terbesar $-$ data terkecil
- Kelebihan: mudah, cepat
- Kekurangan: sgt dipengaruhi nilai ektrem *(outlier)*
### Kuartil dan *Interquartile Range* (IQR)
#### Kuartil
| $Q_{1}=Tb_{i}+\left( \frac{{\frac{1}{4}n-\sum f_{-i}}}{f_{i}} \right)p$ | $Q_{i}=$ kuartil ke-i (1, 2, 3)<br>$Tb_{i}=$ tepi bawah kelas kuartil ke-i<br>$n=$ jumlah semua frekuensi<br>$\sum f_{-i}=$ jumlah frekuensi sebelum kelas kuartil ke-i<br>$f_{i}=$ frekuensi kelas kuartil ke-i<br>$p=$ [[(1) Statistika#^panjang-kelas\|panjang kelas]] |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
#### *Interquartile Range* (IQR)
Mengukur penyebaran 50% data tengah
$IQR=Q_{3}-Q_{1}$
### Pencilan *(outlier)*
Data yg melewati batas terjauh

| $B_{nb}=Q_{1}-1.5*IQR$                                                                                                             | $B_{na}=Q_{3}+1.5*IQR$                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| $B_{nb}=$ batas nilai bawah<br>$Q_{1}=$ [[#Kuartil\|kuartil]] ke-1<br>$IQR=$ [[#*Interquartile Range* (IQR)\|interquartile range]] | $B_{na}=$ batas nilai atas<br>$Q_{3}=$ [[#Kuartil\|kuartil]] ke-3<br>$IQR=$ [[#*Interquartile Range* (IQR)\|interquartile range]] |
### Simpangan Rata-Rata *(Mean Deviation)*
Mengukur rata2 jarak data trhdp mean

| $SR=\frac{\sum\|x_i-\bar{x}\|}{n}$ | $SR=$ simpangan rata-rata<br>$x_{i}=$ data ke-i<br>$\bar{x}=$ [[#Mean\|mean]]<br>$n=$ jumlah data |
| ---------------------------------- | ------------------------------------------------------------------------------------------------- |
### Ragam (Varian)
Mengukur rata2 kuadrat selisih trhdp mean

| $\sigma=\frac{{\sum(x_{i}-\bar{x})^2}}{n}$ | $\sigma=$ ragam/varian<br>$x_{i}=$ data ke-i<br>$\bar{x}=$ [[#Mean\|mean]]<br>$n=$ jumlah data |
| ------------------------------------------ | ---------------------------------------------------------------------------------------------- |
### Simpangan Baku *(Standard Deviation)*
Mengukur penyebaran data bergantung pada mean

| $SB=\sqrt{ \sigma }$ | $SB=$ simpangan baku<br>$\sigma=$ [[#Ragam (Varian)\|ragam/varian]] |
| -------------------- | ------------------------------------------------------------------- |
### *Box and Whisker (Boxplot)*
## Exercises