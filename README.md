# Membuat Program dan Flowchart dari program Tiket Bioskop dan juga Kalkulator

Tugas Pertemuan Ke 6

Nama: Rhendy Zhaky Alvian

Kelas: TI.24.A3

NIM: 312410397

# 1. Tiket Bioskop

Program tiket bioskop ini adalah program untuk menghitung harga Tiket Bioskop. Konsepnya adalah jika pengguna kartu member, maka pengguna akan mendapatkan diskon 20%

**Flowchart dari Program tersebut**

![1730115604877](https://github.com/user-attachments/assets/57c40ef0-a2c2-480d-8391-424d63d87db4)

**Program akan menanyakan status anggota**

![image](https://github.com/user-attachments/assets/aa088970-3408-4e5c-bdbc-fb9b658a2c62)

**Program akan menanyakan status anggota**

![image](https://github.com/user-attachments/assets/8b375165-d837-4a62-86f6-3e22eb2a9eff)

Jika pengguna memiliki kartu member, maka akan mendapatkan diskon 20%

**Output apabila input dimasukkan user adalah N atau tidak memiliki member**

![image](https://github.com/user-attachments/assets/e2fa475f-7cf1-47f6-b106-612a5b1fa8fa)

1. Perintah dibawah adalah untuk memampilkan judul program dan pilihan tiket yang tersedia.

print("=== Program Hitung Harga Tiket Bioskop ===")

print("1. Reguler (Rp50.000)")

print("2. VIP (Rp100.000)")

2. Input tipe tiket

tipe_tiket = input("Pilih tipe tiket (1/2): ")

Prorgam akan meminta input tipe tiket dari pengguna dan menyimpannya di variabel tipe_tiket

3. Status masukkan harga

status_member = input("Apakah anda memiliki kartu member? (y/n): ")

Program akan meminta input status anggota dari pengguna.

4. Harga tiket menggunakan operator ternary

harga_dasar = 50000 if tipe_tiket == "1" else 100000

Jika tipe_tiket="1" maka harga=50000, jika tidak maka harga=100000

5. Hitung diskon

diskon = 0.2 if status_member.lower() == "y" else 0

Jika status_member="y" maka diskon=0,2 (20%), jika tidak maka diskon=0

6. Menghitung total harga

total_harga = harga_dasar - (harga_dasar * diskon)

Menghitung total harga setelah diskon

7. Menampilkan output dari input yang dimasukkan pengguna

![image](https://github.com/user-attachments/assets/619b904a-6c62-462e-8423-724d04eda3a4)

# 2. Kalkulator Sederhana

Program ini adalah program Kalkulator sederhana yang berfungsi untuk menghitung dua angka sesuai dengan operasi hitung yang dipilih

**Flowchart dari Program Kalkulator sederhana**

![1730121882200](https://github.com/user-attachments/assets/072950f7-bb12-454d-a7b9-95bfa17e7964)

**Program akan meminta input angka dan Operator perhitungan**

![image](https://github.com/user-attachments/assets/de9c75bf-e8b2-42a1-980c-f7f226e2f119)

**Contoh apabila kita memilih Operasi hitung Penjumlahan**


![image](https://github.com/user-attachments/assets/8aa38613-01e8-41fe-b305-3e94a2e318da)


**Contoh apabila kita memilih Operasi hitung Pengurangan**

![image](https://github.com/user-attachments/assets/f83579b7-ecde-48c9-a0e2-bee9f6a9043c)

**Contoh apabila kita memilih Operasi hitung Perkalian**






