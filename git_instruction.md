# Инструкция по работе с git
##  Начало работы
Проверить установлен ли git и корректно ли он работает
```sh
git --version
```
Инициализация git
```sh
git init
```
Проверить статус git на данный момент
```sh
git status
```
## Работа с файлами
Добавить файлы в git. Пока еще изменения не сохранены, но зафикстрованы
```sh
git add <имя>
git add --all (все)
git add . (все в папке)
```
Зафиксировать изменения
```sh
git commit -m "комментарий тут текст"
```
Посмотреть список измений
```sh
git log (подробно)
git log --oneline (в одну линию)
выход: q and Q
```
Разница между коммитами
```sh
git diff
```
Перейти к одному из изменений
```sh
git checkout <4 буквы/цифры комита>
```
## Работа с ветками
Посмотреть ветки файла
```sh
git branch 
```

Создать ветку
```sh
git branch имя_ветки
```

Перейти на другую ветку
```sh
git checkout <имя_ветки>
```
Объединить ветки
```sh
git merge
```
Удалить ветку
```sh
git branch -d <название>
```
Отобразить графически ветки
```sh
git log --graph
```
Отправить изменения в гитхаб
```sh
git push
```
Забрать изменения из гитхаб
```sh
git pull
```
Скопировать себе репозиторий
```sh
git clone <ссылка>
```
Если работаем с чьим то репозиторием
1. Делаем fork
2. Клонируем свою копию
3. Делаем в ней новую ветку
4. В ней проводим изменения
5. Выгружаем на сайт через push
6. Нажимаем pull requests и отправляем изменения
7. Ждем ответа