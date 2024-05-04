# belajar-git
## belajar git 2
### belajar git 2
lorem sfdxhg,kbml;mbvxff
## buah buahan
- apel
- jeruk
+ mangga
+ semangka
## logo
  ![logo markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/175px-Markdown-mark.svg.png)
## table
|no|nama|
|---|---|
|1|ahmad|
|2|beni|
```python
#program untuk mengubah teks menjadi format tanggal
#import packages datetime
from datetime import datetime


hari = str(input("Masukkan tanggal: "))
bulan = str(input("Masukkan bulan (angka): "))
tahun = str(input("Masukkan tahun (lengkap): "))
jam = str(input("Masukkan jam: "))
menit = str(input("Masukkan menit: "))


tanggal = hari + ' ' + bulan + ' ' + tahun + ' ' + jam + ':' + menit


datetime_object = datetime.strptime(tanggal, "%d %m %Y %H:%M")


print(type(datetime_object))
print(datetime_object)
```
