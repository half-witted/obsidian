## *Data Cleaning*
- Membersihkan data kosong, rusak, tk sesuai format, duplikat
- *Garbage In, Garbage Out* (GIGO): jika datanya buruk (sampah), hasilnya juga
- Data kosong, pake mean
## Hubungan Variabel
- Korelasi biasa
	- Hanya menunjukkan 2 variable bergerak bersamaan, bukan sebab-akibat
	- Meskipun tinggi, belum tentu kausalitas
- Kausalitas
	- Menunjukkan hubungan sebab-akibat
	- Korelasi $\neq$ kausalitas, harus bener2 diteliti
## Regresi Linear
### Variabel Bebas dan Terikat
Bebas $x$, terikat $y$
### Garis Regresi
| $y=a+bx$ | $b<0\to$ negatif/turun (berbanding terbalik)<br>$b=0\to$ tk ada pengaruh<br>$b>0\to$ positif/naik (searah) |
| -------- | ---------------------------------------------------------------------------------------------------------- |
- Garis lurus terbaik
- Utk prediksi nilai $y$, jika $x$ diketahui
### Koefisien Korelasi ($r$) dan Determinasi ($R^2$)
- Korelasi: seberapa kuat hubungan linear $\to$ negatif/menurun: berbanding terbalik, positif/menaik: searah
- Determinasi: seberapa besar pengaruh
### *Skewness*
Konsentrasi data (negatif: terkonsentrasi di kanan, positif: di kiri)
## Excel
| <center>Rumus</center> | <center>Command</center>       |
| ---------------------- | ------------------------------ |
| Mean                   | ```=AVERAGE()```               |
| Median                 | ```=MEDIAN()```                |
| Modus                  | ```=MOD()```                   |
| Simpangan baku         | ```=STDEV()```                 |
| Variasi                | ```=STDEV()/AVEGAGE() * 100``` |
| Korelasi               | ```=CORREL(A, B)```            |
| Determinasi            | ```=CORREL(A, B)^2```          |
| *Skewness*             | ```=SKEW```                    
## Exercise(s)
