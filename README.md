# Express JS Basic

1. Install package `$ npm init`
2. Install express `$ npm i express`
3. Create server file
4. How to run `$ node index`, index because the file
5. Install nodemon `$ npm i -D nodemon`, nodemon ini supaya kita tidak perlu nge restart si server filenya, jadi tinggal refresh page aja, pakai nodemon hanya untuk develop not for production
6. run pakai nodemon `$ npm run dev`
7. Coba

- http://localhost:5000/
- http://localhost:5000/about.html

8. Test Api, buka postman

- Pastikan pada GET request
- Masukan `http://localhost:5000/api/members`

9. Cek middleware

- Masukan `http://localhost:5000/api/members` di postman
- Cek di console, harusnya keluar 'Helow'

10. Cek url

- Masukan `http://localhost:5000/api/members` di postman
- Cek di console, harusnya keluar url http://localhost:5000/api/members yg keluar

11. Install moment `$ npm i moment`
    Cek moment (waktu)

- Masukan `http://localhost:5000/api/members` di postman
- Cek di console, harusnya keluar url http://localhost:5000/api/members dan ada waktuny

12. Get Single Member
    Test

- http://localhost:5000/api/members/2
  Angka 2 bisa diganti jadi 3, 4, atau berapa aja

13. Create Member

- Install `npm i uuid`<br>

- #### Test nya

- Setup postman sebagai `POST` method
- Masukkan `http://localhost:5000/api/members`
- Pilih `Body`, setelah itu kemudian pilih `raw`
- Masukkan

```
{
	"name": "Jake Smitsh",
	"email": "jake@gmail.com"
}
```

di raw tersebut

- Click `Send`
- Cek Hasilnya di Body > Pretty bagian bawah postman

14. Update Member

- #### Test nya

- Setup postman sebagai `PUT` method
- Masukkan `http://localhost:5000/api/members/1`
- Pilih `Headers`
- Isi colomn pertama pada KEY dengan `Content-Type`
- Isi colomn pertama pada VALUE dengan `application/json`
- Pilih `Body`, setelah itu kemudian pilih `raw`
- Masukkan

```
{
	"email": "john@yahoo.com"
}
```

di raw tersebut

- Click `Send`
- Cek Hasilnya di Body > Pretty bagian bawah postman

15. Delete Member

- #### Test nya

- Setup postman sebagai `DELETED` method
- Masukkan `http://localhost:5000/api/members/1`
- Click `Send`
- Cek Hasilnya di Body > Pretty bagian bawah postman

16. Membuat Template

- Pakai `express-handlebars`, goto [https://github.com/ericf/express-handlebars](https://github.com/ericf/express-handlebars) for ducumentiations
- Install express-handler `npm install express-handlebars`
