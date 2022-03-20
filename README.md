# Symfony 6 + PHP 8.1 with Docker
<hr>
Environment for develop an app 

A very simple Docker-compose to discover Symfony 6 with PHP 8.1 in 5 minutes
<hr>

## How to run ?
<hr>
Clone the project
```bash
git clone https://github.com/disco07/docker-php-nginx-postgres.git
```

Run the docker-compose
```bash
docker-compose build
docker-compose up -d
```

Enter on bash PHP 
```bash
docker exec -it php8-container bash
```

Create your new Symfony application
```bash
symfony new project-name --full
```

Your application is available at http://127.0.0.1:8080* 

Modify the .env file like this:
```bash
DATABASE_URL="postgresql://symfony:ChangeMe@postgres:5432/app?serverVersion=13&charset=utf8"
```

##Requirements
<hr>
<ul>
<li>Linux-Windows-MacOs</li><li>Docker</li><li>docker-compose</li>
</ul>
