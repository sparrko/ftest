<br>В первый запуск необходимо прописать

<br>cd docker
<br>sudo docker-compose up -d
<br>sudo docker exec -ti f-php bash
  <br>composer install
  <br>php artisan migrate
  <br>npm install
  <br>exit

<br>И можно открывать через: http://localhost:4001
