<p align="center"><img src="public/img/logo.png" width="150"></p>

## About TaraPay 
Simple project on Laravel framework for visual test API's payment service of TaraPay.

## Requirments

1. PHP >= 7.3
2. MySQL >= 5.7


## Deploy project

1. git clone git@github.com:tarapay/laravel.git
2. cd laravel
3. composer install
4. cp .env.example .env

5. edit  .env fill your data:
TARAPAY_USERNAME,TARAPAY_PASSWORD, TARAPAY_GATEWAY 
6. php artisan migrate:fresh
7.  php artisan key:generate
8. php artisan serve
9. echo '127.0.0.1:8000' 
## توجه
نام کاربری , رمز عبور و کد درگاه  تارا پی  را حتما باید
در فایل

.env 

وارد کنید:

مثال:

TARAPAY_USERNAME=11111111111

TARAPAY_PASSWORD=aaaaaaaaaaaaaaaa

TARAPAY_GATEWAY=11111

  
 
 


