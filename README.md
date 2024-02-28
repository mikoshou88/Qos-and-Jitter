# Pengukuran QoS Throughput, Packet Loss, Delay dan Jitter menggunakan Wireshark

## Penjelasan tentang Wireshark

<p align="center" style="margin-bottom: 0px !important;">
  <img width="200" src="wire.png" alt="Alma" align="center">
</p>

<p align="center" >Wireshark adalah perangkat lunak analisis jaringan yang memungkinkan pengguna untuk memonitor, menganalisis, dan memecahkan masalah dalam lalu lintas jaringan dengan cara yang mendetil, melalui kemampuannya untuk merekam dan menganalisis paket data yang dikirim dan diterima dalam suatu jaringan komputer.</p>

## Menjalankan pengukuran
Untuk mendapatkan parameter Time di Wireshark, kalian terlebih dahulu menonton youtube atau bermain game online. Disini saya menonton youtube selama 10 menit untuk mendapatkan parameter Time.

#### 1. Buka Wireshark dan pilih wifi lalu buka youtube dan tonton sampai waktu yang ditentukan.
![1](1.jpg)

#### 2. Lalu buka Wireshark lagi dan data-data parameter akan keluar, dari Time, Source, Destination dan lainnya.
![2](3.jpg)

#### 3. Lalu kita akan mengukur `Throughput`, untuk melihat time span dan bytes kita harus pergi ke statistics lalu `Capture File Properties`
![3](13.jpg)

#### 4. Lalu, kita catat time span dan bytes, dan kita cari maka nanti hasilnya akan sama dengan Avarage bits/s
![4](4.jpg)

#### 5. Kita cari dengan rumus seperti dibawah ini
![5](5.jpg)
