## Just Validation Password Using Laravel
- Min 8 Character
- Password Conatining Min 1 Uppercase , 1 digit special character
- Checking for bad password based on dictionary bad password
- History Password (3x)


### Installing

1. Clone this repo

2. Install dependency

   composer install
   ```

3. Setup Database

4. Setup Aplications

Rename .env.example to .env and fill the environment variable.

Generate a new key for your local application
```
php artisan key:generate
```

Migrate the table to database
```
php artisan migrate

5. Run the project
php artisan serve
```
