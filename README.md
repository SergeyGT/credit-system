```markdown
## Быстрый старт

### 1. Клонирование репозитория

```bash
# Клонировать мастер-репозиторий с подмодулями
git clone --recursive https://github.com/SergeyGT/credit-system.git
cd credit-system
```

### 2. Запуск через Docker Compose

```bash
# Собрать и запустить все сервисы
docker-compose up --build

# Или в фоновом режиме
docker-compose up -d --build
```

### 3. Доступ к приложению

| Сервис       | URL                   |
|--------------|-----------------------|
| Фронтенд     | http://localhost      |
| Бэкенд API   | http://localhost:8080 |
| База данных  | localhost:5432        |
```
