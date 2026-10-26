## Translasi (Pergeseran)
| $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}x+a\\y+b\end{pmatrix}$ | $(x,y)=$ koordinat asal<br>$a=$ pergeseran ke kanan $(+)$ atau kiri $(-)$<br>$b=$ pergeseran ke atas $(+)$ atau bawah $(-)$<br>$(x',y')=$ koordinat bayangan |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
## Refleksi (Pencerminan)
Syarat:
- Jarak benda ke cermin $=$ jarak bayangan ke cermin
- Benda, bayangan membentuk garis *perpendicular* dgn cermin

| <center>Refleksi</center> | <center>Matriks</center>                                                                                                                                                                 | <center>Keterangan</center>                                                           |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| Titik O $(0,0)$           | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}-x\\-y\end{pmatrix}$                                                                                                                  |                                                                                       |
| Sumbu $x$                 | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}x\\-y\end{pmatrix}$                                                                                                                   |                                                                                       |
| Sumbu $y$                 | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}-x\\y\end{pmatrix}$                                                                                                                   |                                                                                       |
| Garis $y=k$               | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}x\\2k-y\end{pmatrix}$                                                                                                                 | $k=$ konsanta yg menentukan posisi garis                                              |
| Garis $x=k$               | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}2k-x\\y\end{pmatrix}$                                                                                                                 |                                                                                       |
| Garis $y=x$               | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}y\\x\end{pmatrix}$                                                                                                                    |                                                                                       |
| Garis $y=-x$              | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}-y\\-x\end{pmatrix}$                                                                                                                  |                                                                                       |
| Garis $y=mx$              | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}\cos 2\theta&\sin 2\theta\\sin 2\theta&-\cos 2\theta\end{pmatrix}\begin{pmatrix}x\\y\end{pmatrix}$                                    | $m=$ gradien garis<br>$\theta=$ sudut antara garis $y=mx$ atau $y=mx+c$ dgn sumbu $x$ |
| Garis $y=mx+c$            | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}\cos 2\theta&\sin 2\theta\\sin 2\theta&-\cos 2\theta\end{pmatrix}\begin{pmatrix}x\\y-c\end{pmatrix}+\begin{pmatrix}0\\c\end{pmatrix}$ | $c=$ konstanta $y$ garis                                                              |
## Rotasi (Perputaran)
| <center>Pusat</center> | <center>Matriks</center>                                                                                                                                                                    |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| O $(0,0)$              | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}\cos \alpha&-\sin \alpha\\sin\space \alpha&\cos \alpha\end{pmatrix}\begin{pmatrix}x\\y\end{pmatrix}$                                     |
| $(a,b)$                | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}\cos \alpha&-\sin\alpha\\sin\space \alpha&\cos \alpha\end{pmatrix}\begin{pmatrix}x-a\\y-b\end{pmatrix}+\begin{pmatrix}a\\b\end{pmatrix}$ |

| <center>Sudut (*counter-clockwise*)</center> | <center>Matriks</center>                                                | <center>Keterangan</center> |
| -------------------------------------------- | ----------------------------------------------------------------------- | --------------------------- |
| $90^\circ$                                   | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}-y\\x\end{pmatrix}$  | $-90^\circ=270^\circ$       |
| $180^\circ$                                  | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}-x\\-y\end{pmatrix}$ | $-180^\circ=180^\circ$      |
| $270^\circ$                                  | $\begin{pmatrix}x'\\y'\end{pmatrix}=\begin{pmatrix}y\\-x\end{pmatrix}$  | $-270^\circ=90^\circ$       |
- *Counter-clockwise* $(+)$
- *Clockwise* $(-)$
## Dilatasi (Pembesaran)
| <center>Pusat</center> | <center>Matriks</center>                                                                                    |
| ---------------------- | ----------------------------------------------------------------------------------------------------------- |
| O $(0,0)$              | $\begin{pmatrix}x'\\y'\end{pmatrix}=k\begin{pmatrix}x\\y\end{pmatrix}$                                      |
| $(a,b)$                | $\begin{pmatrix}x'\\y'\end{pmatrix}=k\begin{pmatrix}x-a\\y-b\end{pmatrix}+\begin{pmatrix}a\\b\end{pmatrix}$ |
