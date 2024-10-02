# Tugas-6-Konfigurasi-Server-SSH
### Nama : Anugrah Tegar Noverzha
### NIM : 09011282328029
### Kelas : SK3B
---

Langkah pertama yang dilakukan yaitu mengubah setingan settingan network virtual box ke Bridged Adapter. Caranya buka aplikasi virtual box, pergi ke setting kemudian pilih ke network, pada bagian Attached to nya ubah ke Bridged Adapter.

![Screenshot 2024-10-02 175826](https://github.com/user-attachments/assets/c398e90b-2837-4bd9-8665-e7937c8c2fde)

---

Selanjutnya gunakan command `ifconfig` untuk mengecek ip addres.

![Screenshot 2024-10-01 105135](https://github.com/user-attachments/assets/96e21c21-9dd2-4662-93d7-d82e7a857d1b)

 ip addres nya adalah 10.9.57.163 yang berada pada `enp03s` baris ke 2

 ---

 Selanjutnya gunakan command ssh untuk melakukan koneksi aman ke sistem lain melalui jaringan.
 
 ![Screenshot 2024-10-01 105224](https://github.com/user-attachments/assets/ff39b95b-6c1e-42db-b4e1-ee86cab584ae)

Jika ingin keluar server ketik `exit`
