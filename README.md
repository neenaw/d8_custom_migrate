# d8_custom_migrate
Dependencies: Migrate, Migrate_Tools, Migrate_Plus and Migrate Source CSV

Steps for making it works
1. Enable the above modules after enable Drupal Core's Migrate Module
2. Setup content type that want to used for inpurting the csv data
3. Upload the Source CSV file into the dev drupal 8's sites/default/files public file directory
4. Update the config ymal file to reflect the path for accessing the csv.
5. run drush en to enaable the custom module
6. check migrate status to confirm the csv file is accessible
7. run drush mi to import the csv data through drush
