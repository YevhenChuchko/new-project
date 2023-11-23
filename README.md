# new-project
Створіть аккаунт на github.com

Створіть новий репозиторій з назвою 'new-project' 
    (при створенні репозиторію можна тут же створити файл README.md)

Перейдіть до каталогу "new-project".

Ініціалізуйте новий публічний Git-репозиторій всередині каталогу "new-project". 
    Сайт запропонує це зробити 

Встановіть GIT на свій ПК. (Посиллання на сайт https://git-scm.com/)

Відкрийте свій VS Code, та перейдіть на вкладку для роботи з GIT (Ctrl+Shift+G)

Відкрийте термінал та склонуйте з github.com свій репозиторій:
    git clone https://github.com/ВАШЕ ІМ'Я/new-project.git 
    (посилання на репозиторій можна знайти нажавши на зелену кнопку "Code" у вкладці HTTPS)

Відкрийте файл README.md у Вашому VS Code та додайте текст. 

Підготовка файлу "README.md" до коміту:
    git add README.md

Закомітіть зміни із повідомленням "init":
    git commit -m "init"


Створення та перехід до гілки "development":  
    git checkout -b development

Додавання інструкції до файлу "README.md":
Відкрийте файл "README.md" у вашому редакторі та додайте інструкції. Потім збережіть файл.
Додавання змін до зони індекса: 
    git add README.md

Закомітіть зміни у гілці "development":
    git commit -m "Додано інструкції у файл README.md"


Перехід до гілки "main":
    git checkout main

Об'єднання змін з гілки "development" у гілку "main":
    git merge development


Перевірка статусу:
    git status


Закомітіть об'єднані зміни:
    git commit -m "Об'єднано зміни з гілки development у гілку main"


Тепер ви можете залити ці зміни на GitHub за допомогою команди git push
    git push origin main

