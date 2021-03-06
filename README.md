# Laravel 7 + Tailwind CSS Starter

![Laravel + Tailwind Logo](https://github.com/d3vkk/laravel-tailwind-starter/blob/master/laravel-tailwind-logo.png)

What is [Laravel](https://laravel.com/) or [Tailwind CSS?](https://tailwindcss.com/)

## Prerequisites

You should have the following installed
 - [PHP 7.3 or higher](https://php.net/)
 - [Laravel 7](https://laravel.com/)
 - [npm](https://npm.com/) or [yarn](https://yarnpkg.com/)

## Set up

Fork or clone this repo
```
git clone https://github.com/d3vkk/laravel-tailwind-starter.git
```

Install dependencies with npm or yarn
```bash
npm install
#or
yarn install
```

Compile css file and watch for changes
```
npm run watch
```

Link the css file to a blade file e.g. `./resources/views/welcome.blade.php`
```html
<link href = {{ asset('css/main.css') }} rel = "stylesheet" />
```

Start up php server
```
php artisan serve
```

© 2020-present Donald K • Under MIT License
