## 1.1 Latar Belakang

Disini saya membuat sebuah aplikasi web yang dmn di dalam nya CV dan skil pribadi saya sepeti Designer, Web Developer, Vidiographer, Photographer, Pendaki untuk menawarkan jasa sesuai keahlian saya.
Karena banyaknya orang yang mempunyai sebuah keahlian yang tidak bisa di kembangkan utnuk menjadi sebuah pekerjaan dan mendapatkan penghasilan. Maka dari itu saya membuat sebuah aplikasi untuk memudahkan mengakses job freelance.

## 1.2. Deksripsi Teknologi Informasi

aplikasi web untuk menawarkan jasa sesuai skill yang tercantum di CV, lalu aplikasi web tersebut menggunakan data bes bootstrap.min.css bahasa index.html,css

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
   erDiagram
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER {
        string name
        string custNumber
        string sector
    }
    ORDER ||--|{ LINE-ITEM : contains
    ORDER {
        int orderNumber
        string deliveryAddress
    }
    LINE-ITEM {
        string productCode
        int quantity
        float pricePerUnit
    }
   
## 4. Arsitektur Sistem

Masih pake mermaid.js juga bisa lihat flowchart di [https://mermaid.js.org/syntax/flowchart.html](https://mermaid.js.org/syntax/flowchart.html)




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
## 5. Teknologi, Library, dan Framework

bla bla bla

## 6. Desain User Experience dan User Interface

Bisa load image 
![Contoh](https://fastly.picsum.photos/id/318/536/354.jpg?hmac=Ixy-wle80nudIR_cmnF1iY2y6rMUH7_9sk-BP1fTpM8)

## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?


