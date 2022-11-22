# NAMA : TIARA PUTRI
# NIM : 312210064
# KELAS : TI.22.A1

**Latihan**

Buat sebuah list sebanyak 5 elemen dengan nilai bebas

**Akses list :**
- Tampilkan elemen ke 3
- Ambil nilai elemen ke 2 sampai elemen ke 4
- Ambil elemen terakhir

**Ubah elemen list :**
- Ubah elemen ke 4 dengan nilai lainnya
- Ubah elemen ke 4 sampai dengan elemen terakhir

**Tambah elemen list :**
- Ambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B)
- Tambah list B dengan nilai string
- Tambah list B dengan 3 nilai
- Gabungkan list B dengan list A

 # Latihan
        
        print("Nama : Tiara Putr")
        print("NIM  : 312210064")

        print("Membuat List sebanyak 5 elemen dengan nilai bebas")
        # akses list
        a = [20, 40, 50, 60, 100]
        print(a) #Menampilkan semua elemen
        print(a[2]) #Menampilkan elemen ke 3
        print(a[1:3]) #Menampilkan elemen ke 2 sampai dengan ke 4
        print(a[4]) #Menampilkan elemen terakhir

        print("------------------------------------------")
        # ubah elemen list
        a[3] = 80 # Mengubah elemen ke 4 dengan nilai lainnya
        print(a[3]) # Menampilkan elemen ke 4 yang sudah diubah nilainya
        a[3:4] = 80, 90 # Mengubah elemen ke 4 sampai dengan elemen terakhir
        print(a[3:5]) # menampilkan elemen ke 4 sampai dengan elemen terakhir

        print("------------------------------------------")
        # tambah elemen list
        b = a[0:2] # Mengambil 2 bagian dari list pertama (a) dan jadikan list kedua (b)
        print(b)
        b.append(45) # Menambah list dengan nilai string
        print(b)
        b.extend([85, 90, 95]) # Menambah list b dengan 3 nilai
        print(b)
        c = a+b # Menggabungkan list b dengan list a
        print(c)
        
![2022-11-22 (2)](https://user-images.githubusercontent.com/115775237/203306993-2dd063c7-ad02-48c5-bfd2-f27f92bdfa31.png)

**Hasil run**

![2022-11-22 (3)](https://user-images.githubusercontent.com/115775237/203307215-9565b268-0599-4cb1-9312-6e8cd9d9c2b9.png)

#**Tugas Praktikum**

    Buat program sederhana untuk menambahkan data kedalam sebuah
    list dengan rincian sebagai berikut:
      • Progam meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)
      • Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban t (Tidak), maka program akan menampilkan daftar datanya. 
      • Nilai Akhir diambil dari perhitungan komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
      • Buat flowchart dan penjelasan programnya

![2022-11-20 (1)](https://user-images.githubusercontent.com/115775237/202905224-f749f1e7-caf8-42c8-8bf4-08bf3ae05f58.png)

![2022-11-20 (2)](https://user-images.githubusercontent.com/115775237/202905253-7b799096-b0c3-41c7-a1de-ae37a2fb814d.png)

![2022-11-20 (3)](https://user-images.githubusercontent.com/115775237/202905273-8aafb8b5-dab8-495b-b77b-101fbd380278.png)

**Flowchart**

![2022-11-21 (2)](https://user-images.githubusercontent.com/115775237/203051918-1d26ae86-266d-4bd0-a5f1-e42e414375e4.png)

**Penjelasan**

1. Buatlah list berupa Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS.
2. Lalu inputlah Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS.
3. Lalu mencari nilai akhir dengan perhitungan nilai tugas 30%, nilai uts 35% dan uas 35% , dengan perintah float
4. Gunakan perintah append pada Nama, NIM, Nilai tugas, Nilai UTS, Nilai UAS untuk menambahkan 1 item ke elemen terakhir.
5. Jika ingin menambah list data ketik "ya" dan jika tidak ingin menambahkan list data ketik "tidak". Dengan perintah while jawab =="ya" dan if jawab =="tidak". Jawab input("Tambah data (ya/tidak)").
6. Gunakanlah perulangan for, dengan perintah for i in range(len(Nama)):. Fungsi "len" ialah untuk mengembalikan panjang (jumlah anggota) dari suatu objek.
7. Lalu cetak dengan perintah print
8. Selesai
