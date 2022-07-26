# Docker-PHP-and-MYSQL

Is a containter php + mysql

## Up containers

command: docker-compose up -d

## config:

  MYSQL_ROOT_PASSWORD: cursophp
  
  MYSQL_DATABASE: cursophp
  
  MYSQL_USER: cursophp
  
  MYSQL_PASSWORD: cursophp
  
  ports:
  localhost: web
  
  3306: MySQL

## Estructure of Site

  src/
    index.php
