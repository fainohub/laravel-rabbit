# laravel-rabbit
Laravel + Rabbit MQ Project

Run docker-compose:

docker-compose up -d --build




Install dependencies:

Entrar em cada container e executar composer install


core:

1 - docker exec -it php.core.local sh

2 - composer install



transaction:

1 - docker exec -it php.transaction.local sh

2 - composer install



wallet:

1 - docker exec -it php.wallet.local sh

2 - composer install


Admin RabbitMQ:

http://localhost:15672/

Username: admin
Password: admin
