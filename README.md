# Drupal via DDEV

## Local setup

- make sure you have DDEV (+Docker) installed and running
- > ddev start (containers will start running)
- > ddev composer install (PHP dependencies will be downloaded)
- > ddev drush sql-drop -y
- > ddev drush sql-cli < dumps/dump.sql
- > ddev launch (site will be launched)
