# mvc-api-sample
Symfony 6 based Template

#create entity:
php bin/console make:entity

#make migration:
php bin/console make:migration

#exec migration: #Need to create database backup
php bin/console doctrine:migrations:migrate

#drop a remake migration:
php bin/console doctrine:migrations:migrate

