### HOW TO GET STARTED

> You will need to have Lando installed on your local machine. here is the installation guide https://docs.lando.dev/basics/installation.html.

### Steps
1. Clone the repo to your local machine `git clone https://github.com/imarilele/mtn.git`
2. Go to your peojeect and run `lando start` (this will also gives you a URL to the website )
3. Import the database run `lando db-import database.sql.gz` 

4. You can run `lando info` (This will show all information about your website, including urls and database information) 

### Drupal Login Details
- cd web
- run `lando drush uli`
- run `lando drush cr` to clear cache

### Resources
- https://docs.lando.dev/basics/installation.html
- https://docs.lando.dev/config/drupal9.html#getting-started
- https://dev.to/esnaremaussa/using-lando-with-drupal-9-3pbj