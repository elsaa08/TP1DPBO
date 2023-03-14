# TP1DPBO
## Janji 
Saya [Elsa Nabiilah] [2108805] mengerjakan Tugas Praktikum 1 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.
## deskripsi tugas
Berdasarkan karangan tersebut, ambil kata kunci yang sekiranya
penting, kemudian buatlah desain, objek, serta relasinya
menggunakan OOP!
Catatan
● Diperbolehkan menambah atribut / properti baru.
● Buatlah Class Diagram dari desain yang telah dirancang, serta
berikan penjelasannya!
● Pilihlah satu bahasa yang disukai / dikuasai, kecuali PHP.
● Diperbolehkan menggunakan konsep yang belum diajarkan,
seperti polimorfisme (overload – override), kelas abstrak,
interface, dan sebagainya.

## Desain Program

![Diagram UML TP1](https://user-images.githubusercontent.com/101001227/225013660-8b6cc836-5ca8-48a2-9890-320f15340c91.jpg)


dalan program ini, terdiri dari beberapa struktur relasi antar class antara lain :
1. class Human has a class barang : class Human memiliki Class barang yang berisi list nama barang, setiap Human akan memiliki barang di setiap objeknya dan bisa berbeda-beda
2. class Human inheritance class Mahasiswa, class Dosen : karena Mahasiswa dan Dosen merupakan objek yang sama, maka keduanya sama-sama berada di level yang sama dan dapat memakai atribut yang ada pada class Human termasuk class Barang yang dapat berbeda juga di class Mahasiswa atau class Dosen
3. class Mahasiswa has a class Dosen : pada objek mahasiswa membutuhkan identitas dosen berupa nama sebagai dosen pembimbing permahasiswa dan bisa berbeda
4. class mahasiswa has a kegiatan_mhs : pada setiap objek pada class Mahasiswa akan memiliki kegiatan antara lain BEM, klub, dan Asistem Dosen, maka dari itu class mahasiswa dihubungkan dengan class kegiatan_mhs
5. class kegiatan_mhs has a class Tugas : pada desain ini class Tugas ddigunakan untuk menyimpan dan memanggil list tugas untuk dijadikan daftar tugas pada kegiatan mahasiswa yang menjadi Asisten Dosen
6. class Tugas: class ini menampung list tugas-tugas yang dikerjakan oleh dosen, karena asisten dosen juga merupakan bagiand dari dosen dan hampir memiliki tugas yang sama, oleh karena ini kedua class tersebut saling berhubungan dengan class Tugas
7. class Dosen has a class Tugas: untuk menyimpan list tugas-tugas dosen yang bisa dibagi dengan class kegiatan_mhs

## Alur Program
Contoh alur program kegiatan Mahasiswa

🍎 hardcode kegiatan BEM dan Klub 

<img width="289" alt="image" src="https://user-images.githubusercontent.com/101001227/225011481-1db5a9ad-9575-491e-ba9a-cb437d071dba.png">

 - hardcode class Tugas untuk mendapatkan tugas dosen dan tugas asdos
 <img width="246" alt="image" src="https://user-images.githubusercontent.com/101001227/225012207-b52db6e4-002c-4dc7-a945-60449dc2a595.png">
 
🍎 masukan pada parameter class mahasiswa sesuai dengan yang dibutuhkannya

<img width="382" alt="image" src="https://user-images.githubusercontent.com/101001227/225011682-7609ba1d-8004-40e7-b7e9-09a838505979.png">


🍎 proses print

<img width="364" alt="image" src="https://user-images.githubusercontent.com/101001227/225011874-9a0ff917-80cb-4dd3-97b6-8c7e5ceed424.png">

### alur program yang lain memiliki struktur hampir sama dengan contoh diatas

## Dokumentasi

<img width="299" alt="(1)" src="https://user-images.githubusercontent.com/101001227/225013170-8c50f15f-8123-4ec5-bd6d-d5f02bc30485.png">

<img width="338" alt="(2) getsbi" src="https://user-images.githubusercontent.com/101001227/225013261-893b4960-88af-4df7-82f4-58a9180fae8c.png">

<img width="311" alt="(3) Angga" src="https://user-images.githubusercontent.com/101001227/225013298-d66e79ac-2911-4508-8caf-eaaa19170a8e.png">

<img width="350" alt="(4) mila" src="https://user-images.githubusercontent.com/101001227/225013335-8d401aad-b4f7-429f-8245-ad2c3a1289a2.png">

<img width="352" alt="(5) Resyad" src="https://user-images.githubusercontent.com/101001227/225013377-a5472697-2f99-4243-8c72-9bdd01ec0c76.png">

<img width="418" alt="(6) dosen part 1" src="https://user-images.githubusercontent.com/101001227/225013435-34190803-3bbc-4651-8c71-1bf2f66de135.png">

<img width="337" alt="(7) dosen part2" src="https://user-images.githubusercontent.com/101001227/225013468-b98b7a5e-80f7-4c7c-8a03-6381f29c78e0.png">


