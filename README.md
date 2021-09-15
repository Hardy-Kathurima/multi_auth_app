## Multi-auth with laravel.
This project is an implementation of multi-auth using roles.     

The project consists of a normal user and an admin. 

### Built with 
- Laravel 8 
- Bootstrap 4
- Sass

### How to run it locally 
Clone or download the repository.

Configure the .env file and create database

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=multi_auth_app
DB_USERNAME=root
DB_PASSWORD=
```

Install all the dependencies and compile
```npm
npm install && npm run dev
```
Fire up the local server 

```laravel
php artisan serve
```
Register users,in your database change user role to 1 for admin and 0 for a normal user.

:-) Congratulations! you have successfully installed the project in your local server.

You can change the views according to your specifications.

#### Project preview
Admin page
![alt text](public\images\admin.png)
User Page
![alt text](public\images\user.png)

#### Author
[Hardy Kathurima](https://www.linkedin.com/in/hardykathurima)

