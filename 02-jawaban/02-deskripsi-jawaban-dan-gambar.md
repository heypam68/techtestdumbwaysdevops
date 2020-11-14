02. Grep di gunakan untuk mencari frase atau kata yang berbentuk string  tertentu. 
pada seperti contoh mau mencari kata local di folder ssh/autkey , disini menggunakan paramater/option -r sehingga subdirektori dapat di cari juga dengan kata kunci local dan -i kata kunci dapat diabaikan huruf besar dan kecil tidak case sensitive tetapi dengan string yang sama. dengan perintah 
$ grep -r -i “local” .ssh/authorized_keys
