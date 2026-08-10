1. Клонирование репозитория
# Клонировать мастер-репозиторий с подмодулями
git clone --recursive https://github.com/SergeyGT/credit-system.git
cd credit-system
2. Запуск через Docker Compose
# Собрать и запустить все сервисы
docker-compose up --build

# Или в фоновом режиме
docker-compose up -d --build
3. Доступ к приложению





















СервисURLФронтендhttp://localhostБэкенд APIhttp://localhost:8080База данныхlocalhost:5432
