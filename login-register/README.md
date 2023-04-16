Vous devez avoir préalablement  ceci sur votre PC  : 

-Composer
-CLI Symfony
-PhpMyadmin
-PHP >= 7.2.5

Vous pouvez ensuite faire cette commande dans la console
dans l'emplacement de projet "login-register" : 

php bin/console doctrine:database:create  

php bin/console make:migration

php bin/console doctrine:migrations:migrate

symfony serve:start

Ensuite http://127.0.0.1:8000/register sur votre navigateur


