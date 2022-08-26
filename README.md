# API-Restful-using-symfony

useful commands

php -S localhost:80 -t public -> runs PHP, starts Symfony and send it to the established route

composer require annotation -> allows that the routes can be reached by annotations

composer require symfony/orm-pack -> is used to map the object to a relational model

php bin\console doctrine:migrations:migrate ->migrates to database

php bin\console doctrine:migrations:diff-> verifies the mapping of the classes and databases, 
and creates a migration class based in difference between both

================================================================

composer require symfony/maker-bundle --dev-> install "makerbundle" apparently, allows other ways 
and commands that can be used in symfony

php bin/console make:migration-> makes a migration

php bin/console doctrine:migration:migrate-> migrates the table

