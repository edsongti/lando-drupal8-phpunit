# lando-drupal8-phpunit


Drush version: 9
Drupal version: 8.8.9

## Requirements

Install Git, Docker and Lando (v3.0.0-rc2)

## How to use

run
- git clone git@github.com:edsongti/lando-drupal8-phpunit.git
- cd lando-drupal8-phpunit
- lando start
- lando composer install
- lando install

Now, do your code and unit test cases and just run the follow command to run PHPUnit:
- lando phpunit path_to_folder_or_file
