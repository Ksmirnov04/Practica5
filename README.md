# Practica5
# Практическая работа №5
## Основы работы с системой контроля версий Git

Выполнил: Смирнов Кирилл 
Логин GitHub: Ksmirnov 


## 1. Создан аккаунт на GitHub
- Логин: **Ksmirnov** (первая буква имени + фамилия)

## 2. Создан репозиторий на GitHub
- Репозиторий создан **без README.md**

## 3. Инициализирован локальный репозиторий
```bash
$ git init
```

## 4. Создан файл .gitignore
```bash
$ cat .gitignore
*/bin/
*/obj/

.vs/
packages/
```

## 5. Настроен пользователь Git
```bash
$ git config user.name "Kirill"
$ git config user.email "kirillsmernov00@gmail.com"
$ git config --global http.sslVerify false
```

## 6. Добавлены файлы и создан коммит
```bash
$ git add .
$ git commit -m "Initial commit: добавлен .gitignore"
[main (root-commit) 83242b4] Initial commit: добавлен .gitignore
 1 file changed
 create mode 23482 .gitignore

```

## 7. Привязан удалённый репозиторий
```bash
$ git remote add origin https://github.com/Ksmirnov/first.git
$ git remote -v
origin  https://github.com/Ksmirnov/first.git (fetch)
origin  https://github.com/Ksmirnov/first.git (push)
```

