## Konversi
| <center>Satuan</center> | <center>Simbol</center> | <center>Pangkat</center> |
| ----------------------- | ----------------------- | ------------------------ |
| Kilo                    | $k$                     | $10^3$                   |
| Senti                   | $c$                     | $10^{-2}$                |
| Mili                    | $m$                     | $10^{-3}$                |
| Mikro                   | $\mu$                   | $10^{-6}$                |
| Nano                    | $n$                     | $10^{-9}$                |
| Piko                    | $p$                     | $10^{-12}$               |
## Arus
### Arah Alir
Mengalir kalo ada <mark style="background:#d4b106">perbedaan potensial</mark>
- Muatan <mark style="background:#d4b106">positif: potensial tinggi (lbh banyak) ke rendah (lbh dikit)</mark>
- Muatan <mark style="background:#d4b106">negatif: potensial tinggi (lbh dikit) ke rendah (lbh banyak)</mark>
- Kebalikan arah elektron
### Kuat
| $I=\frac{Q}{t}$<br>^kuat-arus | $I=$ kuat arus $(A)$<br>$Q=$ muatan $(C)$<br>$t=$ waktu $(s)$ |
| ----------------------------- | ------------------------------------------------------------- |
### Hubungan dengan Elektron
| $Q=ne$ | $Q=$ muatan<br>$n=$ jumlah elektron<br>$e=-1,6*10^{-19}\space C=$ muatan yg dibawa 1 elektron |
| ------ | --------------------------------------------------------------------------------------------- |
### Alat Ukur
- Kuat arus: amperemeter dgn pemasangan seri
- Tegangan: voltmeter dgn pemasangan paralel
## Hambatan
| $R=\frac{V}{I}$<br>^hambatan | $R=$ [[#^hambatan-juga\|hambatan]] $(\ohm)$<br>$V=$ tegangan $(V)$<br>$I=$ [[#Kuat\|kuat arus]] $(A)$ |
| ---------------------------- | ----------------------------------------------------------------------------------------------------- |
<mark style="background:#40a9ff">Dlm kondisi ideal, hambatan tk berubah.</mark> $\to$ kalo tegangan dikali 2, kuat arus otomatis dikali 2 jg
### Faktor Pemengaruh
| $R=\frac{\rho l}{A}$<br>^hambatan-juga | $R=$ [[#^hambatan\|hambatan]] $(\ohm)$<br>$\rho=$ hambat jenis $(\ohm m)$<br>$l=$ panjang penghantar $(m)$<br>$A=$ luas penampang $(m^2)$ |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
### Pengaruh Suhu
| <center>Rumus</center>                                                             | <center>Keterangan</center>                                                                                                                                                                              |
| ---------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| $\triangle T=T'-T_{0}$                                                             | $\triangle T=$ perubahan suhu $(^{\circ}C)$<br>$T'=$ suku akhir $(^{\circ}C)$<br>$T_{0}=$ suhu awal $(^{\circ}C)$                                                                                        |
| $\begin{aligned}\triangle R &= R_{0}\alpha\triangle T \\ &= R'-R_{0}\end{aligned}$ | $\triangle R=$ perubahan hambatan $(\ohm)$<br>$R_{0}=$ hambatan awal $(\ohm)$<br>$\alpha=$ koefisien muai $(/^{\circ}C)$<br>$\triangle T=$ perubahan suhu $(^{\circ}C)$<br>$R'=$ hambatan akhir $(\ohm)$ |
![[Pasted image 20261010155215.png]]
### Rangkaian
#### Simbol
| <center>Komponen</center> | <center>Simbol</center>                                                          |
| ------------------------- | -------------------------------------------------------------------------------- |
| Saklar                    | ![[Pasted image 20261010140922.png\|90]]![[Pasted image 20261010141009.png\|94]] |
| Lampu/resistor            | ![[Pasted image 20261010141158.png\|212]]                                        |
| Sumber tegangan           | ![[Pasted image 20261010141222.png\|263]]                                        |
| Hambatan                  | ![[Pasted image 20261010141255.png\|257]]                                        |
#### Seri
Dipasang scr <mark style="background:#9254de">berdampingan</mark>
![[Pasted image 20261010141526.png|232]]

| <center>Rumus</center>                                        | <center>Keterangan</center>                     |
| ------------------------------------------------------------- | ----------------------------------------------- |
| $I_{s}=I_{1}=I_{2}=\dots=I_{n}$                               | $I_{s}=$ [[#^kuat-arus\|kuat arus seri]] $(A)$  |
| $R_{s}=R_{1}+R_{2}+\dots +R_{n}$                              | $R_{s}=$ [[#^hambatan\|hambatan seri]] $(\ohm)$ |
| $V_{s}=V_{1}+V_{2}+\dots+V_{n}$                               | $V_{s}=$ [[#^hambatan\|tegangan seri]] $(V)$    |
| $\frac{V_{1}}{V_{2}}=\frac{R_{1}}{R_{2}}=\frac{I_{2}}{I_{1}}$ |                                                 |
| $V_{n}=\frac{R_{n}}{R_{s}}V_{s}$                              |                                                 |
- Kelemahan: jika 1 lampu putus, seluruh lampu padam
- Manfaat: arus ttp sama meskipun hambatan beda, kabel lbh dikit
#### Paralel
Dipasang scr <mark style="background:#9254de">bercabang</mark>
![[Pasted image 20261010143904.png|179]]

| <center>Rumus</center>                                                  | <center>Keterangan</center>                        |
| ----------------------------------------------------------------------- | -------------------------------------------------- |
| $I_{p}=I_{1}+I_{2}+\dots+I_{n}$                                         | $I_{p}=$ [[#^kuat-arus\|kuat arus paralel]] $(A)$  |
| $\frac{1}{R_{p}}=\frac{1}{R_{1}}+\frac{1}{R_{2}}+\dots+\frac{1}{R_{n}}$ | $R_{p}=$ [[#^hambatan\|hambatan paralel]] $(\ohm)$ |
| $V_{p}=V_{1}=V_{2}=\dots=V_{n}$                                         | $V_{p}=$ [[#^hambatan\|tegangan paralel]] $(V)$    |
| $\frac{V_{1}}{V_{2}}=\frac{R_{2}}{R_{1}}=\frac{I_{2}}{I_{1}}$           |                                                    |
| $I_{n}=\frac{R_{p}}{R_{n}}I_{p}$                                        |                                                    |
- Kelemahan: kabel lbh banyak, arus tk sama
- Manfaat: seluruh lampu nyala, jika 1 rusak yg lain aman
## Hukum Kirkchoff
### Hukum I
$\sum I_{masuk}=\sum I_{keluar}$
### Hukum II
| $\sum\epsilon+\sum IR=0$ | $\epsilon=$ gaya gerak (GGL) |
| ------------------------ | ---------------------------- |
#### Aturan
1. Pilih *loop* (bebas)
	- Searah dgn kuat arus $\to$ penurunan tegangan $(IR)$ positif
	- Berlawanan $\to$ negatif
2. Pas ikut *loop*
	- Ketemu kutub positif dulu $\to$ ggl $(\epsilon)$ positif
	- Negatif dulu $\to$ negatif
#### 1 *Loop*
##### Langkah
1. Tentukan *loop*
2. Tentukan arah
3. Tentukan $\epsilon$ dan $IR$ tiap cabang
4. Masukan ke rumus
#### 2 *Loop*
Lgsg pake rumus
1. Pake 2 titik dgn cabang plg banyak
2. Pilih salah 1 jd acuan
3. Jadikan semua arus keluar dr acuan
4. Tinjau beda potensial 2 titik

| $V_{AB}=$ |     |
| --------- | --- |

