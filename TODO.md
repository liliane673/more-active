# P3-Challenge-2 (Next.js Project)

## W2D1

### Setup Project: Tema Aplikasi

Silahkan setup project aplikasi kamu:

- [v] Pilih tema sesuai kesepakatan bersama  instructor, tuliskan dalam README github kamu
- [v] Membuat layout aplikasi sesuai tema yang dipilih
- [v] Membuat initial data/seeder sesuai struktur data yang ditentukan (Kalian bisa check `db.json` sebagai referensi atau bisa digunakan sebagai data awal)
  - [v] Halaman auth
    - [v] Register
    - [v] Login
  - [v] Halaman home
    - [v] Komponen Banner
    - [v] Komponen Detail info Ecommerce
    - [v] Komponen Featured Product (50-10 product) + “see-all”
  - [v] Halaman product
    - [v] Komponen List Product
    - [v] Komponen Search
    - [v] Komponen Pagination
    - [v] Komponen Add to wishlist
  - [v] Halaman detail product
    - [v] Komponen Add to wishlist
  - [v] Halaman Wishlist
    - [v] Komponen list Wishlist (bisa menggunakan card yang sama dengan halaman list product)
    - [v] Komponen Remove Wishlist

## W2D2

### NEXT.js Intro

- [v] Setup NEXT.js project yang menggunakan typescript
- [v] Convert halaman-halaman dan komponen-komponen yang dibuat sebelumnya menjadi  pages dan components pada NEXT.js:
  - [v] Halaman register: /register
  - [v] Halaman login: /login
  - [v] Halaman home: /
    - [v] Komponen Banner
    - [v] Komponen Detail info Ecommerce
    - [v] Komponen Featured Product (5-10 product) + “see-all”
  - [v] Halaman product: /products
    - [v] Komponen List Product
    - [v] Komponen Search
    - [v] Komponent Pagination
    - [v] Komponen Add to wishlist
  - [v] Halaman detail product: /products/:slug
    - [v] Komponen Add to wishlist
  - [v] Halaman wishlist: /wishlist
    - [v] Komponen List Wishlist (bisa menggunakan card yang sama dengan halaman list product)
    - [v] Komponen Remove Wishlist

> Catatan: Kamu bisa menambahkan halaman sesuai kebutuhan aplikasi kamu

### NEXT.js CSR & SSR

Implementasikan CSR dan SSR pada pada halaman-halaman dan komponen-komponen yang sudah dibuat dengan detail sebagai berikut:

- [v] Halaman register: /register
- [v] Halaman login: /login
- [v] Halaman home: / (SSR)
- [v] Halaman product: /products (CSR)
  - [v] Komponen List Product (CSR)
  - [v] Komponen Search (CSR)
  - [v] Komponen Pagination (CSR)
  - [v] Komponen Add to Wishlist (CSR)
- [v] Halaman detail product: /products/:slug (SSR)
  - [v] Komponen Add to Wishlist (CSR)
- [v] Halaman wishlist: /wishlist
  - [v] Komponen List Wishlist (CSR)
  - [v] Komponen Remove Wishlist (CSR)

> Catatan: Disini belum perlu melakukan fetching atau request data

## W2D3

### NEXT.js Route Handler

- [v] Install MongoDB database pada komputer kamu atau menggunakan MongoDB Atlas
- [v] Lakukan wiring dan validasi terhadap halaman-halaman dan komponen-komponen yang sudah dibuat.
  - [v] Halaman register: /register
    - [v] username:string (validation: required, unique)
    - [v] email:string  (validation: required, unique, email format)
    - [v] password:string  (validation: required, length min 5)
  - [v] Halaman login: /login
    - [v] email:string  (validation: required, email format)
    - [v] password:string  (validation: required)
  - [v] Halaman home: / (SSR)
    - [v] Halaman product: /products
    - [v] Fitur List Product
    - [v] Fitur Search
    - [v] Fitur Pagination
    - [v] Untuk menerapakan infinite scroll salah satu package yang bisa digunakan: react-infinite-scroll
  - [v] Fitur Add to Wishlist
    - [v] userId: ObjectId  (validation: required)
    - [v] productId: ObjectId  (validation: required)
  - [v] Halaman detail product: /products/:slug
    - [v] Fitur Add to Wishlist
      - [v] userId: ObjectId  (validation: required)
      - [v] productId: ObjectId  (validation: required)
  - [v] Halaman Wishlist
    - [v] Fitur List Wishlist
    - [v] Fitur Remove to Wishlist
      - [v] userId: ObjectId  (validation: required)
      - [v] productId: ObjectId  (validation: required)

### NEXT.js Auth

Implementasikan autentikasi pada aplikasi NEXT.js yang sudah dibuat dengan detail sebagai berikut:

- [ ] Hanya user yang sudah login yang bisa menambahkan wishlist produk
- [ ] Hanya user yang sudah login yang bisa menghapus wishlist produk

## W2D4

### Deploy Project

Lakukan deployment pada project ini agar aplikasi bisa dilihat oleh user lain

- [ ] Deploy client

## Day 5 - 6

### Buddy Session

- [ ] Silahkan cek tugas/aplikasi yang kamu buat ke instruktur/buddy untuk memastikan aplikasi yang dibuat sudah sesuai requirement.
