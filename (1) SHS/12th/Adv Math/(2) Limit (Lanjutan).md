## Limit Fungsi Trigonometri
### Sifat Dasar
- Digunakan jika bentuk <mark style="background:#d4b106">subs fungsi jadi tak tentu.</mark> $\to\space \frac{0}{0},\frac{A}{0}$
- Hanya utk fungsi yg memuat <mark style="background:#d4b106">sin, tan,</mark>
- Dipasangin
	- Kalo <mark style="background:#d4b106">penyebut tk punya pasangan,</mark> otomatis <mark style="background:#d4b106">DNE</mark> $\to \frac{\sin ax}{x^2}, \frac{2\sin^2ax}{x^3}$ 
	- Kalo <mark style="background:#d4b106">pembilang tk punya pasangan,</mark> otomatis <mark style="background:#d4b106">0</mark> $\to \frac{2\sin^2ax}{x^2},\frac{\sin^2ax}{x}$

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
4. Dipasangin
	- Kalo <mark style="background:#d4b106">penyebut tk punya pasangan,</mark> otomatis <mark style="background:#d4b106">DNE</mark> $\to \frac{\sin ax}{x^2}, \frac{2\sin^2ax}{x^3}$ 
	- Kalo <mark style="background:#d4b106">pembilang tk punya pasangan,</mark> otomatis <mark style="background:#d4b106">0</mark> $\to \frac{2\sin^2ax}{x^2},\frac{\sin^2ax}{x}$
### Rumus Trigonometri
1. Identitas:
	- $\sin^2x+\cos^2x=1$
	- $1+\tan^2x=\sec^2x=\frac{1}{\sin x}$
	- $1+\cot^2x=\csc^2x$
2. Sudut rangkap: $1-\cos ax=2\sin^2\frac{a}{2}x$ 
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
1. Pake permisalan: $\frac{1}{x}=a \to x=\frac{1}{a}$
2. Ganti $\lim_{ x \to \infty } \to \lim_{ a \to 0 }$
3. Lanjut di [[#Limit Fungsi Trigonometri|limit fungsi trigonometri]]
## Asimtot
