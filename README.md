# Original code of broadcast chat
![terminal](img.png)
Pada gambar di atas, client dan server saling terhubung melalui websocket. Server akan mendengarkan input pesan dari Client dan meneruskan pesan tersebut ke seluruh client yang ada. Ketika kita membuat pesan di client 1 akan terlihat di seluruh client, begitu juga dengan client 2 atau 3, dan seterusnya.

# Modifying the websocket port
Jika kita ingin mengubah port pada client atau server, kita perlu memastikan bahwa keduanya berada pada port yang sama. Hal ini diperlukan agar client dan server bisa sama-sama terhubung. Jika client dan server tidak terhubung, kita tidak dapat meneruskan pesan dari client ke server dan sebaliknya.

