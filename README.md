Docker-kf-3-week

new

stratup-instraction:

открой докер десктоп

перейти в директурию проекта

перейдите в директурию dev: cd deploy\dev

забилди контейнеры: docker-compose up -d --build

composer install: docker-compose exec php composer install

перейдите в директурию dev: cd deploy\prod

забилди контейнеры: docker-compose up -d --build

перейдите в директурию dev: cd deploy\dev

сгенерируй ключ: docker-compose exec php php artisan key:generate

выполни миграцию: docker-compose exec php php artisan migrate

зайди на http://127.0.0.1:8000/ для проверки работоспособности
