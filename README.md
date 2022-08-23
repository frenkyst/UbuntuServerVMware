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


17. Pilih di bagian __ens33__, setelah itu pada bagia __IPv4 Method__ ubah dari yang awalnya __automatic__ menjadi __manual__. Setelah itu masukan detail IP pada form yang tersedia(kalian bisa masukkan saja IP yang sudah tertera di bagian DHCPv4). Jika sudah langsung tekan saja __Save__.

    Keterangan:

- __Subnet__ : Istilah teknologi Informasi yang membedakan Network ID dan Host ID atau sebagai penentu porsi Network ID dan Host ID pada deretan kode biner
- __Address__ : Alamat IP yang akan digunakan untuk Virtual Machine yang akan kalian buat. (kalian dapat mengisi bagian ini dengan IP yang sudah ada di bagian DHCP)
- __Gateway__ : Perangkat komputer yang berfungsi untuk mengkoneksikan sebuah Jaringan komputer terhadap satu jaringan komputer yang lain.
- __Name servers__ : Dibagian __Name servers__ ini kalian cukup memasukkan IP DNS dari google supaya dapat terhubung dengan browser.

![image](https://user-images.githubusercontent.com/40049149/186194609-b6c601c8-b92d-4587-b2c4-45ad46628501.png)

![image](https://user-images.githubusercontent.com/40049149/186194661-be9df4d7-2d51-4bf5-9f90-6e3e6d665827.png)

![image](https://user-images.githubusercontent.com/40049149/186194885-5b065d78-e6f3-47b7-b0fb-a8ec25fb934d.png)


18. Jika konfigurasi sudah selesai maka akan ada perubahan di bagian __DHCPv4__ tadi menjadi __static__.


![image](https://user-images.githubusercontent.com/40049149/186195038-57feb6f7-7c11-47fc-8968-fd772c741e6e.png)


19. Pada tahap selanjutnya kalian bisa skip dengan klik __Done__.


![image](https://user-images.githubusercontent.com/40049149/186195404-98249148-21c6-4b89-8caf-8a61785ec7a4.png)


20. Pada tahap selanjutnya kalian bisa skip dengan klik __Done__.


![image](https://user-images.githubusercontent.com/40049149/186195452-4c2200d5-df95-4760-97b7-a1b518c5daf9.png)


21. Disini kita dapat memilih bagian __Custom storage layout__. Kenapa kita memilih Custom storage layout karena kita akan membuat 2 buah partisi, jika sudah kalian pilih setelah itu langsung saja klik __Done__.


![image](https://user-images.githubusercontent.com/40049149/186195591-d372386a-28dc-4b7e-87e9-257824d38962.png)


22. Selanjutnya disini kita akan membuat 2 buah partisi untuk __root__ dan __swap__. Langsung pilih saja di bagian __free space__ lalu pilih di bagian __Add GPT Partition__. Untuk kapasitasnya kalian bisa samakan saja dengan gambar dibawah (kecuali untuk swap, kalian bisa setting semau kalian apabila merasa kurang).

    Keterangan :

- __root__ adalah tempat dimana sistem kita itu ter-install.
- __swap__ adalah suatu memory cadangan yang akan digunakan untuk server kita apabila memory utama sudah penuh.

![image](https://user-images.githubusercontent.com/40049149/186196208-a567e277-cf56-4109-8f9d-f5bf464abb69.png)

![image](https://user-images.githubusercontent.com/40049149/186196390-0d1daec9-e5c4-4b4e-81d4-15550242befa.png)

![image](https://user-images.githubusercontent.com/40049149/186196666-2f9138ea-8533-44b5-84f7-333415df9281.png)


23. Jika sudah disini kita sudah berhasil membuat 2 partisi untuk __root__ dan __swap__. Jika sudah langsung saja klik __Done__.


![image](https://user-images.githubusercontent.com/40049149/186196727-0bbe52cb-5020-45a2-9096-613616b3d278.png)


24. Lalu akan muncul notifikasi untuk mengkonfirmasi semua konfigurasi yang sudah kita buat. Jika sudah langsung klik saja __Continue__.


![image](https://user-images.githubusercontent.com/40049149/186206538-6134a5bb-9e4f-425f-be1d-5a877a4b60e6.png)


25. Selanjutnya masukan informasi seperti __nama, username__, dan __password__ untuk server yang kalian buat. Jika sudah klik saja __Done__. Lalu akan muncul notifikasi untuk mengkonfirmasi semua konfigurasi yang sudah kita buat. Jika sudah langsung klik saja __Continue__.


![image](https://user-images.githubusercontent.com/40049149/186197914-a609a464-0a93-4c8a-92e1-39cd75df591c.png)


26. Ditahapan ini jangan lupa untuk checklist bagian __Install OpenSSH server__ gunanya adalah untuk me-remote server yang kita buat.


![image](https://user-images.githubusercontent.com/40049149/186198065-7f5a32d2-5133-4c72-8f38-561d9b1cde56.png)


27. Pada tahap selanjutnya skip dengan klik __Continue__.


![image](https://user-images.githubusercontent.com/40049149/186198193-fe564d34-4615-4837-bc45-9043cc3a41cf.png)


28. Kita sudah selesai untuk tahapan instalasinya. Tunggu saja proses instalasi sampai selesai jika sudah selesai langsung saja klik __Reboot Now__.





![image](https://user-images.githubusercontent.com/40049149/186203296-118df5a1-eea3-4731-a9a2-ad6322d11426.png)

