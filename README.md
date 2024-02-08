# Drupal via DDEV

## Local setup

- make sure you have DDEV (+Docker) installed and running
- > ddev start (containers will start running)
- > ddev composer install (PHP dependencies will be downloaded)
- > ddev drush sql-drop -y
- > ddev drush sql-cli < dumps/dump.sql
- > ddev launch (site will be launched)

## Dumps

When ready and you need to export database changes, perfom:

- > ddev drush cr
- > ddev drush sql-dump --result-file=../dumps/dump.sql

And commit all changes to git.
