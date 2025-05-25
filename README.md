# Taski Lab

Проект выполнен в рамках лабораторной работы по дисциплине «Введение в облачные технологии».
Задача: На основе существующего проекта:
- Написать `Dockerfile` для фронтенда и бэкенда  
- Собрать `docker-compose` для запуска приложения  
- Настроить `GitHub Actions` для автоматической сборки образов и загрузка на Docker Hub

---

## Docker Hub

- [Frontend](https://hub.docker.com/repository/docker/kandler3/taski-lab-frontend)  
- [Backend](https://hub.docker.com/repository/docker/kandler3/taski-lab-backend)

---

## Запуск

1. Клонируйте репозиторий:

```bash
git clone https://github.com/Kandler3/taski-lab.git
cd taski-lab
```

2. Запустите приложение:

```bash
docker-compose up --build
```

3. Приложение будет доступно по адресам:

- http://localhost:3000 — фронтенд  
- http://localhost:8000 — бэкенд
