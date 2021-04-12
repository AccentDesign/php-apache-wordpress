## Example docker-compose.yaml

```
version: '2'
services:
  web:
    image: accent/php-apache-wordpress:7.4
    ports:
    - 80:80
    stdin_open: true
    volumes:
    - ./src:/var/www/html
    tty: true
  ```
