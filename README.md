__TXT__

1. Создать внешний репозиторий c названием TXT.

2. Клонировать репозиторий TXT на локальный компьютер.
    - git clone https://github.com/tityuliya/TXT.git

3. Внутри локального TXT создать файл “new.txt”.
    - cd TXT
    - vim new.txt

4. Добавить файл под гит.
    - git add new.txt

5. Закоммитить файл.
    - git commit -m "add new.txt"

6. Отправить файл на внешний GitHub репозиторий.
    - git push

7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

8. Отправить изменения на внешний репозиторий.
    - git commit -am "change new.txt"
    - git push

9. Создать файл preferences.txt
    - vim preferences.txt

10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
    - vim skills.txt

12. Сделать коммит в одну строку.
    - git add . | git commit -m "add files preferences and skills"
    или
    - git add . ; git commit -m "add files preferences and skills"
    или
    - git add . && git commit -m "add files preferences and skills"

13. Отправить сразу 2 файла на внешний репозиторий.
    - git push

14. На веб интерфейсе создать файл bug_report.txt.

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

18. Синхронизировать внешний и локальный репозиторий TXT
    - git pull
