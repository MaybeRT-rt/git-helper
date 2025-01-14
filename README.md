# git-helper

Инициализирует новый Git-репозиторий в текущей директории.

```sh

git init	

```

Клонирует удалённый репозиторий в локальную директорию.

```sh
git clone <url>

```

Показывает текущее состояние рабочего дерева (что изменено, что готово к коммиту и т.д.).

```sh

git status

```

Фиксирует изменения в репозитории с сообщением о том, что было сделано.
```sh

git commit -m "Сообщение коммита"

```

Создаёт новую ветку.


```sh

git branch <branch_name>

```


Переключает текущую ветку на другую.

```sh

git checkout <branch_name>

```

Сливает указанную ветку с текущей.

```sh
git merge <branch_name>
```


Отправляет локальные изменения в удалённый репозиторий.


```sh
git push origin <branch_name>

```

Забирает последние изменения с удалённого репозитория и сливает с текущей веткой.

```sh
git pull origin <branch_name>

```
