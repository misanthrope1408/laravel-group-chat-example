# Laravel WebSockets Group Chat Example

This is a Chat system example application built with the [Laravel WebSockets](https://github.com/beyondcode/laravel-websockets) package, [VueJs](https://vuejs.org/) and [Laravel-Echo](https://laravel.com/docs/5.7/broadcasting#installing-laravel-echo). Pusher account not required!!

## Tutorial
[![Real-time Chat system](http://i3.ytimg.com/vi/H_4UubWE9NQ/hqdefault.jpg)](https://www.youtube.com/watch?v=H_4UubWE9NQ&list=PL1TrjkMQ8UbWfFUCimQ50CdrR_J7QvEFW)
1. I used tutorial by above link.
2. Laravel project was updated on 5.8.
3. laravel-websockets to 1.4.

## Usage

1. Clone this repository
`git clone https://github.com/misanthrope1408/laravel-group-chat-example.git`
2. `composer install`
3. `cp .env.example .env` and configure your database in .env file.
4. `php artisan key:generate`
5. Run migration to create tables in database.
`php artisan migrate`
6. Run websockets server.
`php artisan websockets:serve`,
7. Final step, run artisan server in new terminal window
 `php artisan websockets:serve`,

routes

Now test it in your browser.
