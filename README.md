# Merubah username & passwd

```
# created by K1M4K-ID
$ usermod -l kimak -d /home/kimak -m kali

usermod adalah perintah untuk mengubah pengaturan pengguna di sistem.
-l kimak mengubah nama pengguna dari "kali" menjadi "kimak".
-d /home/kimak mengubah direktori rumah pengguna menjadi "/home/kimak".
-m memindahkan konten dari direktori rumah lama ke yang baru (dalam hal ini, dari "/home/kali" ke "/home/kimak").

$ groupmod -n kimak kali

groupmod digunakan untuk mengubah properti grup, tetapi dalam contoh ini,
tampaknya ada kesalahan karena opsi -n seharusnya digunakan untuk mengganti nama grup.
Seharusnya groupmod -n kimak kali untuk mengganti nama grup "kali" menjadi "kimak".

$ ln -s /home/kimak /home/kali:

ln adalah perintah untuk membuat tautan antara file atau direktori.
-s membuat tautan simbolik (symbolic link).
Ini membuat tautan simbolik dari "/home/kimak" ke "/home/kali", yang berarti bahwa ketika Anda mengakses "/home/kali",
sebenarnya Anda akan mengakses konten dari "/home/kimak".

$ chfn -f "kimak":

chfn digunakan untuk mengubah informasi perubahan pengguna, seperti nama lengkap pengguna.
-f "kimak" mengubah nama lengkap pengguna menjadi "kimak".

# restart lalu login

username : kimak

password : kali


# merubah password 

$ passwd kimak

masukan password baru :

ketikan ulang password :

# restart lalu login

username : kimak

password : password baru
```
