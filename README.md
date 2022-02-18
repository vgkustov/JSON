# JSON

## Homework for git part 1

1. Создать внешний репозиторий c названием JSON.

> git-> repositories-> add. Называем репозиторий, добавляем README.md

2. Клонировать репозиторий JSON на локальный компьютер.

> Репозиторий "JSON", -> Code -> копируем ссылку на репозиторий
  > git clone ссылка на репозиторий

3. Внутри локального JSON создать файл “new.json”.

> touch next.json

4. Добавить файл под гит.

> git add next.json

5. Закоммитить файл.

> git commit -m "пояснение к коммиту"

6. Отправить файл на внешний GitHub репозиторий.

> git push

7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

> vim new.json -> внесение нужной информации

8. Отправить изменения на внешний репозиторий.

> git add new.json, git commit -m "пояснение", git push

9. Создать файл preferences.json

> vim preferences.json

10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

> в vim -> i -> внеение необхдимых данных -> :wq

11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

> vim skills.json -> i -> вносим необходимые данные -> :wq

12. Сделать коммит в одну строку.

> git add . ; git commit

13. Отправить сразу 2 файла на внешний репозиторий.

> git push

14. На веб интерфейсе создать файл bug_report.json.

> Add File -> Create new file -> bug_report.json

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

> Commit changes

16. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

> edit this file -> вносим необходимые данные

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

> Commit changes

18. Синхронизировать внешний и локальный репозиторий JSON

> git pull
