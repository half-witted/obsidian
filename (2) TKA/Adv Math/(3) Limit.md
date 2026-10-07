## Definisi
- <mark style="background:#40a9ff">Nilai yang didekati</mark> oleh suatu fungsi.
- Fokus pd perilaku fungsi di <mark style="background:#40a9ff">sekitar titik, bukan pd titik.</mark>
- $\lim_{ x \to a }f(x)=L\to$ ketika $x$ makin mendekati $a$, nilai fungsi makin mendekati $L$
## Rules
| <center>Konstanta</center>                          | <center>Identity</center>                                                             | <center>Perkalian Konstanta</center>                                        | <center>Penjumalahan, Pengurangan</center>                                   |
| --------------------------------------------------- | ------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| $\lim_{ x \to a }c=c$                               | $\lim_{ x \to a }x=a$                                                                 | $\lim_{ x \to a }[c*f(x)]=c*\lim_{ x \to a }f(x)$                           | $\lim_{ x \to a }[f(x)\pm g(x)]=\lim_{ x \to a }f(x)\pm\lim_{ x \to a }g(x)$ |
| <center>**Pangkat**</center>                        | <center>**Pembagian**</center>                                                        | <center>**Perkalian**</center>                                              |                                                                              |
| $\lim_{ x \to a }[f(x)]^n=[\lim_{ x \to a }f(x)]^n$ | $\lim_{ x \to a }\frac{f(x)}{g(x)}=\frac{\lim_{ x \to a }f(x)}{\lim_{ x \to a }g(x)}$ | $\lim_{ x \to a }[f(x)*g(x)]=[\lim_{ a \to x }f(x)]*[\lim_{ x \to a }g(x)]$ |                                                                              |
## Nilai
### Langkah
- Subs $x$
- Hitung pake aljabar
- Tentukan nilai
### Hasil
1. Tentu
   Nilai blgn real (ex: $2, \frac{3}{6}, 0.67$)
2. Tk tentu
	- Jika nilai $\frac{0}{0}$ atau $\frac{\infty}{\infty}\to$ pemfaktoran atau [[#L'Hopital Rule]]
	- Jika nilai $\frac{a}{0}\to$ limit tk ada (DNE)
## L'Hopital Rule
Digunakan jika hasil $\frac{0}{0}$ atau $\frac{\infty}{\infty}$

| <center>Fungsi</center> | <center>L'Hopital</center> |
| ----------------------- | -------------------------- |
| Constant                | 0                          |
| $x^n$                   | $nx^{n-1}$                 |
| $ax^n$                  | $anx^{n-1}$                |
## Fungsi Kontinu
Hanya jika <mark style="background:#40a9ff">semua syarat terpenuhi:</mark>
- Function must be defined $\to f(a)$
- Limit kiri, kanan sama ($-:$ kiri, sebaliknya) $\to \lim_{ x \to a^- }f(x)=\lim_{ x \to a^+ }f(x)$
- Nilai limit $=$ fungsi $\to \lim_{ x \to a }f(x)=f(a)$
## Titik
- Nilai fungsi
	- Titik penuh (mengambang atau menempel pd garis)
	- Garis kontinu (tanpa titik kosong)
- Nilai limit
	- Titik kosong (mengambang atau menempel pd garis)
	- Titik penuh (menempel pd garis)
	- Garis kontinu (dengan atau tanpa titik penuh yg menempel)