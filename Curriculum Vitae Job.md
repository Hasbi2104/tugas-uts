## 1.1 Latar Belakang

Freelance adalah istilah freelance online, sebenarnya ini adalah pekerjaan yang dilakukan secara sambilan atau lepas tanpa terikat dengan perusahaan mana pun.

4 Alasan Kenapa Freelancer Jadi Pekerjaan yang Diburu
Saat ini banyak sekali jenis pekerjaan yang bisa dilakukan, salah satunya dengan menjadi freelancer. Pekerja lepas yang tidak terikat dengan aturan waktu dan tempat tertentu seperti ini sedang banyak diminati akhir-akhir ini . Karena dianggap sangat mudah dan juga tidak terikat dengan suatu perusahaan membuat banyak orang jadi tergiur untuk menekuninya.
Masih ada alasan lain mengapa seseorang lebih memilih jadi freelancer daripada bekerja langsung ke kantor atau tempat tertentu, beberapa di antaranya benefit yang freelancer dapati sebagai berikut.
1. Penghasilan Sesuai dengan Pekerjaan
2. Waktu Kerjanya Fleksibel
3. Bisa Dikerjakan di Mana pun
4. Tak Harus Bertemu dengan Banyak Orang
   
adapun Keuntungan pekerjaan freelance meliputi fleksibilitas yang tinggi dalam memilih proyek, jadwal kerja, dan lokasi kerja. Freelancer dapat bekerja dari rumah, kafe, atau di mana saja yang mereka pilih. Mereka memiliki kontrol penuh atas karier mereka dan dapat menentukan sendiri berapa banyak proyek yang mereka ambil.

Disini saya membuat sebuah aplikasi berbasis web yang dmn di dalam nya CV dan skil pribadi saya sepeti Designer, Web Developer, Vidiographer, Photographer, Pendaki untuk menawarkan jasa sesuai keahlian saya.
Karena banyaknya orang yang mempunyai sebuah keahlian yang tidak bisa di kembangkan utnuk menjadi sebuah pekerjaan dan mendapatkan penghasilan. Maka dari itu saya membuat sebuah aplikasi untuk memudahkan mengakses job freelance.

## 1.2. Deksripsi Teknologi Informasi
maka dari itu saya membuat aplikasi berbasis web untuk menawarkan jasa pibadi saya sesuai skill yang tercantum di CV, yang dimana aplikasi itu dapat memudahkan dalam hal pekerjaan sesseorang dengan menggunakan sebuah aplikasi tersebut, aplikasi itu juga ada fithur dimana orang orang bisa melihat sill dan kemamupuan kita sebagai seorang freelancer agar si customer bisa tertarik dari hasil skil dan portofolio yang kita upload sebagai freelancer adapun ketika costumer minat hasil dari karya si freelancer, costumer bisa menghubungi kontak yang sudah tercantum di aplikasi berbasis web tersebut.




## 1.3. Branding

Pada tahap ini kita mengeksplorasi branding dari sistem yang dibuat. Branding meliputi:

Merk: CVJOB
Tagline:job freelance mudah dan menyenangkan karena sesuai hobi masing masing
Campaign: bagaimana membuat aplikasi ini untuk memudahkan orang lain menyalurkan hobi,skill nya agar bermanfaat untuk orang lain yang membutuhkan dan dapat bertanggung jawab atas pekerjaanya
Target user:
Seorang yang senang freelance job agar tidak jenuh
Seorang yang senang mengeksplorasi inspirasi dan informasi baru
Seorang yang ingin atau sudah memiliki sikap bertanggung jawab
Seorang yang ingin hobi atau skillnya dapat bermanfaat bagi orang lain dan berbuah hasil
User experience theme:
Mudah
Sederhana
simple
Warna: ala ala blue ang light 
Inspirasi desain:
! [gamabr] (![website-CV-2](https://github.com/Hasbi2104/tugas-uts/assets/144440884/c3b92318-b8a5-4577-b2a3-0ac497cee17e)

## 2. User Story

Sebagai | Saya ingin bisa| Sehingga | prioritas 
---|---|---|---
pengguna | menawarkan jasa pribadi| orang lain dapat terinspirasi | ⭐⭐⭐⭐⭐
pengguna | Melihat CV saya dan melihat skill saya | orang lain dapat percaya atas jasa kita | ⭐⭐⭐⭐⭐
pengguna | mengirim pesan untuk memesan jasanya | memudahkan memesan job dengan mudah dan tidak sulit | ⭐⭐⭐⭐⭐
Pengguna | Membalas pesan customer ketika sedang memesan | customer dan pembeli dapat saling konfirmasi | ⭐⭐⭐⭐⭐
## 3. Struktur Data
Cara membuat aneka macam bentuk grafik menggunakan mermaid.js bisa lihat di [https://mermaid.js.org/syntax/entityRelationshipDiagram.html](https://mermaid.js.org/syntax/entityRelationshipDiagram.html) 
erDiagram
  


  
```mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER {
        string name_lengkap
        string custNumber
        string sector
    }
    ORDER ||--|{ PENGGUNA : contains
    ORDER {
        int orderNumber
        string email
        string kontak
    }
    PENGGUNA {
        string productCode
        int quantity
        float pricePerUnit
    }
```
## 4. Arsitektur Sistem

Masih pake mermaid.js juga bisa lihat flowchart di [https://mermaid.js.org/syntax/flowchart.html](https://mermaid.js.org/syntax/flowchart.html)



```mermaid
%%{init: {"flowchart": {"htmlLabels": false}} }%%
flowchart LR
subgraph "One"
  a("`The **cat**
  in the hat`") -- "edge label" --> b{{"`The **dog** in the hog`"}}
end
subgraph "`**Two**`"
  c("`The **cat**
  in the hat`") -- "`Bold **edge label**`" --> d("The dog in the hog")
end
```
## 5. Teknologi, Library, dan Framework

bla bla bla

## 6. Desain User Experience dan User Interface

![poto] (![08e2ac26-ef23-46b0-b3ab-17a1170b53c8](https://github.com/Hasbi2104/tugas-uts/assets/144440884/5c40af08-7e53-44ff-bdfb-817316fae4a5)
![poto] (![d19b6040-c368-4892-9d5d-8be54e612682](https://github.com/Hasbi2104/tugas-uts/assets/144440884/5e1b874c-cd27-4850-8c6a-672da1881ac3)
![poto] (![46509a6d-573d-41c2-9b5b-5378ea7bcd55](https://github.com/Hasbi2104/tugas-uts/assets/144440884/82c343cb-5b33-4b07-b53d-a736adbeb3cf)



## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?


