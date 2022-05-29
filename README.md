# JSON
4. Создать внешний репозиторий c названием JSON.
```bash
Repositories --> New --> Repos Name:JSON --> Check "Add a README file" --> Press "Create repository"
```

5. Клонировать репозиторий JSON на локальный компьютер.

```bash
git clone   <copy repository HTTPS>
```
6. Внутри локального JSON создать файл “new.json”.

```bash
touch new.json
```
7. Добавить файл под гит.

```bash
git add new.json
```
8. Закоммитить файл.

```bash
git commit -m "the first file json"
```
9. Отправить файл на внешний GitHub репозиторий.
```bash
git push
```

10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в    формате JSON.

```bash
 cat > new.json  --->  ^C
 
 or
 
vim new.json    ---> input data ---> esc ---> enter ":wq"
```
```bash
#"for example"
{
	"Full Name": "Bragin Andrei Aleksandrovich" ,
	"Age": 47 ,
	"Number of pets": 1 ,
	"Salary": "1000$"
}
```
11. Отправить изменения на внешний репозиторий.
```bash
git commit -am "add name age and etc" && git push
```

12. Создать файл preferences.json
```bash
touch preferences.json
```

13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы        посетить) в формате JSON.
```bash
cat > preferences.json  --->  ^C
or
vim preferences.json ---> insert data ---> esc ---> enter ":wq"
```
```bash
#"for example"
{
	"favorite_movie": " The Predator",
	"favorite_series": "House M.D.",
	"favorite_food": "Basmati rice",
	"favorite_time_of_the_year": "summer",
	"country_you_would_like_to_visit": "The Hawaiian Islands US"
}
```

14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

```bash
touch skills.json
```
```bash
#"for example"
{
	"Skill1":"Testing Theory, SDLC, STLC",
	"Skill2":"Clien-server",
	"Skill3":"HTTP-methods",
	"Skill4":"HTTP status-codes",
	"Skill5":"HTTP resp, req stracture",
	"Skill6":"JSON, XML. Structure",
	"Skill7":"API Postman (JS, autotest API).",
	"Skill8":"Logs from servers",
	"Skill9":"Charles and Fiddler.",
	"Skill10":"Dev Tools(Google Chrome, FireFox).",
	"Skill11":"VPN.",
	"Skill12":"Mobile testing",
	"Skill13":"IOS, android guidelines",
	"Skill14":"XCode.",
	"Skill15":"Android Studio.",
	"Skill16":"ADB",
	"Skill17":"iOS Android proxy, vpn",
	"Skill18":"Mobile trafic sniffing. Charles and Fiddler iOS, Android.",
	"Skill19":"terminal Linux",
	"Skill20":"bash scripting",
	"Skill21":"Remote servers access",
	"Skill22":"SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).",
	"Skill23":"DB Postgres.",
	"Skill24":"Redis",
	"Skill25":"Load testing Jmeter.",
	"Skill26":"Scrum.",
	"Skill27":"Python."
}
or 
{
	"skills":[
	"Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.",
	"Что такое клиент-серверная архитектура.",
	"HTTP Методы запросов на сервер.",
	"Коды ответов HTTP сервера.",
	"Структуры HTTP запросов и ответов.",
	"Что такое JSON, XML. Их структура.",
	"Тестирование API через Postman (JS, автотесты API).",
	"Снятие и чтение логов c внешнего сервера.",
	"Снифинг http web трафика через Charles и Fiddler.",
	"Dev Tools веб браузеров (Google Chrome, FireFox).",
	"VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
	"Мобильное тестирование.",
	"Особенность iOS, Android, гайдлайны.",
	"Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)",
	"Сборка Android приложений на Android Studio.",
	"ADB (управление андройд девайсами).",
	"Настройка прокси и vpn на iOS и Android.",
	"Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.",
	"Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
	"Основы bash скриптинг, автоматизация рутинных задач на сервере.",
	"Доступ к удалённым серверам.",
	"Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).",
	"База данных Postgres (установка, настройка и использование).",
	"Нереляционная база данных Redis (установка, настройка и использование).",
	"Нагрузочное тестирование в Jmeter.",
	"Методология разработки Scrum.",
	"Python. (Изучение основ. Создание клиент серверного приложения)"
	]
}
```
15. Отправить сразу 2 файла на внешний репозиторий.
```bash
git add . && git commit -m "add 2 file" && git push
```

16. На веб интерфейсе создать файл bug_report.json.

```bash
Add file --> Create new file --> Name: bug_report.json
```
```bash
#"for example"
{
  "Environment":"<Description of environment>",
  "ID":1 ,
  "Summary":"<What?Where?Why?>",
  "STR":{
          "Step1":"<step description>",
          "Step2":"<step description>"          
        },
        "version","<Number version>",
  "Severity":"<Can be categorized into four parts>",
  "Priority":"<Can be categorized into three parts>",
  "Expected Result":"<Description of expected result>",
  "Actual Result":"<Description of actual result>",
  "Attachments":"<link>"
}
```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit New File
```

18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
```bash
 Choose bug_report.json --> Edit this file
```

19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
Commit changes
```

20. Синхронизировать внешний и локальный репозиторий JSON
```bash
git pull
```
___

## Видео по вышеуказанному заданию можно посмотреть [здесь](https://youtu.be/K3hRT06ROgY)
___
