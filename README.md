aplikasi Retal Mobil Berbasis web menggunakan Framework Laravel 10

## Screenshots

![preview img](/preview.png)

## Donwload

Clone Projek

```bash
  git clone https://github.com/aziznurul/Rental-Mobil-Laravel.git nama_projek
```

Masuk ke folder dengan perintah

```bash
  cd nama_projek
```

-   Copy .env.example menjadi .env kemudia edit databasenya

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```

#### Login

-   email = admin@admin.com
-   password = 123
