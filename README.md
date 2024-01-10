## template Laravel SB Admin 2
more info for template [Laravel SB Admin 2](https://github.com/aleckrh/laravel-sb-admin-2)
its my first time using this template because its free and my usual template I used is using laravel 8 ([QAdmin](https://github.com/superXdev/QAdmin)) where didnt supported anymore. so I decided to use this template and considering using it with newst version (laravel 10 and php 8.2)

### System Info
| information     | version         |
|-----------------|-----------------|
| laravel         | 10x             |
| php             | v8.2            |
| mySQL           | 10.4.28-MariaDB |

### user and password 
| username                 | password  | role      |
|--------------------------|-----------|-----------|
| admin1@gmail.com         | rahasia   | admin     |
| admin2@gmail.com         | rahasia   | admin     |
| moderator1@gmail.com     | rahasia   | moderator |
| moderator2@gmail.com     | rahasia   | moderator |
| driver1@gmail.com        | rahasia   | driver    |
| driver2@gmail.com        | rahasia   | driver    |


- there's 3 roles.
- Admin only can submit the service
- 2 level verification only can be done by driver and moderator sides
- periodict tabel from excel doesnt included due error of vendor([Laravel Excel](https://laravel-excel.com/)) and php version


## Installation

- Clone the repo and `cd` into it
- Run `composer install`
- Rename or copy `.env.example` file to `.env`
- Run `php artisan key:generate`
- Set your database credentials in your `.env` file

## Note

Recommend to install this preset on a project that you are starting from scratch, otherwise your project's design might break.

If you found this project useful, then please consider giving it a :star:

## Credits

Laravel SB Admin 2 uses some open-source third-party libraries/packages, many thanks to the web community.

- Laravel - Open source framework.
- LaravelEasyNav - Making managing navigation in Laravel easy.
- SB Admin 2 - Thanks to Start Bootstrap.

## Preview

`login`

<img src="https://imgur.com/YjGp6Sbl.png">

***

`register`

<img src="https://imgur.com/Wj09cu4l.png">

***

`dashboard`

<img src="https://imgur.com/CrmOfT5l.png">

***

`profile`

<img src="https://imgur.com/5t4eS1rl.png">

***

`logout`

<img src="https://imgur.com/d9JclOYl.png">

## License

Licensed under the [MIT](LICENSE) license.
