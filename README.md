### JSON
 1. Создать внешний репозиторий c названием JSON.
 * открыть https://github.com. Залогиниться. Нажать кнопку `New`.
 * в  `Repository name` ввести JSON, выбрать `Public` и `Add README file`.
 * нажать `Create repository`.
 2. Клонировать репозиторий JSON на локальный компьютер.
 * нажать `code` и копировать `ssh`
 * `git clone [ssh]`
 3. Внутри локального JSON создать файл “new.json”.
 * `touch new.json `
 4. Добавить файл под гит.
 * `git add new.json`
 5. Закоммитить файл.
 * `git commit -m 'initial commit'`
 6. Отправить файл на внешний GitHub репозиторий.
 * `git push`
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 * `vim new.json`
 * `insert`
 ```json
 {
"full_name" : "Aleksey Borsuk",
"age" : 24,
"pets" : [{
		"name":"Caesar"},
		{"age" : 1.5},
		{"animal_type" : "cat"},
		{"breed" : "british"
}],
"desired_salary" : "1000$"
}
 ```
* `Esc`
* `:wq` 
 8. Отправить изменения на внешний репозиторий.
 * `git add`,`git push`
 9. Создать файл preferences.json
 * `touch preferences.json`
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
 * `vim preferences.json`
 * `insert`
 ```json
 {"favourites" : [
{"favourite_film": "Inception"},
{"favourite_series":"Killing"},
{"favourite_food":"draniki"},
{"favourite_season":"spring"},
{"desired_country":"Turkey"}
]}
 ```
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 * `cat > skills.json`
 ```json
 {
"skills": [
	"software testing basic theory",
	"сlient–server model",
	"HTTP server request methods",
	"HTTP server response methods",
	"HTTP request and response structures",
	"JSON nad XML structure",
	"API testing via Postman (JS, autotests API)",
	"Getting and reading logs from an external server",
	"Sniffing http web traffic via Charles and Fiddler",
	"VPN. How to work with it, why we need it, how to use, tools",
	"Mobile testing",
	"IOS, Android, guidelines",
	"Building IOS apps via Xcode",
	"Building Android apps via Android Studio",
	"ADB of android devices",
	"Setting up proxy and VPN on IOS and Android",
	"Sniffing of mobile traffic via Charles and Fiddler",
	"Terminal Linux. Basic commands",
	"Basic of bash scripting. Automation of routine tasks",
	"Access to remote servers",
	"SQL basic commands: Create,Delete, Drop,Insert Into, Select",
	"Postgres installation, configuration and usage",
	"Non-relational DB Redis installation, configuration and usage",
	"Load testing in Jmeter",
	"Scrum development methodology",
	"Python basics. Building a client-server app"
	]
}
 ```
 12. Отправить сразу 2 файла на внешний репозиторий.
 * `git add .`, `git commit -m 'add code'`, `git push`
 13. На веб интерфейсе создать файл bug_report.json.
 * Зайти в нужную папку на `github.com`
 * Нажать `Add file`
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 * Пролистать ниже и нажать `Commit changes`
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 * Зайти в нужный файл на `github.com`
 * Нажать `Edit`
 * Написать пример баг-репорта в формате `JSON`
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 * Нажать `Commit changes`
 17. Синхронизировать внешний и локальный репозиторий JSON
 * `git pull`
 
### XML
 1. Создать внешний репозиторий c названием XML.
 2. Клонировать репозиторий XML на локальный компьютер.
 3. Внутри локального XML создать файл “new.xml”.
 4. Добавить файл под гит.
 5. Закоммитить файл.
 6. Отправить файл на внешний GitHub репозиторий.
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
 8. Отправить изменения на внешний репозиторий.
 9. Создать файл preferences.xml
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 12. Сделать коммит в одну строку.
 13. Отправить сразу 2 файла на внешний репозиторий.
 14. На веб интерфейсе создать файл bug_report.xml.
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий XML

### TXT
 1. Создать внешний репозиторий c названием TXT.
 2. Клонировать репозиторий TXT на локальный компьютер.
 3. Внутри локального TXT создать файл “new.txt”.
 4. Добавить файл под гит.
 5. Закоммитить файл.
 6. Отправить файл на внешний GitHub репозиторий.
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 8. Отправить изменения на внешний репозиторий.
 9. Создать файл preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 12. Сделать коммит в одну строку.
 13. Отправить сразу 2 файла на внешний репозиторий.
 14. На веб интерфейсе создать файл bug_report.txt.
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий TXT