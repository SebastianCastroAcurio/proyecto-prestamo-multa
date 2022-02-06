# CALCULAR MULTAS POR PRÉSTAMO DE EQUIPOS - LARAVEL

Calcular multas de equipos prestados en base a la fecha inicio del préstamo , la fecha de finalización del préstamo y la fecha de entrega del equipo, Si el equipo no ha sido devuelto va mantener el estado de Prestado y no presentará fecha de entrega. En el caso que el equipo no ha sido entregado dentro del filtro de multas, se calculará la multa hasta la fecha actual ( Today() ). En el contralador se calculará $5 por cada día de no cumplir la entrega pactada

# LARAVEL

Laravel es un framework de código abierto para desarrollar aplicaciones y servicios web con PHP 5, PHP 7 y PHP 8. Su filosofía es desarrollar código PHP de forma elegante y simple, evitando el "código espagueti".

# COMPOSER

Composer es un sistema de gestión de paquetes para programar en PHP el cual provee los formatos estándar necesarios para manejar dependencias y librerías de PHP.

# Crear un nuevo proyecto con Composer

`composer create-project laravel/laravel example-app`
`cd example-app`
`php artisan serve`

# Migración de tablas con Laravel

Para crear tabla migrations:

`php artisan migrate:install`

Para borrar todas las tablas de la base de datos y luego volverlas a crear:

`php artisan migrate:refresh`

Para eliminar todas las tablas:

`php artisan migrate:reset`

Permite deshacer el último grupo de migraciones ejecutadas:

`php artisan migrate:rollback`

# BOOTSTRAP

Bootstrap es una biblioteca multiplataforma o conjunto de herramientas de código abierto para diseño de sitios y aplicaciones web.

Para agregar rápidamente Bootstrap a nuestro proyecto podemos descargar el paquete o simplemente utilizamos un CDN.

# Documentación de Laravel:

-   https://laravel.com/docs/8.xl

# Documentación de Bootstrap:

-   https://getbootstrap.com/docs/5.1/getting-started/introduction/

# Contacto

sebastian.castro.acurio@udla.edu.ec
