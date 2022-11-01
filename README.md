# SISTEM LOGIN MENGGUNAKAN LARAVEL DAN REACTJS

<span float="center">
    <img src="https://github.com/giovannyrogi/Backend-Laravel/blob/master/resources/ui/loginpage.png" width="200"/>
    <img src="https://github.com/giovannyrogi/Backend-Laravel/blob/master/resources/ui/registerpage.png" width="200"/>
    <img src="https://github.com/giovannyrogi/Backend-Laravel/blob/master/resources/ui/homepage.png" width="200"/>
</span>
<br><br><br>

## Projek ini dibuat menggunakan :
 * Laravel Framework 8.83.25
 * PHP version 7.4.30
 * Node v16.16.0
 * npm version 8.11.0
 * Git version 2.34.1
 * XAMPP version 7.4.30-1
 * VSCode version 1.72.2
 * Postman version 10.0.1<br><br>
 
### Library / Framework yang digunakan :
 * JWT-Auth     : https://github.com/tymondesigns/jwt-auth
 * React Router : https://reactrouter.com/en/v6.3.0/getting-started/installation
 * Axios        : https://axios-http.com/docs/intro
 * Bootstrap    : https://getbootstrap.com/
 <br><br>
 
## Cara menjalankan projek ini

### <i><strong>Configurasi file Laravel untuk Backend</i></strong>

 * Buat 1 folder dan <i><strong>Clone</i></strong> projek <i><strong>Backend-Laravel</i></strong> ini kedalam folder yang telah dibuat.
 <br><code>git clone https://github.com/giovannyrogi/Backend-Laravel.git</code><br><br>
 * Buka file <i><strong>Backend-Laravel</i></strong> yang telah di <i><strong>Clone</i></strong> dengan menggunakan <i><strong>Text Editor</i></strong>.<br><br>
 * Buka <i><strong>CMD/Terminal</i></strong> di folder <i><strong>Backend-Laravel</i></strong> dan jalankan perintah <code>composer install</code>.<br><br>
 * Jalankan perintah <code>php artisan key:generate</code>.<br><br>
 * Kemudian didalam file <i><strong>Backend-Laravel</i></strong> buat file baru dengan nama <i><strong>.env</i></strong><br><br>
 * buka file <i><strong>.env.example</i></strong> yang ada dalam folder <i><strong>Backend-Laravel</i></strong> menggunakan <i><strong>Text Editor</i></strong>.<br><br>
 * Copy semua code yang ada dalam file <i><strong>env.example</i></strong> dan paste ke dalam file <i><strong>.env</i></strong><br><br>
 * Setelah itu pada file <i><strong>.env</i></strong> silahkan <i><strong>Configurasi</i></strong> sesuaikan dengan <i><strong>Database</i></strong> yang digunakan.<br><br>
 <a href="https://ibb.co/1fQkJT5"><img src="https://i.ibb.co/Fb3FqzM/env.png" alt="env" border="0" width="400"></a><br><br>
 *  Setelah selesai <i><strong>Configurasi database</i></strong>, silahkan jalankan perintah <code>php artisan migrate</code> pada <i><strong>CMD/Terminal</i></strong>.<br><br>
 * Jalankan perintah <code>php artisan jwt:secret</code>.<br><br>
 * Langkah terakhir memulai <i><strong>Server Laravel</i></strong> dengan perintah <code>php artisan serve</code> di <i><strong>CMD/Terminal</i></strong>.<br><br>
 * Biarkan <i><strong>Server</i></strong> berjalan dan lanjutkan ke <i><strong>Configuration</i></strong> file <i><strong>ReactJS</i></strong> untuk <i><strong>Frontend</i></strong>.<br><br>

### <i><strong>Configurasi file ReactJS untuk Frontend</i></strong>
 * Buat 1 folder dan <i><strong>Clone</i></strong> projek <i><strong>Frontend-ReactJS</i></strong> kedalam folder yang telah dibuat.
 <br><code>git clone [https://github.com/giovannyrogi/Backend-Laravel.git](https://github.com/giovannyrogi/Frontend-ReactJS.git)</code><br><br>
 * Buka file <i><strong>Frontend-ReactJS</i></strong> yang telah di <i><strong>Clone</i></strong> dengan menggunakan <i><strong>Text Editor</i></strong>.<br><br>
 * Buka <i><strong>CMD/Terminal</i></strong> di folder <i><strong>Frontend-ReactJS</i></strong> dan jalankan perintah <code>npm install</code>.<br><br>
 * Setelah selesai, mulai server dengan perintah <code>npm start</code> dan <i><strong>Sistem Login</i></strong> akan terbuka pada tab browser yang baru.<br><br>
   <img src="https://i.ibb.co/x1gPtmY/ui-login.png" alt="ui-login" border="0" width="500">
