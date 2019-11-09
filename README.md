# Slim-Twig-Eloquent-Starter

A php starter pack with slim twig and eloquent

## Requirements

 - php 7.1 or more
 - composer
 - a text-file editor

## Install

### Create a project

 - Create your Slim, Eloquent et Twig PHP application by clicking on the button "Use this template"
 - Clone the created repository on your computer

### Configuration

 - Edit the `composer.json` file
    - Replace `template/play` by your application name in the name field
    - Replace `mynamespace` by your base namespace for autoloader in the PS-4 field
 - Run the command line `composer install` to install dependencies
 - To configure database connection, rename `src/config/db.conf.example` to `src/config/db.conf.ini`, then edit it
    - Replace information with your personal database information, especially
      - `host`
      - `username`
      - `password`
      - `database`
    - If you use other database server than mysql or mariadb, change the `driver` too.
    

