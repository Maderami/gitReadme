[К содержанию](./README.md)
## Описание команды git commit

---

## Краткий обзор команды
```bash=git
git commit [-a | --interactive | --patch] [-s] [-v] [-u<mode>] [--amend]
	   [--dry-run] [(-c | -C | --squash) <commit> | --fixup [(amend|reword):]<commit>)]
	   [-F <file> | -m <msg>] [--reset-author] [--allow-empty]
	   [--allow-empty-message] [--no-verify] [-e] [--author=<author>]
	   [--date=<date>] [--cleanup=<mode>] [--[no-]status]
	   [-i | -o] [--pathspec-from-file=<file> [--pathspec-file-nul]]
	   [(--trailer <token>[(=|:)<value>])…​] [-S[<keyid>]]
	   [--] [<pathspec>…​]
```

Основные опции, используемые с git commit:
*  -m:<br>
    Оставление корроткого комментария для отправляеммых изменний.
*  -e:<br>
    Позволяет производить расширенное создание комментария для отправляемых изменений.
### Список основных команд git commit

```git commit -m *[text message for send]``` - переходит удаленный или локальный реозиторий и клонирует его путем скачивания всех файлов.


 