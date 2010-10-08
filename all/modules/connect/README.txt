To connect to an external database:
After installing your drupal 6.x
Open your drupal 6.x folder.(i.e open the folder which contains all the drupal files where you installed it)
Open sites/default/settings.php
Change $db_url to an array.
Key the drupal database as default
Key your database with whatever name you want.
Now you can access your database in any module.
To access your database use the command db_set_active('your db key goes here');


To use the connect module:
In the sites folder open the all folder
Create a modules folder
Create a connect folder in the modules folders
Add the two files connect. module and connect.info into this folder
Open the connect.module file and make the necessary changes.(follow directions in the comments)
Install the module.