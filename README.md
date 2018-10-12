#Membuat EndPoint menggunakan GET

RESTful API merupakan implementasi dari API. REST adalah suatu arsitektur metode komunikasi yang menggunakan protokol
HTTP untuk pertukaran data dan metode ini sering diterapkan dalam pengembangan aplikasi.
RESTful API diakses menggunakan protokol HTTP.URL API biasa disebut endpoint dalam pemanggilannya. 
GET adalah metode HTTP request yang digunakan untuk membaca atau mendapatkan data dari sumber.

## LANGKAH-LANGKAH
1. install nodeJS terlebih dahulu.
2. untuk hasil instalannya, saya letakkan di C.
3. kemudian setelah menginstal nodeJS, kemudian menginstal framework express.
     npm install -g express
untuk menginstal express saya menggunakan direktori C:\nodejs

4. Jika proses instalasi selesai, Kemudian dilajutkan untuk menginstal express generator secara global 
     npm install -g express–generator
	 
5. Membuat file project express baru dengan memasukkan perintah 
     express projekku –e
//disini projek saya bernama projekku

6. Setelah selai maka langkah selanjutnya adalah menginsatal dependencies dengan memasukkan perintah 
cd projekku && npm install

7. Mengaktifkan npm dengan sintak 
     npm start
	 
8. selanjutnya adalah membuat package.json dengan perintah npm init

9. menginstall express dengan menggunakan syntak 
npm install express --save

10. membuat file index.js  untuk memanggil file jsonconst express = require('express')
     const app = express()
     const port = 3000

     app.get('/', function (req, res) {
     res.json({ user: 'tobi' });
     })

     app.listen(port, () => console.log(`Example app listening on port ${port}!`))
	 

