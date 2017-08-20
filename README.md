# NeoCode-fm-php-crud-api
Example of using FileMaker 16 Insert from URL with CURL options, MySQL and php-crud-api


REQUIREMENTS:

1 FileMaker 16 - for curl options!

2 Apache / PHP / MySQL - try MAMP or XAMPP

3 php-crud-api


FileMaker SECURITY:

admin / admin


PHP TO DO:

1 put api.php from php-crud-api into http documentroot

2 configure mysql user / pass in api.php - line 2696 to 2703 - according to your MySQL config


MySQL TO DO:

1 create a database called 'test' and create a 'test' table

CREATE TABLE `test` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `creation` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
  `text` longtext NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=20 DEFAULT CHARSET=utf8;


to use:

1 create MySQL 'test' table

2 configure

3 get secret - put into SMS Nexmo.fmp12

4 get nexmo number - put into from field in SMS Nexmo.fmp12

5 enter the phone number you want to send to into send number field

6 enter the message to send

7 click SEND

8 ???

9 EVEN MORE PROFIT
