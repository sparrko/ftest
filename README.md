В первый запуск необходимо прописать

cd docker
sudo docker-compose up -d
sudo docker exec -ti f-php bash
  composer install
  php artisan migrate
  npm install
  exit

И можно открывать через: http://localhost:4001
