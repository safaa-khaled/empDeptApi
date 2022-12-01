<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>


## About EmpDept Api

empDept API is built using laravel framework, it manage the relationship between employees and departments. the operations which are allowed:
employee: add new employee, update and show employee info, get all employees, get the department of an employee.
departments: add new department, update and show department info, get all departements, get the employees of a department.

to run empDept api on your machine:
- download repository zip file to your machine and extract it.
- create database.
- copy .env file and change database configuration with your database info.
- in terminal or cmd run this instructions:
    - composer update
    - php artisan key:generate
    - php artisan passport:install
    - php artisan migrate
    - php artisan serve
- test empDept api in postman using empDeptApi.postman_collection.json which could be found in empdeptapi zip file.


