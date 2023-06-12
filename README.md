# Task Application in Server

# 1. Perbandingan antara Monolith & Microserves.

- Arsitektur monolitik menempatkan semua komponen aplikasi dalam satu proyek atau satu kontainer. Sedangkan, Arsitektur microservices, memisahkan aplikasi menjadi beberapa komponen yang independen yang dapat di-deploy dan diubah tanpa mempengaruhi komponen lainnya. 

Masing-masing mempunyai kelebihan dan kekurangannya :
#### Kelebihan
1. Arsitektur Monolitik, Aplikasinya akan lebih sederhana dan mudah diatur, serta memudahkan proses pengembangan dan deployment.
2. Arsitektur Microserves, Para developer untuk mengelola dan mem-deploy setiap microservice secara independen, serta mengelola skala dan performa setiap microservice dengan lebih baik.

#### Kekurangan
1. Arsitektur Monolitik, Karena semua komponen aplikasi menyatu dalam satu unit yang sederhana, apabila ada masalah maka akan menyebabkan skalabilitas dan fleksibilitas dalam jangka panjang.
2. Arsitektur Microserves, Karena aplikasi dibagi menjadi beberapa microservices yang independen, ini dapat menjadi lebih kompleks dan rumit untuk dikembangkan dan di-deploy dibandingkan arsitektur monolitik.

# 2. Deploy Aplikasi wayshub-frontend (NodeJS)

1. Ketik command ``$ git clone https://github.com/dumbwaysdev/wayshub-frontend``. Fungsinya membuat salinan untuk repository lokal :<br/><br/>![Wayshub NodeJS 1](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Application-in-Server/assets/98991080/54460008-b39c-4404-aa8f-56acd6419b63)<br/><br/>
2. Selanjutnya, ketik ``$ npm install``. Fungsinya untuk melakukan installasi tools yang berada di package.json, agar aplikasi bisa berjalan :<br/><br/>![Wayshub NodeJS 2](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Application-in-Server/assets/98991080/26f5f3f9-a0be-493b-b7a5-ee8174a1bbd2)<br/><br/>
3. Setelah install, lakukan menjalankan aplikasinya dengan ``$ npm start`` :<br/><br/>![Wayshub NodeJS 3](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Application-in-Server/assets/98991080/1bcdf447-1571-4810-be23-f02d9594ce63)<br/><br/>
4. Tunggu penginstallan selesai :<br/><br/>![Wayshub NodeJS 4](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Application-in-Server/assets/98991080/58f7f35e-0c28-4779-b210-79154cffcd9b)<br/><br/>
5. Setelah tampil gambar diatas, Silahkan lakukan percobaan dibrowser di Link dengan ``IP anda:3000``. Apabila muncul webnya, maka berhasil.  :<br/><br/>![Wayshub NodeJS 5](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-1-Application-in-Server/assets/98991080/da5d2ab8-6549-4789-96a4-f2e3a68590c5)














