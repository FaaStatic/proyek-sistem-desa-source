# Sistem Administrasi Desa (Village Administration System)

A web-based village administration system built with **CodeIgniter 4** — my university final project (tugas akhir). Digitizes citizen data management and administrative letter services for village offices in Indonesia.

## Features

- Citizen/resident data management (CRUD)
- Administrative letter generation exported to **PDF** (FPDF)
- Google API integration (google/apiclient)
- Role-based access for village staff
- MySQL database (schema included: `tugasakhir.sql`)

## Stack

- PHP ≥ 7.2 · CodeIgniter 4 (MVC)
- MySQL
- FPDF for document generation
- PHPUnit for testing

## Setup

```bash
composer install
# import tugasakhir.sql to MySQL
# configure app/Config/Database.php
php spark serve
```

> 📚 Legacy academic project (kept for reference). My current backend work uses Go (Fiber) and Kotlin (Ktor) — see [Shop_project_be](https://github.com/FaaStatic/Shop_project_be).
