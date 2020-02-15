# lando-drupal8-phpunit


Drush version: 9
Drupal version: 8.7.2

## Requirements

Install Git, Docker and Lando (v3.0.0-rc2)

## How to use

run 
- mkdir your_project
- cd your_project
- git init
- git remote add origin https://github.com/edsongti/lando-drupal8-phpunit.git
- git pull origin master
- lando composer install
- lando start
- lando install

Now, do your code and unit test cases and just run the follow command to run PHPUnit:
- lando phpunit path_to_folder_or_file


