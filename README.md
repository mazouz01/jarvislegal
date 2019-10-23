# Jarvis Legal
Test technique backend Symfony - API platform

1- Make sure you have Composer installed and run: composer install
2- Edit .env file with your own database infos and run:

php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate

**Start the built-in web server**
3- download symfony installer from here: https://symfony.com/download
4- run command: symfony serve -d 

5- go to:  http://localhost:8000/api