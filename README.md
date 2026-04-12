# UCC IT Web App

Progressive Web App (PWA) submission for the **UCC IT Progressive Web App**

## Group Members
- Tafarie Dyer   20215471
- Claudine Saddler  20232555

## Lecturer
Otis Osbourne

## Project Summary
This Laravel-based PWA provides students with access to:
- Faculty/Staff Directory
- Courses
- Admissions
- Social Media
- Email FAB for the Head of Department

## Features Implemented
1. **Responsive dashboard UI** with navigation cards for all required activities.
2. **Faculty/Staff Directory** with photo, phone number, email, direct dial and direct mail links.
3. **Courses module** with 10 seeded IT courses stored in the database.
4. **Admissions page** with admission requirements summary and a link to UCC's online application page.
5. **Social Media page** with integrated Facebook and Twitter/X embeds, plus Instagram quick access.
6. **Floating Action Button** that opens the device email app and pre-addresses an email to the HOD.
7. **PWA integration** prepared for the `erag/laravel-pwa` package.

## Tech Stack
- Laravel 11
- PHP 8.2+
- Blade
- HTML5
- CSS3
- JavaScript
- SQLite
- erag/laravel-pwa

## Setup Instructions
1. Extract the project.
2. Open a terminal in the project directory.
3. Run:
   ```bash
   composer install
   cp .env.example .env
   php artisan key:generate
   php artisan migrate --seed
   php artisan erag:install-pwa
   php artisan erag:update-manifest
   php artisan serve
   ```
## Important Notes
- The project uses **SQLite**. The `database/database.sqlite` file is already included.
- The social media page uses official public handles for `@UCCJamaica`.
- Instagram profile embedding is commonly restricted by browser/platform security policies, so a direct open button is provided as a fallback.
- Update the second group member name before submission.


## Deliverables Checklist
- [x] Laravel project files
- [x] README with group members section
- [x] PWA configuration
- [x] Database seeders for 10 courses
- [x] Zip-ready folder structure
- [ ] Push project to GitHub and add repository URL here before submission

## GitHub URL
Add your GitHub repository URL here after pushing.
