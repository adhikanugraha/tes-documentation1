# Problem Statement
User membutuhkan ringkasan final pesanan sebelum melakukan pembayaran untuk memastikan detail belanja sudah benar. Tanpa fitur ini, user bisa salah jumlah, salah alamat, atau salah metode pembayaran, yang dapat menyebabkan ketidaknyamanan, pembatalan pesanan, bahkan kerugian.

# Solution

## Functional Requirements
- User bisa melihat ringkasan semua produk yang akan dibeli beserta jumlah, harga, dan total akhir.
- User bisa memastikan alamat pengiriman dan metode pembayaran sudah benar sebelum melanjutkan.
- User bisa mengonfirmasi pesanan dengan menekan tombol finish.
- User bisa kembali untuk mengubah isi keranjang atau informasi checkout jika ada yang salah.



## UX/UI
- UI checkout overview
![checkout overview][asset/checkout_overview.png]


## Business Logic
Core rule :
- sistem menampilkan payment information
- Sistem menampilkan shiping information
- Sistem menampilkan harga total yang sudah termasuk biaya pajak.
Flowchart :
![checkout overview diagram][diagrams/checkoutoverview.png]


