# Praktikum 2 : CSS Dasar

### Darmawan Jodi Cahyo[311910457]
### TI.19.A.2

## Langkah 1
Membuat dokumen html.
![langkah 1](https://user-images.githubusercontent.com/56252129/113711937-b9a78800-970f-11eb-9c95-c7816d4c7e91.png)

## Langkah 2
Mendeklarasikan CSS Internal pada bagian `<head>` dokumen.
![langkah 2_mendeklarasikan css internal](https://user-images.githubusercontent.com/56252129/113712047-d80d8380-970f-11eb-8b23-48eb104932b6.png)

## Langkah 3
Menambahkan Inline CSS pada tag `<p>`.
![langkah 3_menambah inline css](https://user-images.githubusercontent.com/56252129/113712088-e491dc00-970f-11eb-95ef-da690f59f2fb.png)

## Langkah 4
Membuat CSS Eksternal dan menambahkan tag `<link>` pada bagian `<head>` dalam dokumen html untuk memuat dokumen css eksternal tersebut.
![langkah 4_membuat css eksternal](https://user-images.githubusercontent.com/56252129/113712141-f4a9bb80-970f-11eb-925e-ad56f8b655f7.png)

 Perubahan pada tampilan browser setelah di refresh.
![hasil langkah ke 4](https://user-images.githubusercontent.com/56252129/113712188-04290480-9710-11eb-838c-8c32c273f21b.png)

## Langkah 5
Menambah CSS Selector dengan menggunakan ID dan Class Selector pada dokumen css eksternal.
![langkah 5](https://user-images.githubusercontent.com/56252129/113712229-10ad5d00-9710-11eb-97f4-575ac9ee3779.png)

# Pertanyaan dan Tugas
### 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
![eksperimen](https://user-images.githubusercontent.com/56252129/113732233-9d154b00-9723-11eb-93f5-a37fe4baf710.png)

### 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
* Pendeklarasian CSS elemen h1 akan mengubah tampilan seluruh elemen yang memiliki tag h1, sedangkan #intro h1 hanya mengubah tampilan elemen h1 yang memiliki id #intro.

### 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
* Jika deklarasi ketiga jenis CSS berada pada elemen yang sama (contoh = ukuran font), maka deklarasi inline css lah yang akan ditampilkan oleh browser.

### 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
* Kedua deklarasi tersebut akan tampil, tapi deklarasi selector id lah yang akan ditampilkan jika terdapat deklarasi pada elemen yang sama.
![pertanyaan ke 4](https://user-images.githubusercontent.com/56252129/113732597-ea91b800-9723-11eb-9400-9b4c74704382.png)
