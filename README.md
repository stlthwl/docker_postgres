<h1>Команды docker</h1>

1. Запустить контейнер(ы)

```commandline
docker-compose up -d
```

2. Остановить контенер(ы)
```commandline
docker-compose stop
```

3. Остановить и удалить контейнер, сеть, тома
```commandline
docker-compose down -v
```

<h1>Git</h1>

1. Инициализировать гит 
``` git
git init
```

2. Добавить все файлы
```git
git add .
```

3. Коммит
```git 
git commit -m "Initial commit"
```

4. Связать локальный репозиторий с удаленным
```git 
git remote add origin http://github.com/<yuor_repository>
```
 
5. Переименовать ветку при необходимости
```git
git branch -M main
```

6. Отправить изменения на удаленный репозиторий
```git
git push -u origin main
```
