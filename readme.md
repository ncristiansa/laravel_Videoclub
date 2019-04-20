## VideoClub Laravel
Datos importantes para utilizar la App:

    - Realizar las siguientes comandas en el orden correspondiente:
       1. cp .env.example .env
       2. nano .env
           -  Modificar los parametros de la bases de datos:
               - Nombre DB: videoclub
               - Usuario: admin
               - Clave: admin
       3. php artisan key:generate
       4. php artisan migrate
       5. php artisan db:seed --class=DatabaseSeeder
       5. php artisan serve

