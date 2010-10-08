To connect to an external database:
After installing your drupal 6.x
Open your drupal 6.x folder.(i.e open the folder which contains all the drupal files where you installed it)
Open sites/default/settings.php
Change $db_url to an array.
Key the drupal database as default
Key your database with whatever name you want.
Now you can access your database in any module.
To access your database use the command db_set_active('your db key goes here');