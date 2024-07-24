<h1 align="center">Laravel Blog</h1>
**Admin**

- email: admin@gmail.com
- Password: 123123123

**Penulis**

- email: penulis@gmail.com
- Password: 123123123

**Pembaca**

- email: pembaca@gmail.com
- Password: 123123123

## Install

**Clone Repository**

```bash
git clone https://github.com/wahyu13052003/Blog-Kelompok_6.git
```

**Download zip**

```bash
extract file zip
```

## Buka di kode editor


## Install composer

```bash
composer install
```

## Copy .Env

```bash
copy .env.example menjadi .env
```

## Buat database di localhost 

```bash
nama database : blog
```

## Setting database di .env

```bash
DB_PORT=3306
DB_DATABASE=blog
DB_USERNAME=root
DB_PASSWORD=
```

## Generate key

```bash
php artisan key:generate
```

## Jalankan migrate dan seeder

```bash
php artisan migrate --seed
```

## Buat storage link

```bash
php artisan storage:link
```

## Jalankan Serve

```bash
php artisan serve
```
## License

- Copyright © 2024 Kelompok 6.
