Docker-kf-3-week

new

stratup-instraction:

перейдите в директурию dev: cd deploy\dev

забилди контейнеры: docker-compose up -d --build

сгенерируй ключ: docker-compose exec php php artisan key:generate

выполни миграцию: docker-compose exec php php artisan migrate

зайди на http://127.0.0.1:8001/ для проверки работоспособности