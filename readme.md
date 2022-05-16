### Настройка git
1. Создадим файл `.gitignore` и добавим в него исключения:
```gitignore
# исключенные папки
.idea/
.vc/
node_modules/

# исключенные файлы
.DS_Store
Thumbs.db
dektop.ini

package-lock.json
```

2. Настроим систему контроля версий для себя. Для это в консоли напишем несколько команд (если ранее не было настроено):
```bash
git config --global user.name "[имя]"
git config --global user.email "[ваш_email]"
```

Проверить применились ли изменения в конфигурации:
```bash
git config --global --list
```

3. Создадим репозиторий кода в корне нашего проекта:
```bash
git init
```
4. Сделаем индексацию изменений:
```bash
git add .
```