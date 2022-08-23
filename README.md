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


![image](https://user-images.githubusercontent.com/40049149/186171320-2770ff36-9c85-4b8d-a0f5-34f86bfe70bb.png)



