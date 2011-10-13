Generally the process is:

* Download code in a `heroku run bash` that's a PHP app
* `/app/php/bin/phpize`
* `./configure --with-php-config=/app/php/bin/php-config`
* `make`
