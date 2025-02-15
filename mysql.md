# Managed MySQL Hosting
Product-Website: [https://25space.com/cloud/](https://25space.com/mysql/)
MySQL is an open source, object-relational database built with speed and reliability in mind. Its large and active developer community has created many third-party applications, tools, and libraries that expand MySQL’s functionality.

## What I get
We offer individual fully-managed MySQL databases. Whether it's for a single WordPress site or a larger, more extensive project. Usable and accessible from our primary hosting offers. We will provide you with all connection data, server details and access to our administration console.
MySQL from Oracle is the most widely used database system in the world. The powerful database server application is often used for dynamic web applications. More precisely: for the structured storage of data required for a wide variety of web services, including numerous services from globally recognised brands.

## Version
We use MySQL 8

## Support & Update time
This time can be found in the Cloud Management Suite. The default time is Sunday 2AM - 6AM (MEZ)

## Backups
All databases are backed up fully automatically once a day. We usually keep the snapshots for up to 5 days.

## Technical limits
- Max. storage for each database is 250MB

## Access from infrastructure
You can access the MySQL Databse from all Linux virtual servers as well as WebApps.
Access from Windows Servers is not possible, also they are not available from external services.

## Connection details
Are individual for customers, they can be found in the Cloud Management Suite

### MySQL Connection (for WordPress,...)
<code>
define ('MYSQL_HOST', '*hostname*:25060');
define ('MYSQL_USER', 'us_db_****************');
define ('MYSQL_PASS', '****************');
define ('MYSQL_DATA', 'db_****************');
</code>

### Connection parameters
<code>
username = us_db_****************
password = ****************
host = *to be found in the Cloud Management Suite*
port = 25060
database = db_****************
sslmode = REQUIRED
</code>

### Connection string
<code>
mysql://us_db_****************:show-password@*hostname*:25060/defaultdb?ssl-mode=REQUIRED
</code>

### Connection flag
<code>
mysql -u us_db_**************** -pshow-password -h *hostname* -P 25060 -D db_****************
</code>

## MySQL Access & PHPMyAdmin
You will find your connection details in the Cloud Management Suite at "Applications" > "MySQL".
To manage the database itself, you can use our phpMyAdmin installation: https://cloud.25space.com/tools/phpMyAdmin
