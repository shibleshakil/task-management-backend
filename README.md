# task-management-backend

1. Pull the project
    git clone https://github.com/shibleshakil/task-management-backend.git

2. Update the composer 
    update composer

3. create a .env file and generate a app_key 
    php artisan key:generate

4. Setup database in .env

5. Migrate the database and seed admin table
    php artisan migrate --seed

6. Run the server 
    php artisan serve

Admin credentials

Email: admin@admin.com
Password: admin
    
