# Docker setup for symfony 4

- php7.1-fpm
- nginx
- mysql5.6

## Installation

> Run the following command as sudo to view the project in browser on url [http://s4.local](http://s4.local)
> ```bash
> echo "127.0.0.1 s4.local" >> /etc/hosts
> ```

```bash
cd projects/symfony

composer install

cd ../../

docker-compose up
```
