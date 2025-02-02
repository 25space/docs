# WebApps Hosting
Product-Website: https://25space.com/cloud/

## MySQL Access & PHPMyAdmin
You will find your connection details in the Cloud Management Suite at "Applications" > "MySQL".
Please note, you can only access to our database-services only from our own platform and services. In the Cloud Management Suite Applications you can access the phpMyAdmin app and also find the current database credentials.
![phpMyAdmin]([http://url/to/img.pn](https://25space.com/support/data/mysql_access.jpg))
To manage the database itself, you can use our phpMyAdmin installation.
https://cloud.25space.com/tools/phpMyAdmin

## WebApps Access - Via Web Manager
With the App Manager you can directly access the source code / webspace of your WebApp. You can do administrative work in the files and folders there. If you have multiple projects, you can manage them all centrally.
Access
You will receive the access data from our customer service after the product order or provision. You will find the access data in the Cloud Management Suite at "Applications" at the respective WebApp.
You can change the password after login, right click on the menu button to make this setting. If you have forgotten your access data, please contact our customer service directly.


## WebApps URL
Once your WebApp is up and running, you’ll find your WebApp in My Applications in the Cloud Management Suite.
If you have not yet enabled a domain for your WebApp, you can access your app at:
https://app.on25space.com/manager/workspace/**YOUR-ID**


## WebApps SSL Certificate
To assign an SSL certificate to a domain, perform the following steps:
- Log in to the Cloud Management Suite
- Click on “Create” in the top left
- Choose “SSL”
- Enter the domain for which the certificate is to be activated.
A subsequent change is unfortunately not possible with SSL certificates for technical reasons.
In this case you are welcome to contact our customer service.


## WebApps Time Zone
WebApps – Time Zone Changes To change the time zones in WebApps (default DE), define this in the HTML code.
Start your PHP session with: date_default_timezone_set(„Europe/Berlin“);
https://www.php.net/manual/de/timezones.php

## WebApps Application Default Access
If you order a pre-installed application (like WordPress) for WebApps, access is automatically created here. This is different from accessing the WebApp (web space) itself.

### Installations after 2020
You will receive a individual crypt password for the installation.

### Installations until end of 2019
Until 2019 all pre-installations have the login passowrd like the following:
User: admin
Password: password123!
Please change it afterwards!


## MySQL External Access
Update August 2020
You can only access our database services our from own hosting services. This includes our virtual servers and also the WebApp platform. The URL and port information you will find in the Cloud Management Suite > Applications.

### Update from 29.11.2018
On 8th December 2018 we will stop the external access for all our MySQL Database Server and Applications. On this date you will only reach your database from your server, WebApp or mdct Cloud Application. Please make sure that you are connected to our MySQL Server via “localhost” or the known URL on an application, which is hosted on a mdct Cloud Product.
Please note: Our vServers are not allowed to connect to our database system.
We proceed this step as a part against cyber security.



