# Tugas1_Netpro_1301188566

## nomor 1

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

## nomor 2
Melakukan perulangan for sesuai dengan nilai yang sudah ditentukan dengan nilai awal i=1. Didalam perulangan for yang pertama mencetak nilai i selama i<=3, maka hasilnya akan 1 2 3. Didalam perulangan for yang kedua mencetak nilai j selama j<=9 dimana nilai awal j adalah 7, maka hasilnya adalah 7 8 9.  Perulangan for yang ketiga adalah loop forever yang mencetak string “loop”. 

Pada program if/else akan melakukan pengecekan pada suatu kondisi. Jika kondisi tersebut terpenuhi maka akan melakukan aksi dari kondisi tersebut.

## nomor 3
Array adalah sekumpulan data yang sama, yang disimpan dalam sebuah variabel. Array memiliki kapasitas yang nilainya ditentukan pada saat pembuatan, menjadikan elemen/data yang disimpan di array tersebut jumlahnya tidak boleh melebihi yang sudah dialokasikan. Default nilai tiap elemen array pada awalnya tergantung dari tipe datanya. Jika int maka tiap element zero value-nya adalah 0, jika bool maka false, dan seterusnya. Setiap elemen array memiliki indeks berupa angka yang merepresentasikan posisi urutan elemen tersebut. Indeks array dimulai dari 0.

Function merupakan sekumpulan pernyataan yang jika namanya dipanggil maka ia akan dijalankan. Didalam program, function memanggil func plus dan func plusPlus. Func plus mengembalikan nilai a+b, dan func plusPlus mengembalikan nilai a+b+c.
## nomor 4
Struct merupakan instruksi untuk membuat tipe data bentukan. Struct mempunyai berbagai macam variabel yang tipe datanya berbeda. Saat pemanggilan struct jika terdapat variabel yang tidak terdefinisi nilainya, maka nilai tersebut akan menjadi 0 atau nil

Method merupakan fungsi yang memiliki akses terhadap properti struck. Untuk memanggilnya harus diawali dengan variabel struct. 

## nomor 5
Multiple Return adalah fungsi yang dapat mengembalikan lebih dari 1 nilai

Commamd line merupakan interaksi dengan system operasi atau perangkat lunak computer dengan cara mengetik perintah untuk menjalankannya.

## nomor 6
Didalam program handlefunc berfungsi untuk menentukan route/konten ketika akan diakses, dan listenAndServe berfungsi untuk menentukan port yang digunakan ketika ingin mengakses

*catatan : 
