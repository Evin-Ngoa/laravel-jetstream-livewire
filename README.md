# laravel-jetstream-livewire

- Nothing Serious, Just checking use of jestream-auth and livewire crud.

## Step 1
- Install Laravel framework `composer create-project --prefer-dist laravel/laravel laravel-jetstream-livewire`

## Step 2
- Install Jetstream: `composer require laravel/jetstream`. Point to note. jetsream uses tailwind css by default.
- Have Team Management Demo. Run : `php artisan jetstream:install livewire --teams`
- Run Frontend Dependencies : `npm install && npm run dev`

# Step 3
- Edit `.env` file and add your db creentials.
- Run Migration `php artisan migrate`
- Start Server :   `php artisan serve`

# Step 4 Simple Crud
- Create Model and migration for Student - `php artisan make:model Student -m`
