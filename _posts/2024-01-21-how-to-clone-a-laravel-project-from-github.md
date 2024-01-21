---
title: How to clone a Laravel project from Github
date: 2024-01-21
categories: [Laravel, PHP, Github]
tags: [laravel, php, github]
---

__Clone your project__ <br>
__Go to the folder application using ```cd``` command on your cmd or terminal__<br>
__Copy .env.example file to .env on the root folder.__<br>
*Windows command prompt*
```bash
copy .env.example .env
```
*Linux Terminal*
```bash
cp .env.example .env
```
__Open your ```.env``` file and change the database name ```(DB_DATABASE)``` to whatever you have, username ```(DB_USERNAME)``` and password ```(DB_PASSWORD)``` field correspond to your configuration.__<br>

__Run__
```bash
php artisan key:generate
php artisan migrate
php artisan serve
```
<br>
__Go to__ http://localhost:8000/

