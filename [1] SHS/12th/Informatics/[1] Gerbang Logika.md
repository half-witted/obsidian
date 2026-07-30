## Jenis
### Dasar
#### AND
| <center>A</center> | <center>B</center> | <center>OUT</center> |
| ------------------ | ------------------ | -------------------- |
| <center>0</center> | <center>0</center> | <center>0</center>   |
| <center>0</center> | <center>1</center> | <center>0</center>   |
| <center>1</center> | <center>0</center> | <center>0</center>   |
| <center>1</center> | <center>1</center> | <center>1</center>   |
![[Pasted image 20260722210306.png|167]]
#### OR
| <center>A</center> | <center>B</center> | <center>OUT</center> |
| ------------------ | ------------------ | -------------------- |
| <center>0</center> | <center>0</center> | <center>0</center>   |
| <center>0</center> | <center>1</center> | <center>1</center>   |
| <center>1</center> | <center>0</center> | <center>1</center>   |
| <center>1</center> | <center>1</center> | <center>1</center>   |
![[Pasted image 20260722210634.png|164]]
#### NOT
| <center>A</center> | <center>OUT</center> |
| ------------------ | -------------------- |
| <center>0</center> | <center>1</center>   |
| <center>1</center> | <center>0</center>   |
![[Pasted image 20260722210754.png|168]]
### Turunan
#### NAND (NOT AND)
| <center>A</center> | <center>B</center> | <center>OUT</center> |
| ------------------ | ------------------ | -------------------- |
| <center>0</center> | <center>0</center> | <center>1</center>   |
| <center>0</center> | <center>1</center> | <center>1</center>   |
| <center>1</center> | <center>0</center> | <center>1</center>   |
| <center>1</center> | <center>1</center> | <center>0</center>   |
![[Pasted image 20260722210923.png|167]]
#### NOR (NOT OR)
| <center>A</center> | <center>B</center> | <center>OUT</center> |
| ------------------ | ------------------ | -------------------- |
| <center>0</center> | <center>0</center> | <center>1</center>   |
| <center>0</center> | <center>1</center> | <center>0</center>   |
| <center>1</center> | <center>0</center> | <center>0</center>   |
| <center>1</center> | <center>1</center> | <center>0</center>   |
![[Pasted image 20260722211109.png|167]]
#### XOR (EXCLUSIVE OR)
| <center>A</center> | <center>B</center> | <center>OUT</center> |
| ------------------ | ------------------ | -------------------- |
| <center>0</center> | <center>0</center> | <center>0</center>   |
| <center>0</center> | <center>1</center> | <center>1</center>   |
| <center>1</center> | <center>0</center> | <center>1</center>   |
| <center>1</center> | <center>1</center> | <center>0</center>   |
![[Pasted image 20260722211212.png|167]]
#### XNOR (EXLUSIVE NOT OR)
| <center>A</center> | <center>B</center> | <center>OUT</center> |
| ------------------ | ------------------ | -------------------- |
| <center>0</center> | <center>0</center> | <center>1</center>   |
| <center>0</center> | <center>1</center> | <center>0</center>   |
| <center>1</center> | <center>0</center> | <center>0</center>   |
| <center>1</center> | <center>1</center> | <center>1</center>   |
![[Pasted image 20260722211306.png|164]]
## Penerapan
- AND: ATM, login akun (pw dan *username* benar)
- OR: lampu otomatis, alarm darurat
- etc