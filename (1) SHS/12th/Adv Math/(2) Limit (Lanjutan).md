## Limit Fungsi Trigonometri
### Sifat Dasar
- Digunakan jika bentuk <mark style="background:#d4b106">subs fungsi jadi tak tentu.</mark> $\to\space \frac{0}{0},\frac{A}{0}$
- Hanya utk fungsi yg memuat <mark style="background:#d4b106">sin, tan,</mark>

| <center>Koefisien sama</center>           | <center>Koefisien beda</center>                       |
| ----------------------------------------- | ----------------------------------------------------- |
| $\lim_{ x \to 0 }\frac{\sin x}{x} = 1$    | $\lim_{ x \to 0 }\frac{\sin ax}{bx}=\frac{a}{b}$      |
| $\lim_{ x \to 0 }\frac{x}{\sin x}=1$      | $\lim_{ x \to 0 }\frac{ax}{\sin bx}=\frac{a}{b}$      |
| $\lim_{ x \to 0 }\frac{\tan x}{x}=1$      | $\lim_{ x \to 0 }\frac{\tan ax}{bx}=\frac{a}{b}$      |
| $\lim_{ x \to 0 }\frac{x}{\tan x}=1$      | $\lim_{ x \to 0 }\frac{ax}{\tan bx}=\frac{a}{b}$      |
| $\lim_{ x \to 0 }\frac{\sin x}{\tan x}=1$ | $\lim_{ x \to 0 }\frac{\sin ax}{\tan bx}=\frac{a}{b}$ |
| $\lim_{ x \to 0 }\frac{\tan x}{\sin x}=1$ | $\lim_{ x \to 0 }\frac{\tan ax}{\sin bx}=\frac{a}{b}$ |
| $\lim_{ x \to 0 }\frac{\sin x}{\sin x}=1$ | $\lim_{ x \to 0 }\frac{\sin ax}{\sin bx}=\frac{a}{b}$ |
| $\lim_{ x \to 0 }\frac{\tan x}{\tan x}=1$ | $\lim_{ x \to 0 }\frac{\tan ax}{\tan bx}=\frac{a}{b}$ |
### Memuat Cosinus
1. Subs
2. Jika bentuk tk tentu, pake sifat dasar
3. Kalo <mark style="background:#d4b106">cosinus buat</mark> fungsi jadi <mark style="background:#d4b106">tk tentu,</mark> ubah jadi <mark style="background:#d4b106">sin atau tan</mark> pake [[#Rumus Trigonometri|rumus trigonometri]]
### Rumus Trigonometri
1. Identitas:
	- Dasar:
		- $\sin^2x+\cos^2x=1$
		- $1+\tan^2x=\sec^2x$
		- $1+\cot^2x=\csc^2x$
	- Perbandingan:
		- $\cot x=\frac{1}{\tan x}$
		- $\sec x=\frac{1}{\cos x}$
		- $\csc x=\frac{1}{\sin x}$
2. Sudut rangkap: 
	- $\sin 2x=2\sin x\cos x$
	- $\cos ax=1-2\sin^2\frac{a}{2}x$ 
	- $\cos ax=\cos^2\frac{a}{2}x-\sin^2\frac{a}{2}x$
	- $\cos ax=2\cos^2x-1$
3. Jumlah sudut, selisih sudut: $\cos A-\cos B=-2\sin\frac{1}{2}(A+B)\sin\frac{1}{2}(A-B)$
## Limit Tak Hingga
- Pd aljabar linear, subs $x$ dgn $\infty$. 
- $\infty$ dibagi, dikurangi, dijumlah dgn apapun masih $\infty$
### Bentuk Pecahan
Tentukan derajat tertinggi dr pembilang, penyebut

| <center>Kondisi</center> | <center>Shortcut                                     |
| ------------------------ | ---------------------------------------------------- |
| Pembilang $>$ penyebut   | $\lim_{ x \to \infty }\frac{x^3}{x^2}=0$             |
| Pembilang $=$ penyebut   | $\lim_{ x \to \infty }\frac{1x^2}{2x^2}=\frac{1}{2}$ |
| Pembilang $<$ penyebut   | $\lim_{ x \to \infty }\frac{x^2}{x^3}=\infty$        |
### Bentuk Akar
Bentuk umum: $\sqrt{ ax^2+bx+c }-\sqrt{ px^2+qx+r }$ (jadikan gini semua)

| <center>Kondisi</center> | <center>Hasil</center>    |
| ------------------------ | ------------------------- |
| $a>p$                    | $\infty$                  |
| $a=p$                    | $\frac{b-q}{2\sqrt{ a }}$ |
| $a<p$                    | $-\infty$                 |
### Fungsi Trigonometri
$-\frac{1}{x}\leq \frac{\sin ax}{x},\frac{\cos ax}{x} \leq \frac{1}{x} \to  o\leq \frac{\sin ax}{x},\frac{\cos ax}{x}\leq 0$
1. Pake permisalan: $\frac{1}{x}=a \to x=\frac{1}{a}$
2. Ganti $\lim_{ x \to \infty } \to \lim_{ a \to 0 }$
3. Lanjut di [[#Limit Fungsi Trigonometri|limit fungsi trigonometri]]

\color{#1971c2}
\color{#2f9e44}