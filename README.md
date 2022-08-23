# Installation Ubuntu Server VMware

1. Buka Virtual machine kalian, untuk contohnya disini menggunakan VMware. Jika sudah langsung klik saja di bagian __Create a new Virtual Machine__.


![image](https://user-images.githubusercontent.com/40049149/186162184-c62c3f40-4240-417a-aee4-fc156965df80.png)


2. Jika sudah nanti akan masuk ke halaman seperti gambar dibawah. Disini kalian pilih saja di bagian __use ISO image__. Setelah itu masuk ke bagian __browser__ lalu cari lokasi __ISO ubuntu server__ yang sudah kalian download sebelumnya.


![image](https://user-images.githubusercontent.com/40049149/186162731-225e305c-130a-4444-8ffc-fa73a0d937af.png)


3. Lalu tahapan pilih Sistem opreasi yang akan di gunakan disini karana Ubuntu server makan pilih linux.


![image](https://user-images.githubusercontent.com/40049149/186162907-6e902fbe-bf46-4fb2-a540-36f659bdaab9.png)


4. Tahapan selanjutnya masukan nama yang diinginkan jikan ingin di rubah dan tempat penyimpanan sistem jika ingin di rubah juga.


![image](https://user-images.githubusercontent.com/40049149/186166852-c9511dd3-0260-46a9-b0bb-e521a72f8d85.png)


5. Setelah atur size disk yang ingin kalian gunakan. Disini sebagai contoh saya menggunakan 20GB. Disini ada 2 pilihan yaitu __Store Disk as a single file__ dan __Split virtual disk into multiple files__.

      Keterangan :

    - __Store Disk as a single file__ maksudnya adalah disk yang kalian buat itu nantinya akan langsung terbuat 20Gb. (ini tidak disarankan untuk pengguna yang memiliki hardisk yang berkapasitas kecil).
    - __Split virtual disk into multiple files__ maksudnya adalah disk yang kita pakai untuk virtual machine kita nantinya itu akan dibagi menjadi beberapa bagian. Jadi walaupun kita menggunakan disk berkapasitas 20Gb itu nanti tidak akan terpakai seluruhnya.


![image](https://user-images.githubusercontent.com/40049149/186168558-6bbc28ad-1433-4f24-8516-f7e9ab6b62de.png)


6. Sekarang kita akan meng-customisasi hardware untuk server kita, tekan saja di bagian __Customize Hardware__.


![image](https://user-images.githubusercontent.com/40049149/186168673-2762d611-cf1e-4e3e-8944-1a46ac1f2ea7.png)


7. Disini ada beberapa pilihan untuk kita melakukan customisasi seperti __Memory__, __Processors__ dan __Network adapter__.

      Keterangan:

    - __Memory__ berfungsi untuk penyimpanan data yang ingin kita gunakan untuk Virtual Machine yang ingin kita buat. Disini kita pilih gunakan saja defaultnya yaitu sebesar 4Gb tetapi misalkan kalian merasa kurang kalian boleh untuk menaikkannya sesuai keinginan kalian.
    - __Processors__ adalah salah satu komponen penting untuk Virtual Machine yang ingin kita bangun, serta berfungsi untuk memproses data dan mengontrol sistem yang ada pada Virtual Machine kita. Disini kita menggunakan defaultnya saja yaitu sebesar 2 core.
    - __Network adapter__ berfungsi untuk menghubungkan komputer ke jaringan. Untuk penjelasan lebih lanjut ada di poin berikutnya.


![image](https://user-images.githubusercontent.com/40049149/186170432-6bdc5178-ffc8-4c5d-bcc6-0fb70054475c.png)


8. Jika sudah selesai untuk meng-setting __memory__ dan __processor__, kalian bisa pergi ke bagian __Network Adapter__. Setelah itu ubah dari defaultnya yaitu __NAT__ menjadi __Bridge__.

      Keterangan:

  - kalau menggunakan __NAT__ nantinya server yang kita buat ini akan mendapatkan IP yang sudah di sediakan oleh Virtual Machine kita.
  - Kalau Menggunakan __Bridge__ nantinya server yang kita buat akan mendapatkan IP dari internet yang sedang kita gunakan.


![image](https://user-images.githubusercontent.com/40049149/186171498-3f2b3462-7219-4e4b-994b-3a49bbed0881.png)

   Jika sudah langsung klik saja __Close__.


9. Setelah nanti kalian akan di kembalikan ke halamannya sebelumnya dengan perubahan yang di seting, setelah itu tekan saja di bagian __Finish__.


![image](https://user-images.githubusercontent.com/40049149/186171852-3694604c-b4b6-48f5-ae1e-f5081ea7486c.png)
![image](https://user-images.githubusercontent.com/40049149/186172250-2a550167-bdc8-4c7d-a6b4-5cd7b63a4f24.png)

  Jika muncul seperti di gambar klik saja __Close__.


10. Klik __OK__ jika muncul notif berikut dan akan langsung di arahkan ke bagian installasi


![image](https://user-images.githubusercontent.com/40049149/186173167-92ec9798-74fb-40eb-91e3-3fdcf883f459.png)
![image](https://user-images.githubusercontent.com/40049149/186173363-012e7046-8e9a-4d8e-be21-28b3783f8b9f.png)


11. Tekan __Enter__.


![image](https://user-images.githubusercontent.com/40049149/186186358-2bd88581-7ca7-4fe5-989b-abe8dd627eb0.png)


12. Disini kalian tunggu saja sampai prosesnya selesai.


![image](https://user-images.githubusercontent.com/40049149/186173511-389e578a-3311-443b-a49f-8b0e2edd08c3.png)


13. Setelah itu pilih bahasa yang ingin digunakan __English__.


![image](https://user-images.githubusercontent.com/40049149/186173710-b5525f78-025c-4c9c-8ab3-cdb43b8261bd.png)


14. Proses ini bisa langsung kalian skip dengan klik __Done__.


![image](https://user-images.githubusercontent.com/40049149/186174033-7652aafd-4625-496d-8e7d-4fbb31c745c0.png)


15. Proses ini pilihan sudah bener ubuntu server klik __Done__.


![image](https://user-images.githubusercontent.com/40049149/186174164-a8c31518-0d16-42de-84a0-be0ed2cc3d3e.png)


16. Selanjutnya kita akan ubah konfigurasinya dari yang awalnya itu __DHCPv4__ menjadi __Static__.

    Keterangan:

- __DHCP (Dynamic Host Protocol Configuration)__ : Alamat IP yang dapat berubah-ubah pada perangkat yang tersambung setiap kali terhubung kembali pada jaringan tersebut (otomatis).
- __Static__ : Alamat IP tidak berubah-ubah dari yang telah diberikan oleh adminisitrator (setting manual)


![image](https://user-images.githubusercontent.com/40049149/186174246-451cb83b-a9c3-4141-943f-48b4ff07cfa3.png)


15. Pilih di bagian __ens33__, setelah itu pada bagia __IPv4 Method__ ubah dari yang awalnya __automatic__ menjadi __manual__. Setelah itu masukan detail IP pada form yang tersedia(kalian bisa masukkan saja IP yang sudah tertera di bagian DHCPv4). Jika sudah langsung tekan saja __Save__.

    Keterangan:

- __Subnet__ : Istilah teknologi Informasi yang membedakan Network ID dan Host ID atau sebagai penentu porsi Network ID dan Host ID pada deretan kode biner
- __Address__ : Alamat IP yang akan digunakan untuk Virtual Machine yang akan kalian buat. (kalian dapat mengisi bagian ini dengan IP yang sudah ada di bagian DHCP)
- __Gateway__ : Perangkat komputer yang berfungsi untuk mengkoneksikan sebuah Jaringan komputer terhadap satu jaringan komputer yang lain.
- __Name servers__ : Dibagian __Name servers__ ini kalian cukup memasukkan IP DNS dari google supaya dapat terhubung dengan browser.


![image](https://user-images.githubusercontent.com/40049149/186174367-71dd173e-8d18-47cd-883f-ba2e84f111b6.png)

![image](https://user-images.githubusercontent.com/40049149/186174455-4ad5d706-4792-4c71-9bfe-cfe082b6eac8.png)

![image](https://user-images.githubusercontent.com/40049149/186174545-6b5f6efc-cc95-4a2c-afe7-c3f96da76640.png)

![image](https://user-images.githubusercontent.com/40049149/186174737-d183a31c-574a-40b7-9e46-36d3481c0d93.png)

![image](https://user-images.githubusercontent.com/40049149/186174786-e32303a9-fc39-47c0-864a-a18729ef8986.png)


Lalu akan muncul notifikasi untuk mengkonfirmasi semua konfigurasi yang sudah kita buat. Jika sudah langsung klik saja Continue.


![image](https://user-images.githubusercontent.com/40049149/186174886-6912d8e3-6889-469f-ada0-76b1df5bd4e9.png)


Selanjutnya masukan informasi seperti nama, username, dan password untuk server yang kalian buat. Jika sudah klik saja Done.


![image](https://user-images.githubusercontent.com/40049149/186175188-c52d6978-f13f-4be1-ab38-3befd87568d9.png)


Ditahapan ini jangan lupa untuk checklist bagian Install OpenSSH server gunanya adalah untuk me-remote server yang kita buat.


![image](https://user-images.githubusercontent.com/40049149/186175598-a6f8a785-9a2c-4856-8051-de041cafa636.png)


Pada tahap selanjutnya skip dengan klik Continue.


![image](https://user-images.githubusercontent.com/40049149/186175691-8d94bea3-37e6-44d2-831a-d0cc5f215ee1.png)

![image](https://user-images.githubusercontent.com/40049149/186175758-3f27e544-ba16-45c0-8069-d435572f16e9.png)

