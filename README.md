# client-area-subscription
A Custom Client area for services subscription. Paypal gateway payment and automatic invoice generation

#Installation requirements
* PHP
* Database
* ssh access to for automated SSL domain certificates validation with let's encrypt and to edit crontab

#Installation
Download the client-area folder into the root directory of your active domain.
The application will be available at http://example.com/client-area


#Configuration
* Copy dbconfig.sample.php to dbconfig.php
* Edit file dbconfig.php with your custom settngs for database connection and your site url
* Edit file classes/ClassEmailSender.php with the email account settings to send emails from




