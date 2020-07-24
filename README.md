# docker-php-nginx

## Description

- Nginx latest
- PHP 7.4
- MySql 8.0
- Phpmyadmin

I use docker-compose as an orchestrator. To run these containers:

```
docker-compose up -d
```

Open web browser to look at a simple php example at [http://localhost](http://localhost)
Open phpmyadmin at [http://localhost:8000](http://localhost:8000)

Run mysql client:

- `docker-compose exec db mysql -u root -p` 

Enjoy !
