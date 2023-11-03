# db-hack

Этот репозиторий нужен для работы с бд электронного дневника. Если вы попали в этот репозиторий случайно, то вы не сможете его запустить, т.к. у вас нет доступа к БД, но можете свободно использовать код вёрстки или посмотреть как реализованы запросы к БД.

### Как запустить

Для запуска кода есть 2 варианта:
    1. Скопировать код нужной вам функции в shell и запустить ее там.
    2. Положить файл с кодом рядом с manage.py и подключить через import.

Каждая функция отвечает за свое отдельное действие:

remove_chastisements(schoolkid_name) отвечает за удаление замечаний отдельного ученика. Для запуска запустите команду:
```
remove_chastisements(schoolkid_name)
```


fix_marks(schoolkid_name) отвечает за изменение плохих оценок на хорошие для отдельного ученика. Для запуска запустите команду:
```
fix_marks(schoolkid_name)
```

create_commendation(schoolkid_name, subject) отвечает за добавления похвалы для отдельного ученика на отдельный предмет. Для запуска запустите команду:
```
create_commendation(schoolkid_name, subject)
```

Где schoolkid_name - Имя нужного вам ученика, subject - нужный вам предмет