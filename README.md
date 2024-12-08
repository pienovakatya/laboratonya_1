<h1>Лабораторна робота 1: Вивчення Git</h1>

Завантаження та розпакування початкових файлів проєкту. Файл githowto.zip розміром 1 933 КБ було успішно завантажено.
<p align="center">
<img src="Screenshots/ (1).png" alt="(1)"/>
</p>

Навігація по структурі проєкту. Провідник файлів показує дві основні папки в каталозі githowto: 'files' та 'repositories', що знаходяться в папці Завантаження.
<p align="center">
<img src="Screenshots/ (2).png" alt="(2)"/>
</p>

Налаштування глобальної конфігурації Git. Встановлення імені користувача як "penovakaterina", електронної пошти як "penovakaterina@gmail.com", налаштування гілки за замовчуванням на "main" та налаштування обробки закінчень рядків за допомогою параметрів autocrlf та safecrlf.
<p align="center">
<img src="Screenshots/ (3).png" alt="(3)"/>
</p>

Створення та ініціалізація нового репозиторію Git. Створення робочого каталогу, перехід до нього, створення файлу hello.html, ініціалізація репозиторію Git та виконання першого коміту з файлом hello.html.
<p align="center">
<img src="Screenshots/ (4).png" alt="(4)"/>
</p>

Перевірка стану репозиторію. Команда git status показує, що ми знаходимось на гілці main, робоче дерево чисте і немає змін для коміту.
<p align="center">
<img src="Screenshots/ (5).png" alt="(5)"/>
</p>
Створення HTML-файлу з базовою структурою. У файлі hello.html додано заголовок першого рівня з текстом "Hello, World!".
<p align="center">
<img src="Screenshots/ (6).png" alt="(6)"/>
</p>

Перевірка стану репозиторію після змін. Git показує, що файл hello.html був модифікований, але зміни ще не додані до індексу для коміту.
<p align="center">
<img src="Screenshots/ (7).png" alt="(7)"/>
</p>

Додавання змін до індексу. Використання команди git add hello.html для підготовки змін до коміту, після чого git status показує, що файл готовий до коміту.
<p align="center">
<img src="Screenshots/ (8).png" alt="(8)"/>
</p>

Виклик команди git commit для створення нового коміту зі змінами.
<p align="center">
<img src="Screenshots/ (9).png" alt="(9)"/>
</p>

Додавання повідомлення коміту. У редакторі відкрито файл COMMIT_EDITMSG, де вказано опис змін: "Added h1 tag".
<p align="center">
<img src="Screenshots/ (10).png" alt="(10)"/>
</p>

Завершення коміту зі змінами. Коміт успішно створено з повідомленням "Added h1 tag", змінено 1 файл з 1 вставкою.
<p align="center">
<img src="Screenshots/ (11).png" alt="(11)"/>
</p>

Додавання базової структури HTML. До файлу hello.html додано основні теги html та body.
<p align="center">
<img src="Screenshots/ (12).png" alt="(12)"/>
</p>

Додавання змін до індексу за допомогою команди git add hello.html.
<p align="center">
<img src="Screenshots/ (13).png" alt="(13)"/>
</p>

Доповнення HTML-структури. До файлу додано тег head для кращої організації документа.
<p align="center">
<img src="Screenshots/ (14).png" alt="(14)"/>
</p>

Фіксація змін у репозиторії. Створено новий коміт з повідомленням "Added standard HTML page tags", який відображає 5 вставок та 1 видалення у файлі.
<p align="center">
<img src="Screenshots/ (15).png" alt="(15)"/>
</p>

Додавання та коміт HTML-заголовка. Використання git add для індексації змін та створення коміту з повідомленням "Added HTML header".
<p align="center">
<img src="Screenshots/ (16).png" alt="(16)"/>
</p>

Перегляд історії комітів за допомогою команди git log. Показано всі коміти з авторами, датами та повідомленнями.
<p align="center">
<img src="Screenshots/ (17).png" alt="(17)"/>
</p>

Використання різних форматів виведення git log. Демонстрація команд --pretty=oneline, --max-count=2, --since, --until та --author для фільтрації історії комітів.
<p align="center">
<img src="Screenshots/ (18).png" alt="(18)"/>
</p>

Налаштування формату виведення git log. Використання --pretty-format для налаштування формату виведення дати та інформації про коміти.
<p align="center">
<img src="Screenshots/ (19).png" alt="(19)"/>
</p>

Переміщення між комітами за допомогою git checkout. Перехід до початкового коміту (fbfc299) та повернення на гілку main, перевірка вмісту файлу hello.html.
<p align="center">
<img src="Screenshots/ (20).png" alt="(20)"/>
</p>

Створення та управління тегами у Git. Створено тег v1 для поточного коміту, перевірка історії комітів з тегами.
<p align="center">
<img src="Screenshots/ (21).png" alt="(21)"/>
</p>

Робота з різними версіями тегів. Використання команд checkout для переміщення між тегами v1 та v1-beta, перегляд списку наявних тегів.
<p align="center">
<img src="Screenshots/ (22).png" alt="(22)"/>
</p>

Повернення до основної гілки main за допомогою команди git switch main.
<p align="center">
<img src="Screenshots/ (23).png" alt="(23)"/>
</p>

Додавання коментаря до HTML-файлу. Доданий коментар "This is a bad comment. We want to revert it." до файлу hello.html.
<p align="center">
<img src="Screenshots/ (24).png" alt="(24)"/>
</p>

Відновлення файлу до попереднього стану. Використання команди git checkout для скасування небажаних змін у файлі hello.html.
<p align="center">
<img src="Screenshots/ (25).png" alt="(25)"/>
</p>

Додавання небажаного коментаря. У файл hello.html додано коментар "This is an unwanted but staged comment".
<p align="center">
<img src="Screenshots/ (26).png" alt="(26)"/>
</p>

Індексація змін у файлі. Використання git add для додавання змін до індексу, що підтверджується командою git status.
<p align="center">
<img src="Screenshots/ (27).png" alt="(27)"/>
</p>

Скасування проіндексованих змін. Використання команди git reset HEAD для видалення файлу з індексу та git checkout для відновлення його стану.
<p align="center">
<img src="Screenshots/ (28).png" alt="(28)"/>
</p>

Додавання нового коментаря. У файл hello.html додано коментар "This is an unwanted but committed change".
<p align="center">
<img src="Screenshots/ (29).png" alt="(29)"/>
</p>

Створення та скасування небажаного коміту. Створення коміту з повідомленням "Oops, we didn't want this commit" та його скасування за допомогою git revert.
<p align="center">
<img src="Screenshots/ (30).png" alt="(30)"/>
</p>

Перегляд історії комітів та створення тегу. Додано тег 'oops' до останнього коміту після виконання revert.
<p align="center">
<img src="Screenshots/ (31).png" alt="(31)"/>
</p>

Використання git reset --hard для повернення до попереднього стану. Команда повертає HEAD до коміту з тегом v1.
<p align="center">
<img src="Screenshots/ (32).png" alt="(32)"/>
</p>

Видалення тегу та перевірка історії. Використання команди git tag -d oops для видалення тегу та підтвердження змін через git log.
<p align="center">
<img src="Screenshots/ (33).png" alt="(33)"/>
</p>

Додавання інформації про автора. У файл hello.html додано коментар з інформацією про автора "Author: Penova Katerina".
<p align="center">
<img src="Screenshots/ (34).png" alt="(34)"/>
</p>

Створення коміту з інформацією про авторські права. Додано та закомічено зміни з повідомленням "Added copyright statement".
<p align="center">
<img src="Screenshots/ (35).png" alt="(35)"/>
</p>

Оновлення інформації про автора. Додано електронну адресу до коментаря з інформацією про автора.
<p align="center">
<img src="Screenshots/ (36).png" alt="(36)"/>
</p>

Коміт оновленої інформації про автора. Зміни збережено з повідомленням "Added copyright statement with email".
<p align="center">
<img src="Screenshots/ (37).png" alt="(37)"/>
</p>

Створення нової гілки для стилів. Використання команди git switch -c style для створення та переключення на нову гілку 'style'.
<p align="center">
<img src="Screenshots/ (38).png" alt="(38)"/>
</p>

Створення CSS-файлу. У файлі style.css визначено стиль для заголовка h1 з червоним кольором тексту.
<p align="center">
<img src="Screenshots/ (39).png" alt="(39)"/>
</p>

Збереження CSS-стилів. Додавання та коміт файлу style.css з повідомленням "Added css stylesheet".
<p align="center">
<img src="Screenshots/ (40).png" alt="(40)"/>
</p>

Підключення CSS-файлу. До файлу hello.html додано посилання на файл стилів style.css через тег link.
<p align="center">
<img src="Screenshots/ (41).png" alt="(41)"/>
</p>

Збереження змін у HTML-файлі. Коміт змін з повідомленням "Included stylesheet into hello.html".
<p align="center">
<img src="Screenshots/ (42).png" alt="(42)"/>
</p>

Перегляд історії комітів. Відображення всіх комітів з використанням команди git log --all.
<p align="center">
<img src="Screenshots/ (43).png" alt="(43)"/>
</p>

Переключення між гілками. Порівняння вмісту файлу hello.html у гілках main та style за допомогою команди git switch.
<p align="center">
<img src="Screenshots/ (44).png" alt="(44)"/>
</p>

Перегляд історії змін файлів. Використання команд git log для перегляду історії змін hello.html та style.css, а також git show v1 для перегляду змін у конкретній версії.
<p align="center">
<img src="Screenshots/ (45).png" alt="(45)"/>
</p>

Реорганізація файлової структури. Перейменування hello.html в index.html та переміщення style.css до папки css з відповідними змінами у Git.
<p align="center">
<img src="Screenshots/ (46).png" alt="(46)"/>
</p>

Створення файлу README. Додавання файлу з описом проєкту: "This is the Hello World example from the GitHowTo tutorial."
<p align="center">
<img src="Screenshots/ (47).png" alt="(47)"/>
</p>

Додавання README файлу до репозиторію. Виконання команд git add та commit для збереження файлу README.
<p align="center">
<img src="Screenshots/ (48).png" alt="(48)"/>
</p>

Візуалізація історії комітів. Використання команди git log --all --graph для відображення графу комітів та гілок.
<p align="center">
<img src="Screenshots/ (49).png" alt="(49)"/>
</p>

Об'єднання гілок. Використання git merge main для включення змін з гілки main до гілки style.
<p align="center">
<img src="Screenshots/ (50).png" alt="(50)"/>
</p>

Повернення до гілки main. Використання команди git switch main для переключення на основну гілку.
<p align="center">
<img src="Screenshots/ (51).png" alt="(51)"/>
</p>

Оновлення HTML-файлу. Додавання заголовка сторінки та нового параграфу тексту "Let's learn Git together".
<p align="center">
<img src="Screenshots/ (52).png" alt="(52)"/>
</p>

Збереження змін та перегляд історії. Створення коміту з повідомленням "Added meta title" та відображення графу комітів.
<p align="center">
<img src="Screenshots/ (53).png" alt="(53)"/>
</p>

Виникнення конфлікту злиття. При спробі об'єднати гілки виникає конфлікт у файлі index.html.
<p align="center">
<img src="Screenshots/ (54).png" alt="(54)"/>
</p>

Вирішення конфлікту злиття. Відображення конфліктних змін у файлі та можливість вибору потрібної версії.
<p align="center">
<img src="Screenshots/ (55).png" alt="(55)"/>
</p>

Скасування невдалого злиття. Використання команди git merge --abort для скасування процесу злиття та повторна спроба.
<p align="center">
<img src="Screenshots/ (56).png" alt="(56)"/>
</p>

Вирішення конфлікту злиття. Ручне редагування файлу index.html для об'єднання змін з обох гілок.
<p align="center">
<img src="Screenshots/ (57).png" alt="(57)"/>
</p>

Завершення злиття гілок. Створення коміту з повідомленням "Resolved merge conflict" після вирішення конфлікту.
<p align="center">
<img src="Screenshots/ (58).png" alt="(58)"/>
</p>

Відновлення попереднього стану. Використання git reset --hard HEAD~2 для повернення на два коміти назад.
<p align="center">
<img src="Screenshots/ (59).png" alt="(59)"/>
</p>

Спроба перебазування. Виконання команди git rebase main для перенесення змін з гілки style на основі main.
<p align="center">
<img src="Screenshots/ (60).png" alt="(60)"/>
</p>

Вирішення конфлікту під час перебазування. Редагування файлу hello.html для об'єднання змін з обох версій.
<p align="center">
<img src="Screenshots/ (61).png" alt="(61)"/>
</p>

Збереження вирішеного конфлікту. Файл hello.html після вирішення конфлікту містить всі необхідні зміни.
<p align="center">
<img src="Screenshots/ (62).png" alt="(62)"/>
</p>

Завершення перебазування. Використання git rebase --continue для завершення процесу після вирішення конфлікту.
<p align="center">
<img src="Screenshots/ (63).png" alt="(63)"/>
</p>

Об'єднання гілок після перебазування. Успішне злиття гілки style в main за допомогою git merge style.
<p align="center">
<img src="Screenshots/ (64).png" alt="(64)"/>
</p>

Клонування репозиторію. Створення локальної копії репозиторію work у новій директорії home за допомогою git clone.
<p align="center">
<img src="Screenshots/ (65).png" alt="(65)"/>
</p>

Перехід до клонованого репозиторію. Перегляд структури та історії комітів у директорії home.
<p align="center">
<img src="Screenshots/ (66).png" alt="(66)"/>
</p>

Перегляд інформації про віддалений репозиторій. Використання команд git remote та git remote show origin для отримання деталей про з'єднання.
<p align="center">
<img src="Screenshots/ (67).png" alt="(67)"/>
</p>

Перегляд поточної гілки. Команда git branch показує, що ми знаходимось на гілці main.
<p align="center">
<img src="Screenshots/ (68).png" alt="(68)"/>
</p>

Перегляд всіх гілок. Команда git branch -a показує локальні та віддалені гілки репозиторію.
<p align="center">
<img src="Screenshots/ (69).png" alt="(69)"/>
</p>

Повернення до робочого репозиторію. Використання команди cd для переходу назад до директорії work.
<p align="center">
<img src="Screenshots/ (70).png" alt="(70)"/>
</p>

Модифікація файлу README в оригінальному репозиторії. Додавання тексту "(changed in origin)" до файлу README.
<p align="center">
<img src="Screenshots/ (71).png" alt="(71)"/>
</p>

Збереження змін у файлі README. Створення коміту з повідомленням "Changed README in original repo".
<p align="center">
<img src="Screenshots/ (72).png" alt="(72)"/>
</p>

Оновлення клонованого репозиторію. Використання git fetch для отримання змін з віддаленого репозиторію та перегляд оновленої історії комітів.
<p align="center">
<img src="Screenshots/ (73).png" alt="(73)"/>
</p>

Перевірка поточного стану файлу README. Вміст файлу ще не містить останніх змін з віддаленого репозиторію.
<p align="center">
<img src="Screenshots/ (74).png" alt="(74)"/>
</p>

Об'єднання змін з віддаленого репозиторію. Використання git merge origin/main для оновлення локальних файлів та git pull для перевірки стану.
<p align="center">
<img src="Screenshots/ (75).png" alt="(75)"/>
</p>

Відстеження віддаленої гілки style. Створення локальної гілки style, що відстежує віддалену гілку origin/style.
<p align="center">
<img src="Screenshots/ (76).png" alt="(76)"/>
</p>

Створення порожнього репозиторію. Використання git clone --bare для створення репозиторію work.git без робочої копії.
<p align="center">
<img src="Screenshots/ (77).png" alt="(77)"/>
</p>

Додавання спільного репозиторію. Команда git remote add shared для додавання посилання на спільний репозиторій work.git.
<p align="center">
<img src="Screenshots/ (78).png" alt="(78)"/>
</p>

Внесення змін для спільного репозиторію. Модифікація файлу README з додаванням тексту про зміни та спільний репозиторій.
<p align="center">
<img src="Screenshots/ (79).png" alt="(79)"/>
</p>

Публікація змін у спільному репозиторії. Створення коміту та використання git push shared main для відправки змін.
<p align="center">
<img src="Screenshots/ (80).png" alt="(80)"/>
</p>

Отримання змін зі спільного репозиторію. Налаштування відстеження віддаленої гілки та отримання змін за допомогою git pull shared main.
<p align="center">
<img src="Screenshots/ (81).png" alt="(81)"/>
</p>

Запуск Git демона. Використання команди git daemon для створення серверу Git з можливістю клонування через протокол git://.
<p align="center">
<img src="Screenshots/ (82).png" alt="(82)"/>
</p>

Клонування через мережу. Створення копії репозиторію через протокол git:// з локального сервера в нову директорію network_work.
<p align="center">
<img src="Screenshots/ (83).png" alt="(83)"/>
</p>
