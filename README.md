# lando-drupal8-phpunit

Install Git, Docker and Lando (v3.0.0-rc2)

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
