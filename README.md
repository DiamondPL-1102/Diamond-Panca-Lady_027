Tugas Diamond Panca Lady_G1F022027
# Tugas Mata Kuliah PBO mengenai perulangan (Loops)
### 1. Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:
 pembahasan :

for i in range(1, 101):

// dimana kode ini digunakan untuk mengatur perulangan variabel i dari 1 hingga 100.

if i % 10 == 0:

// menggunakan if else untuk suatu perkondisian atau memeriksa variabel i adalah kelipatan 10 apakah benar atau salah.

    for _ in range(3):
        print("Diamond Panca Lady")
//kode diatas digunakan untuk mengulangi sebuah kode sebanyak 3x seperti untuk menghasilkan nama sebanyak 3x secara berurutan kebawah.

else:

    print(i)
    
//kode tersebut menjelaskan jika kondisi salah maka kode else akan dieksekusi. 

Berikut Screenshot saat code dijalankan :

<div align="center"><img src="https://github.com/DiamondPL-1102/Diamond-Panca-Lady_027/assets/149948656/1662ae45-0880-4664-a70b-4e7121848c9f" width="400"></div>

### 2. Buatlah program bebas, dengan menerapkan if else pada:
   
   a. For Loops
   
   b. While Loops

 pembahasan :

   ##### a. For Loops
  
    print("Program dengan menerapkan if else pada For Loops :")
   
     // perintah print ini digunakan untuk menampilkan teks yang sudah dibuat.
 
    for i in range(2, 15):
   
     // dimana kode ini digunakan untuk mengatur perulangan variabel i dari 2 hingga 15.

      if i % 2 == 0:
   
          print(f"{i} adalah bilangan genap.")
   
     // menggunakan if else untuk suatu perkondisian atau memeriksa variabel i adalah bilangan genap apakah benar atau salah dengan cara memeriksa apakah variabel i dibagi dengan 2 maka sisa bagi yaitu 0.
 
      else:
   
        print(f"{i} adalah bilangan ganjil.")
   
     // kode diatas menjelaskan jika sisa bagi tidak sama dengan 0 maka perintah else akan dieksekusi dan mengeluarkan output bilangan ganjil.

Berikut Screenshot saat code dijalankan :

<div align="center"><img src="https://github.com/DiamondPL-1102/Diamond-Panca-Lady_027/assets/149948656/e045d9c0-a64e-4551-9354-a29f418ab487" width="400"></div>

  ##### b. While Loops
    
    print("Program dengan menerapkan if else pada While Loops:")
    // perintah print ini digunakan untuk menampilkan teks yang sudah dibuat.
   
    i = 2
    // kode ini adalah dimana variabel i dengan nilai variabel 2.
 
    while i <= 15:
    // jika variabel i bernilai kurang dari atau sama dengan 15 maka kondisi perulangan akan benar.
 
    if i % 2 == 0:
        print(f"{i} adalah bilangan genap.")
    // menggunakan if else untuk suatu perkondisian atau memeriksa variabel i adalah bilangan genap apakah benar atau salah dengan cara memeriksa apakah variabel i dibagi dengan 2 maka sisa bagi yaitu 0.
 
    else:
        print(f"{i} adalah bilangan ganjil.")
    i += 3
    
    // kode diatas menjelaskan jika sisa bagi tidak sama dengan 0 maka perintah else akan dieksekusi dan mengeluarkan output bilangan ganjil. Dan nilai variabel i akan bertambah 3 setiap terjadi perulangan/loops hingga loops berhenti.

Berikut Screenshot saat code dijalankan :

<div align="center"><img src="https://github.com/DiamondPL-1102/Diamond-Panca-Lady_027/assets/149948656/6abace77-8067-4e5f-827c-61d7e6a65802" width="450"></div>

### 3. Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for
   
   pembahasan :

   list_NilaiUAS = ["70", "75", "80", "85", "90", "95", "100"]

   // list_NilaiUAS ini adalah nama variabel yang terdiri dari daftar nilai uas.

   print("Nilai UAS Kelas A SI:")

   // perintah print ini digunakan untuk menampilkan teks yang sudah dibuat seperti teks Nilai UAS Kelas A SI.

   for nilai in list_NilaiUAS:

      print(nilai)
   
   // kode diatas digunakan untuk mengulang setiap daftar nilai yang ada pada variabel list_NilaiUAS kemudian perintah print akan menampilkan seluruh nilai yang ada di variabel nilai

  Berikut Screenshot saat code dijalankan :
  
<div align="center"><img src="https://github.com/DiamondPL-1102/Diamond-Panca-Lady_027/assets/149948656/a36f924c-554e-48b2-8e79-b4afd7ed859c" width="450"></div>
