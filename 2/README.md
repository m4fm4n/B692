Playbook для:
1. Создание группы superusers
2. Добавление этой группы в sudo
3. Создание пользователей user2 и user3 и добавление их в группу superusers


Изменить адреса хостов можно через файл hosts .


Запуск осуществляется:
```ansible-playbook -i ./hosts ./user_su.yml -K```
