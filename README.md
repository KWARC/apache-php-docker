# apache-php-docker

This is a Docker Image containing an [Apache](https://www.apache.org) Webserver with PHP 7 and pre-installed PHP Extensions:
- json
- opcache
- readline
- xml 

It serves files from `/var/www/html` on port `80`. 

This image can be found on [Docker Hub](https://hub.docker.com/r/kwarc/apache-php) and is configured as an automated build. 

To use it, run e.g.: 

```
    docker run -p 80:80 -v static:/var/www/html kwarc/apache-php
```

## License

This work is released into the public domain, using the [UNLICENSE](./LICENSE). 
