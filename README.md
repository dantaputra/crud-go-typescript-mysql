# Website Database

Website sederhana untuk Create, Read, Update, dan Delete data MySQL dengan bahasa Go dan Typescript

Langkah-langkah:
- Buat database bernama 'gosql' dan tabel di database mysql dengan nama tabel 'obat'

```java
DROP TABLE IF EXISTS `obat`;
CREATE TABLE `obat` (
  `id_obat` int(6) unsigned NOT NULL AUTO_INCREMENT,
  `kode_obat` varchar(10) NOT NULL,
  `nama_obat` varchar(255) NOT NULL,
  `harga` int(10) NOT NULL,
  PRIMARY KEY (`id_obat`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;
```

- Ketikan perintah ini di terminal atau di git command
> git clone https://github.com/dantaputra/crud-go-typescript-mysql.git
- Masuk ke dalam folder project go dan jalankan perintah
> go run main.go
- Buka browser dan buka link berikut
> http://localhost:8080/

Tampilan website yang telah diisi beberapa data dapat dilihat pada gambar berikut

![Screenshot 2023-01-31 162021](https://user-images.githubusercontent.com/58434914/215720942-13cc0d57-7356-4fcd-a949-9f8dda6f217d.jpg)
