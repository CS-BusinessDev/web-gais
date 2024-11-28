## SUMO (Submission Mobile)
SUMO yang merupakan singkatan dari Submission Mobile adalah aplikasi berbasis Web yang ditujukan untuk mengelola data pengajuan dan laporan gangguan. SUMO juga merupakan pengembangan dari aplikasi IMO (IT Support Mobile) secara fungsional, dengan penambahan fitur-fitur dan aturan bisnis yang dibutuhkan.

## Database Design
<img src="https://devinaviantie.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F6331f855-64df-42ab-91a9-4aa09b5dbc67%2FGAIS_(2).jpeg?table=block&id=d730fe51-6e99-46cf-a84c-9134c4ff117a&spaceId=88824cb2-a652-488c-8937-b355bc9a5fa8&width=1420&userId=&cache=v2" width="100%"></img> 

## Requirements
* PHP 8.2 or higher
* Database (eg: MySQL, PostgreSQL, SQLite)
* Web Server (eg: Apache, Nginx, IIS)

## Installation
* Install [Composer](https://getcomposer.org/download)
* Clone the repository: `git clone https://github.com/CS-BusinessDev/web-gais.git`
* Install PHP dependencies: `composer install`
* Setup configuration: `cp .env.example .env`
* Generate application key: `php artisan key:generate`
* Create a database and update your configuration.
* Run database migration: `php artisan migrate`
* Run database seeder: `php artisan db:seed`
* Create a symlink to the storage: `php artisan storage:link`
* Run the dev server: `php artisan serve`
