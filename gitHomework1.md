GIT Homework 1

Для выполнения задания у вас должен быть установлен для Windows - GitBash.
Создан аккаунт в GitHub

Все шаги сценария выполняйте в терминале GitBush, Terminal, в папке под гитом.


JSON
 4. Создать внешний репозиторий c названием JSON.

https://github.com/new -> Enter Repository name "JSON" -> Create repository 

 5. Клонировать репозиторий JSON на локальный компьютер.

git clone https://github.com/quazarchick/JSON.git

 6. Внутри локального JSON создать файл “new.json”.

cd JSON
touch new.json



 7. Добавить файл под гит.

$ git add new.json


 8. Закоммитить файл.

$ git commit -m "add new json file"

 9. Отправить файл на внешний GitHub репозиторий.

$ git push

 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

nano new.json

Add json: 

{
    "human": {
        "name": "Vladimir T",
        "age": 30,
        "numberOfPets": 1,
        "desiredSalary": 1000000
    }
}

Ctrl + X
Y

 11. Отправить изменения на внешний репозиторий.

$ git commit -m "add json data"
$ git push

 12. Создать файл preferences.json

$ touch preferences.json
$ git add preferences.json


 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

$ nano preferences.json

Add json:

{
    "preferences": {
        "favoriteMovie": "Stalker",
        "favoriteSeries": "The Sopranos",
        "favoriteFood": "club sandwich",
        "favoriteSeason": "summer",
        "countryLikeToVisit": "Portugal"
    }
}

Ctrl + X
Y


 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

$ touch skills.json
$ git add skills.json
$ nano skills.json


Add json:

{
    "skills": {
        "1": "Terminal Linux",
        "2": "SQL",
        "3": "Git",
        "4": "Postman",
        "5": "Client-server architecture",
        "6": "Mobile testing"
    }
}

Ctrl + X
Y


 15. Отправить сразу 2 файла на внешний репозиторий.

$ git commit -m "new files"
$ git push


 16. На веб интерфейсе создать файл bug_report.json.

Repositories - JSON -> Add file -> Create new file -> name new file -> bug_report.json -> Commit changes

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Commit changes

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

 bug_report.json -> edit this fire

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Commit changes

 20. Синхронизировать внешний и локальный репозиторий JSON

git pull

XML
 21. Создать внешний репозиторий c названием XML.

https://github.com/new -> Enter Repository name "XML" -> Create repository 

 22. Клонировать репозиторий XML на локальный компьютер.

$ git clone https://github.com/quazarchick/XML.git

 23. Внутри локального XML создать файл “new.xml”.

$ touch new.xml

 24. Добавить файл под гит.

$ git add new.xml

 25. Закоммитить файл.

$ git commit -m "new xml"

 26. Отправить файл на внешний GitHub репозиторий.

$ git push

 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

$ nano new.xml

 28. Отправить изменения на внешний репозиторий.

$ git commit -m "new changes"
$ git push


 29. Создать файл preferences.xml

$ touch preferences.xml


 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

$ nano preferences.xml

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

$ touch skills.xml
$ nano skills.xml

 32. Сделать коммит в одну строку.

 $ git add .&& git commit -m "one string"

 33. Отправить сразу 2 файла на внешний репозиторий.

$ git push


 34. На веб интерфейсе создать файл bug_report.xml.

Repositories - XML -> Add file -> Create new file -> name new file -> bug_report.xml -> Commit changes


 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Commit changes

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

Edit this file

Add XML

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Commit changes

 38. Синхронизировать внешний и локальный репозиторий XML

 git pull

TXT

1. Создать внешний репозиторий c названием TXT.

https://github.com/new -> Enter Repository name "TXT" -> Create repository 

 2. Клонировать репозиторий TXT на локальный компьютер.

$ git clone https://github.com/quazarchick/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.

$ cd TXT
$ touch new.txt

 4. Добавить файл под гит.

$ git add new.txt

 5. Закоммитить файл.

$ git commit -m "new text file"

 6. Отправить файл на внешний GitHub репозиторий.

$ git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

$ nano new.txt


 8. Отправить изменения на внешний репозиторий.

$ git commit -m "update"
$ git push

 9. Создать файл preferences.txt

$ touch preferences.txt


 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

$ nano preferences.txt
add info
ctrl+x
y

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

$ touch skills.txt

 12. Сделать коммит в одну строку.

$ git add .&& git commit -m "upd"

 13. Отправить сразу 2 файла на внешний репозиторий.

 $ git push

 14. На веб интерфейсе создать файл bug_report.txt.

Repositories - TXT -> Add file -> Create new file -> name new file -> bug_report.txt -> Commit changes

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 Commit changes

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

 Edit this file

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 Commit changes

 18. Синхронизировать внешний и локальный репозиторий TXT

  git pull
