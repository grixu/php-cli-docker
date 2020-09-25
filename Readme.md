## PHP-CLI

Custom Docker image of php-cli in newest stable version

## Arguments

* **user_uid** - nginx user UID value (default: 1001)
* **group_gid** - nginx group GID value (default: 1001)
* **max_upload** - max upload size in format: *40M* (which is default value)

## Modules:
* opcache
* PDO (Mysql)
* Mbstring
* exif
* curl
* bcmath
* pcntl
* redis
* gd
* gmp
* imagick
* intl
* zip
* swoole

## php.ini path
```
/usr/local/etc/php/php.ini
```