# Problem Statement
Pengguna perlu melihat daftar produk secara jelas (nama, harga, deskripsi) agar dapat memilih barang yang ingin dibeli. Tanpa daftar produk yang rapi, pengalaman belanja menjadi sulit dan membingungkan.


# Solution

## Functional Requirements
- User dapat melihat daftar produk yang ditampilkan lengkap dengan nama, deskripsi singkat, gambar, dan harga.
- User bisa menyortir produk sesuai dengan kebutuhannya, misalnya berdasarkan nama (A-Z/Z-A) atau harga (termurah-termahal)
- User bisa mengklik sebuah produk untuk melihat detailnya
- Sistem harus memungkinkan pengguna mengklik produk untuk melihat detail produk.

## UX/UI
- UI halaman inventory
![inventory][assets/inventory.png]
-Ui halaman detail produk
![detail product][assets/detail_product.png]


## Business Logic
- Core Rule :
  - Secara defult produk akan ditampilkan secara terurut berdasarkan abjad [A-Z]
  - Produk yang ditampilkan hanya produk yang tersedia
- Flowchart :
![inventory diagram][diagrams/inventory.png]
