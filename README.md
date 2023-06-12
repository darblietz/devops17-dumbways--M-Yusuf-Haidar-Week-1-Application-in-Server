# Task Application in Server

## 1. Perbandingan antara Monolith & Microserves.

- Arsitektur monolitik menempatkan semua komponen aplikasi dalam satu proyek atau satu kontainer. Sedangkan, Arsitektur microservices, memisahkan aplikasi menjadi beberapa komponen yang independen yang dapat di-deploy dan diubah tanpa mempengaruhi komponen lainnya. 

Masing-masing mempunyai kelebihan dan kekurangannya :
#### Kelebihan
1. Arsitektur Monolitik, Aplikasinya akan lebih sederhana dan mudah diatur, serta memudahkan proses pengembangan dan deployment.
2. Arsitektur Microserves, Para developer untuk mengelola dan mem-deploy setiap microservice secara independen, serta mengelola skala dan performa setiap microservice dengan lebih baik.

#### Kekurangan
1. Arsitektur Monolitik, Karena semua komponen aplikasi menyatu dalam satu unit yang sederhana, apabila ada masalah maka akan menyebabkan skalabilitas dan fleksibilitas dalam jangka panjang.
2. Arsitektur Microserves, Karena aplikasi dibagi menjadi beberapa microservices yang independen, ini dapat menjadi lebih kompleks dan rumit untuk dikembangkan dan di-deploy dibandingkan arsitektur monolitik.

## 2. Deploy Aplikasi wayshub-frontend (NodeJS)

1. Ketik command ``$ git clone https://github.com/dumbwaysdev/wayshub-frontend``. Fungsinya membuat salinan untuk repository lokal :<br/><br/>![Wayshub NodeJS 1](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Application-in-Server/assets/98991080/54460008-b39c-4404-aa8f-56acd6419b63)<br/><br/>
2. Selanjutnya, ketik ``$ npm install``. Fungsinya untuk melakukan installasi tools yang berada di package.json, agar aplikasi bisa berjalan :<br/><br/>![Wayshub NodeJS 2](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Application-in-Server/assets/98991080/26f5f3f9-a0be-493b-b7a5-ee8174a1bbd2)<br/><br/>
3. Setelah install, lakukan menjalankan aplikasinya dengan ``$ npm start`` :<br/><br/>![Wayshub NodeJS 3](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Application-in-Server/assets/98991080/1bcdf447-1571-4810-be23-f02d9594ce63)<br/><br/>
4. Tunggu penginstallan selesai :<br/><br/>![Wayshub NodeJS 4](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Application-in-Server/assets/98991080/58f7f35e-0c28-4779-b210-79154cffcd9b)<br/><br/>
5. Setelah tampil gambar diatas, Silahkan lakukan percobaan dibrowser di Link dengan ``IP anda:3000``. Apabila muncul webnya, maka berhasil.  :<br/><br/>![Wayshub NodeJS 5](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Application-in-Server/assets/98991080/da5d2ab8-6549-4789-96a4-f2e3a68590c5)


## 3. Deploy Golang & Python dengan menampilkan nama masing-masing.

- Golang :<br/><br/>

  1. Pertama, install engine-nya terlebih dahulu, <br/><br/>![1](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/0f4c21b6-8537-4f44-9d77-34015c47db24)<br/><br/>
  2. dan ketik ``rm -rf /usr/local/go && tar -C /usr/local -xzf go1.16.5.linux-amd64.tar.gz && exit``<br/><br/>![2](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/f005e169-774b-4eda-9ff5-4b0347b04d74)<br/><br/>
  3. Berikutnya ketik ``$ sudo nano .bashrc``<br/><br/>![3](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/73805b83-05b1-488b-930b-f2faa5eb9a37)<br/><br/>
  4. Dan lakukan ketik atau Copy di bagian akhir paling bawah export ``PATH=$PATH:/usr/local/go/bin`` sete;ah itu Exit<br/><br/>![4](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/7ed7b67d-2099-4b80-8a16-8bb4e610a715)<br/><br/>
  5. Lakukan verifikasi go dengan cara ``$ go version``.<br/><br/>![5](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/0ee3abc3-c1ba-4322-be58-146fe14b2fd3)<br/><br/>
  6. Berikutnya membuat aplikasi sederhana menggunakan Go. Membuat file terlebih dahulu dengan commandn ``$ nano index.go``.<br/><br/>![6](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/f69a632b-f223-4c71-a33f-56495423519c)<br/><br/>
  7.  Setelah itu masukan script beriku,<br/>
      ``package main

      import "fmt"

      func main() {
      fmt.Println("Hello World!")
      }``<br/><br/>![7](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/58f40df7-1451-408e-a34e-e04434353876)
  8. Sekarang jalankan Aplikasi dengan perintah berikut ``$ go run index.go``<br/><br/>![8](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Linux-Shell/assets/98991080/7bb33ef6-35ec-49c8-9369-628c679c010f) 














