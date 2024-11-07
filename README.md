# PROJECT AKHIR-KELOMPOK 8-DASPRO
Sistem Informasi-A 2024

**Sistem Manajemen Hotel**

# Anggota Kelompok
1. Hendri Zaidan (2409116013)
2. Najmi Hafizh Mauludan Zain (2409116028)
3. Maifariza Aulia Dyas (2409116032)

# Menu Login atau Sign Up
![Screenshot (164)](https://github.com/user-attachments/assets/30df4070-5d49-42b0-9a7f-c556b166da81)

Pada awal program, akan ditampilkan menu utama dengan melakukan Login atau Sign Up terlebih dahulu.
1. Login (jika sudah punya akun)
   Ketika user telah memiliki akun atau telah memasukkan Username dan PIN yang disimpan dalam database maka user ketik 1.
   
   * Tampilan jika user salah menginputkan Username.
     
   ![Screenshot (181)](https://github.com/user-attachments/assets/0872ed26-68fb-44f8-abfd-a8ced5669e9f)

   User diminta menginputkan Username kembali
   
2. Sign Up (jika belum punya akun)
   Jika user belum memiliki akun maka user menginputkan 2.

# Jika Masuk dengan Username dan PIN "Admin" (Menu Fitur Admin)
![Screenshot (165)](https://github.com/user-attachments/assets/50bf684e-7a5e-4cf4-b99f-396047fac8a8)

Ketika user menginputkan Username "adminhotel" dan PIN "202921", maka user telah terdaftar sebagai admin. Setelah berhasil melakukan login, admin akan ditampilkan dengan menu fitur admin yang di menu fitur admin ini bisa melakukan proses CRUD (Create, Read, Update, Delete) data kamar, daftar reservasi, daftar akun, serta logout.

# Jika Masuk dengan Username Tamu (Menu Fitur Tamu)
![Screenshot (170)](https://github.com/user-attachments/assets/376f2528-7f2a-4161-99d4-8f072a664707)

Tamu menginputkan Username dan PIN yang sudah terdaftar dalam database. Seperti gambar diatas, user menginputkan Username "Mepa" dan PIN "15937" maka user telah berhasil melakukan login sebagai tamu. Selanjutnya tamu akan diarahkan ke menu fitur tamu, yang di menu fitur tamu ini bisa melakukan melihat daftar kamar, buat reservasi, daftar reservasi, cek saldo E Money, Top Up saldo, Update Akun, Cek informasi akun, serta log out dari menu fitur tamu. 

# Sign Up Akun (Daftar Akun Baru)
![Screenshot (167)](https://github.com/user-attachments/assets/0bd44bf7-8d0b-4dfe-bd3e-11049e45413b)

Bagi user yang belum memiliki akun untuk melakukan login, maka user bisa sign up dengan menginputkan nama panjang, username dan no. Hp.

* Tampilan output jika user menginputkan username yang telah terdaftar, dan diarahkan untuk sig up kembali. 
![Screenshot (166)](https://github.com/user-attachments/assets/e31934d1-7032-4780-922e-6cec26ff5c68)

Setelah proses sign up berhasil dilakukan, dengan otomatis akan menampilkan output seperti gambar dibawah dengan saldo E Money dan PIN yang telah disimpan dalam database.

![Screenshot (168)](https://github.com/user-attachments/assets/7c3e23e0-91e0-45df-b4cb-f33859780d0d)


# Jika memilih opsi 1 maka akan diarahkan ke Daftar Kamar
![Screenshot (170)](https://github.com/user-attachments/assets/17749cb0-1e85-4508-bfb1-8180a3b91a5c)

Pada opsi 1, tamu bisa melihat daftar kamar yang ada di hotel dengan keterangan Nomor kamar, Tipe, Fasilitas, serta Harga/Malam nya.

# Jika memilih opsi 2 maka akan diarahkan ke Buat Reservasi


# Jika memilih opsi 3 maka akan diarahkan ke Daftar Reservasi


# Jika memilih opsi 4 maka akan diarahkan ke Cek Saldo E Money
![Screenshot (174)](https://github.com/user-attachments/assets/3aa5b9eb-c767-4068-a3ce-29588803809d)

Pada opsi 4, tamu bisa mengecek terlebih dahulu nominal saldo di E Money nya.

# Jika memilih opsi 5 maka akan diarahkan ke Top Up Saldo
![Screenshot (175)](https://github.com/user-attachments/assets/73230227-4ec7-45a6-a063-314e2320ee09)

Saat ingin menambah saldo ke E Money, tamu diminta untuk memasukkan nominal untuk ditambahkan. Dan nominal harus lebih dari 0.

* Jika memasukkan nominal kurang dari 0
Akan menampilkan output bahwa jumlah top up harus lebih dari 0 dan setelah itu diminta memilih opsi 1-5 kembali.
![Screenshot (187)](https://github.com/user-attachments/assets/2155bc43-2136-4208-aa20-28adf39497ca)

* Ketik 4 jika ingin mengecek saldo E Money tamu setelah nominal tadi ditambahkan
  Nomor kamar sudah tidak ada dalam daftar kamar
![Screenshot (176)](https://github.com/user-attachments/assets/68001e60-f4f5-420b-ae0d-bed428be6798)


# Jika memilih opsi 6 maka akan diarahkan ke Update Akun


# Jika memilih opsi 7 maka akan diarahkan ke Cek Informasi Akun


# Jika memilih opsi 8 maka akan diarahkan ke Log Out
![Screenshot (189)](https://github.com/user-attachments/assets/1030ab3a-f98f-48eb-985e-3c4ca0c88185)

Pada opsi 8 ini tamu bisa melakukan Log Out dari program atau mulai kembali.

* Tampilan jika keluar dari program
  Jika memilih keluar dari program, maka menampilkan output seperti dibawah ini.
  
![Screenshot (187)](https://github.com/user-attachments/assets/1f526bcd-a11e-44c1-9ab7-3a8ba75be858)

* Tampilan jika mulai kembali
  Jika mulai kembali, maka kembali diminta untuk memasukkan Username dan PIN.

![Screenshot (186)](https://github.com/user-attachments/assets/93df42e8-9423-4c23-8510-db3652cd6194)

# Tampilan Mode Create (Tambah Kamar) Pada Admin


# Tampilan Mode Read pada Admin (Insert Fitur Sorting dan Searching)


# Tampilan Mode Sorting


# Tampilaan Mode Searching


# Tampilan Mode Update Kamar pada Admin


# Tampilan Mode Remove (Hapus Kamar) pada Admin
![Screenshot (182)](https://github.com/user-attachments/assets/333d1860-eef6-4025-a6c7-e79c599ce749)

Pada opsi ini, admin bisa menghapus kamar dari daftar kamar dengan memasukkan nomor kamar yang ingin dihapus.

![Screenshot (183)](https://github.com/user-attachments/assets/eee18b77-1b04-44a0-b138-905a90a0bee4)

Ketik 1 untuk melihat daftar kamar setelah nomor kamar tersebut dihapus.

# Tampilan Mode Log Out
![Screenshot (184)](https://github.com/user-attachments/assets/bad2ad02-edc6-4b3a-a566-ad82323c5d46)

Pada opsi 7 ini admin bisa keluar dari program atau mulai kembali

* Tampilan jika keluar dari program
  Jika memilih keluar dari program, maka menampilkan output seperti dibawah ini.
  
![Screenshot (185)](https://github.com/user-attachments/assets/68494ce7-4a46-45aa-be4e-c84f76930a66)

* Tampilan jika mulai kembali
  Jika mulai kembali, maka kembali diminta untuk memasukkan Username dan PIN.
![Screenshot (182)](https://github.com/user-attachments/assets/cc664e52-6279-4ae2-b622-bbdc7b478dff)
