# Monster Kill
### Seorang pangeran harus membunuh 2 monster yang ada di hutan. Pangeran memiliki kapasitas power untuk membunuh setiap monster. Jika dia berhasil membunuh sebuah monster, maka power dari monster tersebut akan *diserap* oleh sang pangeran. Sang pangeran *hanya* mampu membunuh monster yang powernya lebih kecil dari sang pangeran. Jika tidak berhasil membunuh kedua monster maka sang pangeran dinyatakan tewas.

## Masukan
### Terdiri dari sebuah bilangan bulat P yang menyatakan power dari sang pangeran diikuti oleh 2 bilangan bulat terdiri dari  m<sub>1</sub> sebagai power monster pertama dan m<sub>2</sub> sebagai power dari monster kedua.

## Keluaran
### Sebuah bilangan yang power akhir dari sang pangeran atau sebuah string  "tewas" jika gagal membunuh monster.

## Contoh
| Input  | Output  | Pembahasan |
|:---:   |:---:    | :--- |
| 5 <br>3 7    | 15       | 5 + 3 = 8; 8 + 7 = 15 |
| 6 <br> 4 10  | tewas    | 6 + 4 = 10; 10 !> 10 |
| 3 <br>3 3    | tewas    |
***



>Hint  
&ensp; Tidak ada