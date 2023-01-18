<br>  my-php-mvc-project/
<br>  ├── config/
<br>  │   ├── config.php                              This folder contains the configuration files for the application, such as database connection details.
<br>  │   ├── database.php
<br>  ├── app/                                        This folder contains the core application files, such as the controllers, models, and views.
<br>  │   ├── controllers/                            This folder contains the controllers that handle the logic for the different pages of the website.
<br>  │   │   ├── HomeController.php
<br>  │   │   ├── UserController.php
<br>  │   ├── models/                                 This folder contains the model classes that interact with the database.
<br>  │   │   ├── User.php
<br>  │   ├── views/
<br>  │   │   ├── home/
<br>  │   │   │   ├── index.php
<br>  │   │   ├── auth/
<br>  │   │   │   ├── login.php
<br>  │   │   │   ├── register.php
<br>  │   │   ├── users/
<br>  │   │   │   ├── index.php
<br>  │   │   │   ├── edit.php
<br>  │   │   │   ├── add.php
<br>  ├── public/                                     This folder contains the publicly accessible files, such as CSS, JavaScript, and images.
<br>  │   ├── css/
<br>  │   │   ├── style.css
<br>  │   ├── img/
<br>  │   ├── js/
<br>  │   │   ├── script.js
<br>  │   ├── index.php
<br>  ├── .htaccess                                   This file is used for URL rewriting and redirecting all incoming requests to the front controller public/index.php.
