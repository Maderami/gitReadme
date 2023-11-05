[К содержанию](./README.md)
## Описание команды git clone

---

## Краткий обзор команды
```bash=git
git clone [--template=<template-directory>]
	  [-l] [-s] [--no-hardlinks] [-q] [-n] [--bare] [--mirror]
	  [-o <name>] [-b <name>] [-u <upload-pack>] [--reference <repository>]
	  [--dissociate] [--separate-git-dir <git-dir>]
	  [--depth <depth>] [--[no-]single-branch] [--no-tags]
	  [--recurse-submodules[=<pathspec>]] [--[no-]shallow-submodules]
	  [--[no-]remote-submodules] [--jobs <n>] [--sparse] [--[no-]reject-shallow]
	  [--filter=<filter> [--also-filter-submodules]] [--] <repository>
	  [<directory>]
```

Основные опции, используемые с git clone:
*  -l, --local:<br>
    Когда репозиторий для клонирования находится на локальном компьютере, этот флаг обходит обычный транспортный механизм "Git aware" и клонирует репозиторий, создавая копию HEAD и всего остального в каталогах objects и refs.
*  --progress:
    Собщаетс в терминале, в стандартной форме о состоянии происходящего при клонировании репозитория.
*  --origin:
    Производит переопределение удаленного имени в конфигурации
### Список основных команд git clone

```**git clone *[name url path]***``` - переходит удаленный или локальный реозиторий и клонирует его путем скачивания всех файлов.


 