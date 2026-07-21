## Konsep
### Definisi
- Kumpulan informasi/data yg rapi, teratur
- Bisa disimpan di komputer, fisik
- Jaga data ttp konsisten, bisa digunakan bersama, mengurangi duplikasi
### Struktur
- *Table*
- *Field* (kolom)
- *Record* (baris, kecuali kategori)
- *Query:* permintaan data spesifik
- Tipe data: *string/text, float, character, boolean, integers*
- *Entity:* objek yg dibuatkan *database*
### Tipe
#### Flat File
Hanya menyimpan 1 tabel data, tk terikat dgn tabel lain

| <center>Kekurangan</center> | <center>Penjelasan</center>                                                          |
| --------------------------- | ------------------------------------------------------------------------------------ |
| Integritas data             | Tk ada validasi kualitas data (duplikat, format salah, kosong)                       |
| Privasi data                | Semua disimpan di 1 tabel, yg umum maupun privat                                     |
| Redundansi data             | Data yg sama disimpan berkali2 (duplikat: semua sama, redundansi: disimpan berkali2) |
| Inkonsistensi data          | Tk bisa otomatis mengubah semua isi data duplikat                                    |
#### Relational Database
Tabel2 terpisah yg saling terhubung
- *Primary key:* kolom khusus berisi kode unik, beda
## Relasi dan Kueri
### Kardinalitas dan *Entity Relationship Diagram* (ERD)
#### Kardinalitas
#### *Entity Relationship Diagram* (ERD)
### *Structured Query Language* (SQL)
| <center>Kode</center> | <center>Kegunaan</center>                                           |
| --------------------- | ------------------------------------------------------------------- |
| ```SELECT```          | Memilih data                                                        |
| ```FROM```            |                                                                     |
| ```WHERE```           | Menetapkan kondisi                                                  |
| ```ORDER BY```        | Mengurutkan (```ASC```: kecil ke besar, ```DESC```: besar ke kecil) |
| ```SUM()```           | Penjumlahan, hanya bisa data angka                                  |
| ```COUNT()```         | Perhitungan                                                         |
## Exercise(s)