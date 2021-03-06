## Workflow работы с github

Каждый студент делает [fork](https://help.github.com/articles/fork-a-repo) репозитория ```fizteh-java-2014```. Работа
ведётся в собственном репозитории, в директории ```src/ru/fizteh/fivt/students/<name>/<task>```.

После того, как задание выполнено и протестировано в собственном репозитории, необходимо создать
[pull request](https://help.github.com/articles/using-pull-requests) в репозиторий ```fizteh-java-2014```. В заголовке
к pull request необходимо написать: ```Имя Фамилия, № группы, задание``` (например, ```Василий Иванов, 123, Shell```).
Также необходимо назначить pull request на своего семинариста.

В одном pull request должно быть решение только одной задачи. Если хочется сдавать параллельно несколько заданий,
необходимо создавать бранчи и делать pull request из бранчей.

Чтобы сократить количество итераций на проверку задания, полезно самостоятельно удостовериться, что Code Conventions
соблюдены. Для этого нужно запустить сборку проекта с помощью ```ant checkstyle```. Вместо этого можно поставить
соответствующий плагин в IDE и настроить этот плагин на конфигурационный файл ```bin/checkstyle-rules.xml```.
