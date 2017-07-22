# Laravel 5.5.x Front-end Preset For Zurb Foundation

Preset for Zurb Foundation 6 scaffolding on new Laravel 5.5.x project.
Current version: Zurb Foundation for sites 6.4.1

## Usage
1. Fresh install Laravel 5.5.x and `cd` to your app.
2. Install this preset via `composer require laravel-frontend-presets/zurb-foundation`.
3. Use `php artisan preset foundation` for basic Zurb Foundation scaffolding.
4. Use `php artisan preset foundation-auth` to add Auth route entry and create Zurb Foundation Auth views. (NOTE: If you run this command several times, be sure to clean up the duplicate Auth entries in `routes/web.php`)
5. `npm install`
6. `npm run dev`
7. Configure your favorite database (mysql, sqlite etc.)
8. `php artisan migrate` to create basic user tables.
9. `php artisan serve` (or equivalent) to run server and test preset.