# Laravel OAuth 2.0 RestFUL API

Bu proje Mediatriple Teknolojileri iş mülakatı için Çağla Öztürk tarafından yapılmıştır.

# Gereksinimler

1. PHP versiyon en az 7.3    
2. Laravel versiyon  8  

# Kurulum
```sh
$ composer install
$ php artisan migrate
$ php artisan db:seed
```
  - composer install komutuyla bağımlılıkları yükleyin.
  - .env.example dosyasını .env olarak değiştirin ve veritabanı bilgilerinizi güncelleyin

# Giriş
>     
> email : admin@admin.com
> pass :  12345678
> 

# Test:
>'headers' => [
>    'Accept' => 'application/json',
>    'Authorization' => 'Bearer '. $access_token,
>]

| Method | Link | İstek |
| ------ | ------ | ------ |
| Döküman | http://localhost:8000/api/documentation | ---- |
| POST | http://localhost:8000/api/register | name, email, password |
| POST | http://localhost:8000/api/login | email, password |
| POST | http://localhost:8000/api/address | detail |
| GET | http://localhost:8000/api/users | ---- |
| GET | http://localhost:8000/api/address | ---- |
| GET | http://localhost:8000/api/address/{id} | ---- |
| PUT | http://localhost:8000/api/address/{id} | detail |
| DELETE | http://localhost:8000/api/address/{id} | ---- |
