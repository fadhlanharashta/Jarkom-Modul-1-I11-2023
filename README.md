# Jarkom-Modul-1-I11-2023
Muhammad Fadhlan Ashila Harashta 5025211068 <br />
Hanifi Abrar Setiawan <br />
I Putu Arya Prawira Wiwekananda 5025211065 <br />

## No 1
## No 2
## No 3
Dapin sedang belajar analisis jaringan. Bantulah Dapin untuk mengerjakan soal berikut:<br />
a. Berapa banyak paket yang tercapture dengan IP source maupun destination address adalah 239.255.255.250 dengan port 3702? <br />
b. Protokol layer transport apa yang digunakan?<br />

```
ip.src == 239.255.255.250 || ip.dst == 239.255.255.250) && udp.port ==  3702
```
FILTER EXPRESSION <br />
![filterexpression3](https://cdn.discordapp.com/attachments/903112010504482836/1154437676989157537/9a20eabc-b2da-4779-bdd3-4c92a90e5a63.png)
ANSWER <br />
![jawaban3](https://cdn.discordapp.com/attachments/903112010504482836/1154438574377279620/image.png)
## No 4
## No 5
## No 6
## No 7
Berapa jumlah packet yang menuju IP 184.87.193.88?<br />
```
ip.dst == 184.87.193.88
```
FILTER EXPRESSION <br />
![filterexpression7](https://cdn.discordapp.com/attachments/934661338934943774/1154439675084284035/ae7fef6f-bca9-45fd-a3ff-c26fdf5471f6.png)
ANSWER <br />
![jawaban7](https://cdn.discordapp.com/attachments/934661338934943774/1154440364321689640/807fbe30-38eb-4867-b5e0-ef2e94a33383.png)
## No 8
Berikan kueri filter sehingga wireshark hanya mengambil semua protokol paket yang menuju port 80! (Jika terdapat lebih dari 1 port, maka urutkan sesuai dengan abjad)<br />
```
ip.dstport == 80 || udp.dstport == 80
```
FILTER EXPRESSION <br />
![filterexpression8](https://cdn.discordapp.com/attachments/934661338934943774/1154440828735996014/6c0e5200-4b46-4597-ad5d-3ed1098c0bda.png)
ANSWER <br />
![jawaban8](https://cdn.discordapp.com/attachments/934661338934943774/1154442034896183316/d42896e9-daf9-4966-95d0-4e8ed76b0929.jpg)
## No 9
Berikan kueri filter sehingga wireshark hanya mengambil paket yang berasal dari alamat 10.51.40.1 tetapi tidak menuju ke alamat 10.39.55.34!<br />
```
ip.src == 10.51.40.1 && ip.dst != 10.38.55.34
```
FILTER EXPRESSION <br />
![filterexpression9](https://cdn.discordapp.com/attachments/934661338934943774/1154441532561170442/cfcae0f3-69e8-4209-ad69-fe016f612603.png)
ANSWER <br />
![jawaban9](https://cdn.discordapp.com/attachments/934661338934943774/1154441280751939605/ba836980-d9cd-45ae-ac8e-ca6a200ebc66.jpg)
## No 10
