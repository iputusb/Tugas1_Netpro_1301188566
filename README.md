# Tugas1_Netpro_1301188566

## Soal Nomer 1

![image](https://user-images.githubusercontent.com/54670695/65815797-29d17580-e21e-11e9-9f4c-620fc02e2a85.png)

Finite State Machine adalah model logis untuk perilaku sistem yang kondisi internal berubah dengan terjadinya peristiwa yang ditentukan
Server:
 - Server dimulai starting point
 - Server membuat koneksi secara passive open(LISTEN)
 - Server menerima SYN lalu mengirimkan SYN,ACK ke SYN RCVD
 - Server menerima ACK di CONNECTION ESTABLISHED
 - Server menerima FIN lalu mengirimkan ACK ke CLOSE WAIT
 - Server mengirimkan FIN ke LAST ACK
 - Server menerima ACK lalu mengakhiri koneksi(CLOSED)
Client:
 - Client active open
 - CLient mengirimkan SYN ke SYN SENT
 - Client menerima SYN,ACK kemudian mengirimkan ACK ke CONNECTION ESTABLISHED
 - Client mengirimkan FIN ke FIN WAIT 1
 - Client menerima ACK ke FIN WAIT 2
 - Client menerima FIN lalu mengirimkan ACK ke TIME WAIT
 - Timeout, maka koneksi berakhir(CLOSED)

## Soal Nomer 2

![image](https://user-images.githubusercontent.com/54670695/65815857-bc721480-e21e-11e9-89a6-f52c761df535.png)

Melakukan perulangan for sesuai dengan nilai yang sudah ditentukan dengan nilai awal i=1. Didalam perulangan for yang pertama mencetak nilai i selama i<=3, maka hasilnya akan 1 2 3. Didalam perulangan for yang kedua mencetak nilai j selama j<=9 dimana nilai awal j adalah 7, maka hasilnya adalah 7 8 9.  Perulangan for yang ketiga adalah loop forever yang mencetak string “loop”. 

![image](https://user-images.githubusercontent.com/54670695/65815879-03600a00-e21f-11e9-91f2-796c3d0ab7c4.png)

Pada program if/else akan melakukan pengecekan pada suatu kondisi. Jika kondisi tersebut terpenuhi maka akan melakukan aksi dari kondisi tersebut.

## Soal Nomer 3

![image](https://user-images.githubusercontent.com/54670695/65815897-33a7a880-e21f-11e9-9f2a-4a2e4310ba5b.png)

Array adalah sekumpulan data yang sama, yang disimpan dalam sebuah variabel. Array memiliki kapasitas yang nilainya ditentukan pada saat pembuatan, menjadikan elemen/data yang disimpan di array tersebut jumlahnya tidak boleh melebihi yang sudah dialokasikan. Default nilai tiap elemen array pada awalnya tergantung dari tipe datanya. Jika int maka tiap element zero value-nya adalah 0, jika bool maka false, dan seterusnya. Setiap elemen array memiliki indeks berupa angka yang merepresentasikan posisi urutan elemen tersebut. Indeks array dimulai dari 0.

![image](https://user-images.githubusercontent.com/54670695/65815899-399d8980-e21f-11e9-8b46-c3103e3624f6.png)

Function merupakan sekumpulan pernyataan yang jika namanya dipanggil maka ia akan dijalankan. Didalam program, function memanggil func plus dan func plusPlus. Func plus mengembalikan nilai a+b, dan func plusPlus mengembalikan nilai a+b+c.

## Soal Nomer 4

![image](https://user-images.githubusercontent.com/54670695/65815908-5934b200-e21f-11e9-8e5f-d6911d10f558.png)

Struct merupakan instruksi untuk membuat tipe data bentukan. Struct mempunyai berbagai macam variabel yang tipe datanya berbeda. Saat pemanggilan struct jika terdapat variabel yang tidak terdefinisi nilainya, maka nilai tersebut akan menjadi 0 atau nil

![image](https://user-images.githubusercontent.com/54670695/65815911-605bc000-e21f-11e9-8e27-f2c13cb62aee.png)

Method merupakan fungsi yang memiliki akses terhadap properti struck. Untuk memanggilnya harus diawali dengan variabel struct. 

## Soal Nomer 5
![image](https://user-images.githubusercontent.com/54670695/65815918-8bdeaa80-e21f-11e9-8d71-c31f531aa9b9.png)

Multiple Return adalah fungsi yang dapat mengembalikan lebih dari 1 nilai

![image](https://user-images.githubusercontent.com/54670695/65815919-90a35e80-e21f-11e9-9640-511a9d270fb3.png)

Commamd line merupakan interaksi dengan system operasi atau perangkat lunak computer dengan cara mengetik perintah untuk menjalankannya.

## Soal Nomer 6

![image](https://user-images.githubusercontent.com/54670695/65815927-a9137900-e21f-11e9-822c-c0d686b7b839.png)

Didalam program handlefunc berfungsi untuk menentukan route/konten ketika akan diakses, dan listenAndServe berfungsi untuk menentukan port yang digunakan ketika ingin mengakses

## Soal Nomer 7

[![SS-7.png](https://i.postimg.cc/3Rb0W9zZ/SS-7.png)](https://postimg.cc/62npmVW7)

Untuk nomer 7, pertama kita harus membuat file config.json sebagai konfigurasinya. Didalam file config.json mempunyai tipe data server dan juga memiliki atribut berupa port. Fungsi http didalam GO adalah untuk mengambil nomer port dari config.json dengan menggunakan viper(sintaks viper.GetString("server.port")), yang nanti akan digunakan untuk mengembalikan nilai port dari tipe data server yang ada didalam konfig.json
