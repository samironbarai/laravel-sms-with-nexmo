# Laravel SMS with Nexmo

You will be able to send sms from laravel application to any mobile number

# Installation
1. Clone this repo
```
https://github.com/samironbarai/laravel-sms-with-nexmo
```

2. Install composer packages
```
$ cd laravel-sms-with-nexmo
$ composer install
```

3. Create and setup .env file
```
$ copy .env.example .env
$ php artisan key:generate
```

4. Install Nexmo Package for Laravel 
```
$ composer require nexmo/laravel
```

5. Create an account at https://www.nexmo.com
```
put Key and Secret in .env file
next go to # Test Numbers
add your desired mobile number and you will receive test message to this number
```
