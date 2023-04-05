# naive_bayes

Nama : Aditya Herdiansyah Putra
NIM  : A11.2021.13948

Pada proses klasifikasi dengan metode naive bayes ini saya menggunakan 4 library utama yaitu numpy, matplotlib, pandas, dan juga sklearn. Hal pertama yang saya lakukan yaitu Mengimport dataset dan kemudian pisahkan untuk atribut ditampung pada variable x dan untuk label ditampung pada variable y agar data tersebut bisa dilakukan proses klasifikasi. 
Setelah itu, kita tampilkan variable x dan y untuk memastikan bahwa perintah sudah berhasil dijalankan. Kemudian setelah itu memisahkan data menjadi dua yaitu testing dan juga training yang mana sebanyak 3/4 dari data akan digunakan untuk Training sedangkan untuk sisanya yaitu 1/4 digunakan untuk Testing. 
Pada proses ini, saya memanfaatkan library dari sklearn.model_selection dan menggunakan function train_test_split. Lalu untuk melakukan proses klasifikasi naive bayes maka saya menggunakan library skelarn.naive_bayes dengan menambahkan function GaussianNB.
Kemudian setelah itu saya hitung prediksinya dengan funtion predict. Untuk mengetahui tingkat keakuratan/nilai akurasinya, saya menggunakan diagram confussion matriks yang merupan fasilitas dari linrary sklearn untuk mengetahui tingkat keakuratan/ nilai akurasi dari data testing terhadap data prediksi.
Dari proses diatas menghasilkan prediksi tingkat keakurasiannya yaitu 0.88. Seletah itu untuk menampilkan diagram persebaran data yang harus dilakukan pertama kali yaitu mengalokasikan data x_train dan y_train ke variable baru yaitu x1 dan x2 supaya data x_train dan y_train tidak berubah ketika mejalankan proses. 
Kemudian saya kelompokkkan menjadi x1 untuk menampung age dan x2 untuk menampung annual salary dengan menggunakan function meshgrid dan arange dari numpy. Setelah itu perlu memetakan dari kedua data tersebut dengan function contourf dan saya bedakan warna agar mudah dipahami yaitu jika "yes" maka akan tampil merah dan "no" akan tampil warna hijau. 
Kemudian karena saya akan memvisualisasi datanya dengan grafik maka saya perlu mengatur batas sumbu dari plot, maka saya menggunakan xlim dari library matplotlib. Setelah itu saya enumerate kan data nya. dan yang terakhir tidak lupa untuk memberikan judul dan label untuk memperjelas grafik yang saya buat.
