git clone https://github.com/ed-an/deep-queue-laravel.git


instale docker:
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04

instale docker-compose:
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-20-04


```
docker run --rm -v $(pwd):/app composer/composer create-project --prefer-dist  laravel/laravel src "9.*"
```
```
chown -R $user:$user -R src
```
```
export USER=$(whoami) && export  IDUSER=$(id -u)
```
```
docker-compose up -d --build
```

````
php artisan queue:table
````
```
php artisan migrate
```

```
fonte: https://www.honeybadger.io/blog/laravel-queues-deep-dive/
```

```
fonte: https://www.phind.com/search?cache=1e42f202-0667-4c0b-a034-8703d72f7459&init=true
```
