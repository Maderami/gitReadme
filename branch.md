[К содержанию](./README.md)
## Описание команды git branch

---

## Краткий обзор команды
```bash=git
git branch [--color[=<when>] | --no-color] [--show-current]
	[-v [--abbrev=<n> | --no-abbrev]]
	[--column[=<options>] | --no-column] [--sort=<key>]
	[--merged [<commit>]] [--no-merged [<commit>]]
	[--contains [<commit>]] [--no-contains [<commit>]]
	[--points-at <object>] [--format=<format>]
	[(-r | --remotes) | (-a | --all)]
	[--list] [<pattern>…​]
git branch [--track[=(direct|inherit)] | --no-track] [-f]
	[--recurse-submodules] <branchname> [<start-point>]
git branch (--set-upstream-to=<upstream> | -u <upstream>) [<branchname>]
git branch --unset-upstream [<branchname>]
git branch (-m | -M) [<oldbranch>] <newbranch>
git branch (-c | -C) [<oldbranch>] <newbranch>
git branch (-d | -D) [-r] <branchname>…​
git branch --edit-description [<branchname>]
```

Основные опции, используемые с git branch:
*  -d, --delete:<br>
    Удаляе ветку. Ветвь должна быть полностью объединена в своей восходящей ветви или в HEAD, если восходящий поток не был установлен с помощью --track или --set-upstream-to.
*  -c, --copy:<br>
    Скопирует ветку вместе с ее конфигурацией и рефлогом.
*  --a, --all:<br>
    Позволяет покзать в виде списка как удаленного ветки, так и локальные. Часто комбинируется с --list

### Список основных команд git branch

```**git branch *[name branch]***``` - переходит и сразу создает новую ветку.


 