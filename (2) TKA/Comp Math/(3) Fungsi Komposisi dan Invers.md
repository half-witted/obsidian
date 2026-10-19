## Fungsi Komposisi
Fungsi $f$ komposisi $g$ $\to (f\circ g)(x)$ atau $f(g(x))$
### Konsep
#### Syarat
$(f\circ g)(x)\to R_{g}\subset D_{f}$
$(g\circ f)(x)\to R_{f}\subset D_{g}$
#### Sifat
1. Tk komutatif $\to(f\circ g)(x)\neq (g\circ f)(x)$
2. Asosiatif $\to((f\circ g)\circ h(x))=(f\circ(g\circ h)(x))$
### Komposisi 2 Fungsi
$(f\circ g)(x)=f(g(x))$
#### Nilai Fungsi
Tinggal subs2
#### Salah Satu Fungsi Penyusun
- Diketahui $(f\circ g)(x)$ dan $f(x)$ $\to$ tinggal subs
- Diketahui $(f\circ g)(x)$ dan $g(x)$ $\to$ pake permisalan
### Komposisi 3 Fungsi
$(f\circ g\circ h)(x)=f(g(h(x)))$
## Fungsi Invers
- Fungsi <mark style="background:#40a9ff">kebalikan</mark> dr <mark style="background:#40a9ff">suatu fungsi</mark>
- $f(x)=y$ jika dan hanya jika $f^{-1}(y)=x$
### Konsep
#### Syarat
Harus fungsi bijektif atau fungsi korespondensi satu2.
- $n(A)=n(B)$
- Tiap anggota $A$ berpasangan tepat 1 dgn anggota $B$
#### Metode
1. Buat $y=f(x)$
2. Ubah $y=f(x)$ jadi $x=$
3. Subs ke $x=f^{-1}(y)$
4. Ganti $y$ dgn $x$
### Aplikasi
| <center>Jenis</center> | <center>Fungsi</center>  | <center>Invers</center>                           | <center>Tambahan</center>                                                                                                                                |
| ---------------------- | ------------------------ | ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Linear                 | $f(x)=ax+b$              | $f^{-1}(x)=\frac{x-b}{a}$                         | - <mark style="background:#d4b106">Semua fungsi linear</mark> merupakan fungsi <mark style="background:#d4b106">bijektif</mark><br>- $a\neq 0$           |
| Rasional               | $f(x)=\frac{ax+b}{cx+d}$ | $f^{-1}(x)=\frac{-dx+b}{cx-a}$                    | $x\neq -\frac{d}{c}\to x\neq \frac{a}{c}$                                                                                                                |
| Kuadrat                | $f(x)=ax^2+bx+c$         | $f^{-1}(x)=\frac{-b\pm \sqrt{ b^2-4a(c-x) }}{2a}$ | 1. Pake $x_{p}=-\frac{b}{2a}$<br>2. Domain fungsi dibatasi jd $D_{f}\leq-\frac{b}{2a}$ dan $D_{f}\geq-\frac{b}{2a}$<br>3. Pake kuadrat sempurna atau ABC |
| Irasional              | $f(x)=\sqrt{ x }$        |                                                   | - $x\geq 0$<br>- Pake [[#Metode\|metode]]                                                                                                                |
| Eksponen               | $f(x)=n^x$               |                                                   | - Invers $=$ fungsi log<br>- Pake [[#Metode\|metode]]                                                                                                    |
## Invers dari Fungsi Komposisi
### Fungsi Identitas
$I(x)=x$
- Anggota domain, range selalu sama
- Jika $f(x)$ dikomposisikan dgn $I(x)\to(f\circ I)(x)=(I\circ f)(x)=f(x)$
- $(f\circ f^{-1})(x)=(f^{-1}\circ f)(x)=I(x)=x$
