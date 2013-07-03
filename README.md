PHP-movie-database
=======================
PHP-movie-database is a movie database script written in PHP.

Tested on
-------------------------
The script is tested on both a local (virtual) Ubuntu 13.04 server with:
* PHP 5.4.9
* MySQL 5.5.31
* Apache 2.2.22

and on 000webhost.com with:
* PHP 5.2.17
* MySQL 5.1
* Apache 2.2.19

You have to do the following for the script to work:
-------------------------
* Download [Twitter Bootstrap](http://twitter.github.com/bootstrap/), created with 2.3.1
 * Just copy it straight to the script folder
* Download [PHP IMDb Scraper](http://web3o.blogspot.se/2010/10/php-imdb-scraper-for-new-imdb-template.html), tested with update June 10 - 2013 
 * Copy it to the class/ directory
* Change MySQL account information in file class/database.php
* Run the install script located in the install directory, then remove it from the webserver (for safety)
* When uploaded to your webpage will you need to make the director img/posters/ writable as it is the folder where the posters will be saved by the script

TODO:
-------------------------
- [x] Install script (for database)
- [ ] Admin zon?
- [x] Possibility to mark seen movies, comment and rate them 
- [ ] Multilanguage, currently only swedish

Licence
-------------------------
[![Creative Commons License](http://i.creativecommons.org/l/by-sa/3.0/88x31.png)](http://creativecommons.org/licenses/by-sa/3.0/deed.en_US)
