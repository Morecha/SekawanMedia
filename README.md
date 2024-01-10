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
| kontraktor1@gmail.com    | rahasia   | driver    |
| kontraktor2@gmail.com    | rahasia   | driver    |


- there's 3 roles.
- Admin only can submit the service
- 2 level verification only can be done by driver and moderator sides
- periodict tabel from excel doesnt included due error of vendor ([Laravel Excel](https://laravel-excel.com/)) doesnt support php version
- as long as the car status is "tidak aktif" there is chance to add service, when the status is "active" we cant add more (but the remaining doesnt deleted)


## Guides
### submit services only by Admin
1. Login using Admin
2. choose Service menu on sidebar
3. click "Tambah Service" Button
4. Masukkan Data

### Confirmation by Moderator or Driver
1. Login as Moderator or Driver
2. choose Pengajuan menu on sidebar (they only show service need your aproval)
3. click check button to accept
4. when both Moderator and Driver Accept it, the Cars status going to be active (can see on 'kendaraan' menu)

