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
