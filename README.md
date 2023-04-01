Тестовое задание<br><br>

Этот проект реализует простое CRUD API управления списком пользователей, с валидацией полей.<br><br>

Для запуска необходим Docker<br><br>

В директории с проектом выполните:<br>
docker-compose up<br><br>
Затем, в консоли php в контейнере выполните миграцию<br>
bin/console make:migration<br><br>

Проект доступен в браузере по фдресу: https://localhost/<br>
Api platform: https://localhost/api<br><br>

Контейнер основан на другом контейнере: <br>
https://github.com/dunglas/symfony-docker<br><br>

Список изменений:<br>
Db: Mysql<br>
Pdo: mysql_pdo<br>
Bundles: ApiPlatform, maker, validator<br>
И сам проект
