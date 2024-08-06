# GitHub-repository_AMH

HINANAY, ALEXANDER M. 

**Google Document:** [here](https://docs.google.com/document/d/1B_3uHDOq65iIYs3ZhEH-dc2QGRysxmSA15Sp_RRv_Fg/edit)

## Software/packages
- MacOS or Ubuntu OS
  - doesn't have any backup option :(

- Node 18.x
  - v20.16.0

- PHP 8.2
  - PHP 8.3.10 (cli) (built: Jul 30 2024 15:15:59) (ZTS Visual C++ 2019 x64)
  - Copyright (c) The PHP Group
  - Zend Engine v4.3.10, Copyright (c) Zend Technologies

- MySQL/MariaDB Database
  - mysql Ver 8.0.39 for Win64 on x86_64 (MySQL Community Server - GPL)

- Composer
  - Composer version 2.7.7 2024-06-10 22:11:12
  - PHP version 8.3.10 (C:\php-8.3.10\php.exe)
  - Run the "diagnose" command to get more detailed diagnostics output.

- Git
  - git version 2.46.0.windows.1

- PHPUnit
  - (built in with Laravel) - (PHPUnit 11.3.0 by Sebastian Bergmann and contributors.)
  - Laravel Framework 11.19.0

- Playwright
  - Version 1.45.3

## Setup

## Setup

### 1. Clone the Repository
Clone the repository using Git:
```bash
git clone https://github.com/praxxys/qa-engineer-exam
cd qa-engineer-exam
```
Install Laravel 10.x and set up the project:
```bash
composer create-project laravel/laravel:^10.0 example-app
cd example-app
php artisan serve
```
### 2. Implement Laravel Tests
Create at least 3 browser tests using Laravel Dusk
```bash 
composer require laravel/dusk --dev
```
```bash 
php artisan dusk:install
```
```bash
php artisan dusk:make test-1
php artisan dusk:make test-2
php artisan dusk:make test-3
```


### 3. Install Playwright
```bash
npm init playwright@latest
```
```bash
npx playwright test
```
```bash
npx playwright test --ui
```


## System Specifications

- **Processor**: AMD Ryzen 7 4800H with Radeon Graphics 2.90 GHz
- **Installed RAM**: 12.0 GB (11.4 GB usable)
- **Device ID**: B63238E3-B291-438B-9403-8713311BE880
- **Product ID**: 00342-42609-66323-AAOEM
