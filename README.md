# Kantin SMA 3 Bojonegoro

A canteen management web application for SMA Negeri 3 Bojonegoro, featuring menu management, member handling, transactions, and reporting.

## Features

- Dashboard overview of canteen operations
- Menu type management (CRUD)
- Member management
- Transaction processing with printable receipts
- Report generation and export

## Tech Stack

- PHP
- MySQL
- JavaScript (vanilla)
- CSS

## Project Structure

```
.
├── index.php
├── dashboard.php
├── header.php
├── footer.php
├── koneksi.php
├── jenis-menu.php
├── jenis-menu-edit.php
├── jenis-menu-delete.php
├── laporan-*.php
├── cetak-*.php
├── Database/
├── css/
├── js/
└── img/
```

## Getting Started

1. Import the database schema from the `Database/` folder into MySQL.
2. Configure database credentials in `koneksi.php`.
3. Place the project files in your web server's document root (e.g., `htdocs` for XAMPP).
4. Open `index.php` in your browser.

<!-- last-updated -->
_Last updated: 2026-09-05_

