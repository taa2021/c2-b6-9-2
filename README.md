# B6.9.2

## Задание

Ссылка: [здесь](./TASK.md)

## Решение

- Ansible-роль, настраивающая кэширующий DNS-сервер dnsmasq - [здесь](./roles/dnsmasq/)
- Ansible-playbook, создающий группу пользователей superusers, - [здесь](./superusers.yml); вспомогательная роль - [здесь](./roles/superusers/)
- Ansible-роль, настраивающая связку nginx+php-fpm - [здесь](./roles/webservices/)

```
# Заполняем перечень удаленных хостов для выполнения задания
vi hosts

# Конфигурируем супер-запуск
vi site.yml

```

## Проверка

Выводы проверочных команд: [здесь](./check-results/),
где первая строка в файле - проверочная команда, инициировавшая вывод.
