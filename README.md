# Dodee
Docker Development Environment via docker-compose

Run `wget -qO- -O flkone-php_mysql_slim.zip https://github.com/FLKone/Dodee/archive/php_mysql_slim.zip && unzip flkone-php_mysql_slim.zip && rm flkone-php_mysql_slim.zip`

Rename `Dodee-php_mysql_slim`

`cd` to it

Run `composer create-project slim/slim-skeleton code`

Run `docker-compose up`

Add `127.0.0.1 default.local` to `/etc/hosts`

Open http://default.local

Enjoy :D
