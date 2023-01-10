<br>В первый запуск необходимо прописать:

<br>cd docker
<br>sudo docker-compose up -d
<br>sudo docker exec -ti f-php bash
  <br>composer install
  <br>php artisan migrate
  <br>npm install
  <br>exit

<br>После можно открывать через: http://localhost:4001

<br><br>Если надо все удалить и переустановить (других images и containers не нужны!):
<br>cd docker
<br>docker rmi -f $(docker images -aq)
<br>sudo docker-compose build