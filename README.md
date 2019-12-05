# Что такое Git

**Git (version control system)** — система контроля версий. Программа позволяющая сохранять,
изменять и отслеживать различные версии файлов проекта. Работает по принципу чекпоинтов -
контрольных точек, в которых сохраняется состояние файлов.

## Установка Git

Заходим по ссылке [https://git-scm.com/downloads](https://git-scm.com/downloads), скачиваем и устанавливаем версию для своей
  операционной системы.

После завершения установки, открываем любой терминал. Пользователям Windows
рекомендуется использовать оболочку Git Bash, которая у них будет установлена вместе с Git.
Пользователи Linux и macOS могут использовать стандартный терминал встроенный в их
операционные системы.

Для проверки того, что Git был успешно установлен в систему, в терминале нужно выполнить
команду git —version. Если все в порядке, будет выведена установленная версия Git.

## Команда git commit

Создает коммит, точку сохранения, запись в истории изменений. В коммит входят все
зафиксированные на текущий момент изменения отслеживаемых файлов. 

```shell
git commit -m “Мой комментарий к коммиту”

git commit —amend -m “Мой измененный комментарий к последнему коммиту”
```