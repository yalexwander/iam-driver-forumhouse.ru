## Инфо

Драйвер ItIsAllMail для forumhouse.ru.

## Установка:

1) Установить ItIsAllMail.
2) Установить драйвер.

    cd lib/ItIsAllMail/Driver/
    git clone https://github.com/yalexwander/iam-driver-forumhouse.ru forumhouse.ru

3) Включить драйвер в конфигурации ItIsAllMail в `conf/config.yml`:

```
drivers :
  - "forumhouse.ru"
```

4) Добавить source в `conf/sources.yml`:

```
- url: https://www.forumhouse.ru/threads/536095/
  mailbox_base_dir: /tmp
  mailbox: mailbox_lor
```

