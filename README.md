# Video
- [Drive Link](https://drive.google.com/drive/folders/1Bh7UQxvFoigFDR03SwewOJIMI59iojdl?usp=sharing)

# Laravel Assignment – Requirements

This Laravel project includes the following components as per the assignment instructions:

## ✅ 1. Blade Template Conversion

- The following HTML/Bootstrap template has been converted into Laravel Blade:
  - [StartBootstrap - Personal](https://startbootstrap.com/theme/personal)
- Converted into:
    - `resources/views/layouts/app.blade.php` for the main layout.
- Partials :
    - `resources/views/partials/header.blade.php` for the header.
    - `resources/views/partials/footer.blade.php` for the footer.
- Pages :
    - `resources/views/home.blade.php` for the home page.
    - `resources/views/contact.blade.php` for the contact page.
    - `resources/views/projects.blade.php` for the projects page.
    - `resources/views/resume.blade.php` for the resume page.
- Contact page includes a form that submits data.
- All pages extend the main layout using `@extends('layouts.app')`.

## ✅ 2. Database Migrations

- Migration files are created based on the provided database diagram:
  - `customers` table
  - `categories` table
  - `products` table
  - `invoices` table
  - `invoice_products` table
- Each table in the schema is defined using Laravel migration files in the `database/migrations` folder.
- [Folder Link](https://github.com/AriyaArKa/MDL-16/tree/main/myproject/database/migrations)

## ✅ 3. Form Handling (e.g., Contact Form)

- A contact or task form is created and performs the following:
  - Submits data via `POST` request.
  - Displays a **success message** using `session()->flash()`.
  - Logs user input using `Log::info()` into Laravel's log file.
  - Redirects to a **confirmation page** that shows the submitted data.

- Confirmation page:
  - `resources/views/confirmation.blade.php`
  - Displays the submitted data.
  - Uses `@extends('layouts.app')` to extend the main layout.


