# План автоматизации тестирования возможности записи на обучение профессии "Тестировщик ПО"
## Содержание:
1. Перечень автоматизируемых сценариев
2. Перечень используемых инструментов с обоснованием выбора
3. Перечень необходимых разрешений/данных/доступов
4. Перечень и описание возможных рисков при автоматизации
5. Перечень необходимых специалистов для автоматизации
6. Интервальная оценка с учётом рисков (в часах)


## Перечень автоматизируемых сценариев

1. **Сценарии перехода на страницу курса "Тестировщик ПО" (далее - Страница)**

    1.1. Переход на Страницу через "Каталог курсов":
    - Зайти на [главную страницу](https://netology.ru/) Нетологии;
    - Нажать на [Каталог курсов](https://github.com/Purpurova-k/TestPlan/blob/905a329fc6bfe06fdcdf0464b2c034cf99f060c9/screenshots/KatalogKursov.png), размещенный в верхней части Страницы;
    - Навести курсор на направление [Программирование](https://github.com/Purpurova-k/TestPlan/blob/905a329fc6bfe06fdcdf0464b2c034cf99f060c9/screenshots/KatalogKursov2.png);
    - Выбрать курс [Тестировщик ПО](https://github.com/Purpurova-k/TestPlan/blob/905a329fc6bfe06fdcdf0464b2c034cf99f060c9/screenshots/KatalogKursov3.png) из списка "Для начинающих".

    1.2. Переход на Страницу через "Направления обучения":
    - Зайти на [главную страницу](https://netology.ru/) Нетологии;
    - Найти на главной странице блок "Направления обучения" и выбрать [Программирование](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/NapravleniyaObucheniya.png);
    - Выбрать курс [Тестировщик ПО](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/NapravleniyaObucheniya2.png).

    1.3. Переход на Страницу через "Выберите вектор развития":
    - Зайти на [главную страницу](https://netology.ru/) Нетологии;
    - Найти на главной странице блок "Выберете вектор развития" и нажать на [Выбрать курс](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/VectorRazvitiya.png);
    - В левой части открывшейся страницы в блоке [Направления](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/VectorRazvitiya1.png) поставить галочку напротив направления "Программирование";
    - Выбрать курс [Тестировщик ПО](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/VectorRazvitiya2.png).

    1.4. Переход на Страницу через поиск в блоке "Выберите вектор развития":
    - Зайти на [главную страницу](https://netology.ru/) Нетологии;
    - Найти на главной странице блок "Выберете вектор развития" и нажать на [Выбрать курс](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/VectorRazvitiya.png);
    - В строке поиска ввести "Тестировщик ПО" и выбрать курс [Тестировщик ПО](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/Poisk2.png).

    1.5. Переход на Страницу через футер(footer):
    - Зайти на [главную страницу](https://netology.ru/) Нетологии;
    - Проскроллить в самый низ главной страницы до футера и выбрать [Программирование](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/Footer.png) в блоке "Обучение";
    - Выбрать курс [Тестировщик ПО](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/Footer2.png).


2. **Сценарии перехода к форме записи на курс "Тестировщик ПО"**

    2.1. На странице [Тестировщик](https://netology.ru/programs/qa) нажать на кнопку [Записаться](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/Zapisatsa.png). Будет осуществлен переход к форме записи в самом низу страницы.
    2.2. На странице [Тестировщик](https://netology.ru/programs/qa) проскроллить вниз, сверху появится кнопка [Записаться](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/Zapisatsa2.png), нажать на нее. Будет осуществлен переход к форме записи в самом низу страницы.
    2.3. На странице [Тестировщик](https://netology.ru/programs/qa) проскроллить в самый низ страницы, где расположена [форма записи](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/Zapisatsa3.png).

3. **Сценарии заполнения и отправки формы записи на курс "Тестировщик ПО"**
Форма содержит поля **Имя**, **Телефон**, **Электронная почта**, а также кнопки **Записаться** и **Получить консультацию**. Все поля обязательны к заполнению. [Форма записи](https://github.com/Purpurova-k/TestPlan/blob/739384a5b140af3a9516545d88b82435ff5aab1f/screenshots/Zapisatsa3.png)
    3.1. Позитивные сценарии: заполняем соответствующие поля формы 

    *Позитивные сценарии проверки поля Имя*

    - Валидное имя; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Имя, состоящее из 1 буквы; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Сложное имя через дефис; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Сложное имя через пробел; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Пробел перед именем, валидное имя; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Имя, содержащее букву ё; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Имя в нижнем регистре; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Имя в верхнем регистре; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru

    *Позитивные сценарии проверки поля Телефон*

    - Валидное имя; телефон в формате 8(999)999-99-99; валидная почта в формате example@mail.ru
    - Валидное имя; телефон в формате 89999999999; валидная почта в формате example@mail.ru
    - Валидное имя; телефон в формате +79999999999; валидная почта в формате example@mail.ru

    *Позитивные сценарии проверки поля Электронная почта*

    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта, содержащая цифры в имени аккаунта в формате example123@mail.ru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта, содержащая дефис в имени аккаунта в формате example-example@mail.ru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта, содержащая нижнее подчеркивание в имени аккаунта в формате example_example@mail.ru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта, содержащая точку в имени аккаунта в формате example.example@mail.ru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта, содержащая пробел вначале в формате " example.@mail.ru"
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта, содержащая цифры, дефис, нижнее подчеркивание в доменной части в формате example@ex.ample-ex_123.ru

    3.2. Негативные сценарии: заполняем соответствующие поля формы 

    *Негативные сценарии проверки поля Имя*

    - Имя, содержащее цифры; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Имя на латинице; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Имя, содержащее спецсимволы или знаки препинания; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Пустое поле имени; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Пробел в поле имени; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru
    - Имя, превыщающее допустимое количество символов; телефон в формате +7 (999) 999-99-99; валидная почта в формате example@mail.ru

    *Негативные сценарии проверки поля Телефон*

    - Валидное имя; телефон, содержащий буквы; валидная почта в формате example@mail.ru
    - Валидное имя; телефон, содержащий прочие спецсимволы (все, кроме кргулых скобок, знак плюс и дефис); валидная почта в формате example@mail.ru
    - Валидное имя; телефон, содержащий меньше 11 цифр; валидная почта в формате example@mail.ru
    - Валидное имя; телефон, содержащий больше 11 цифр; валидная почта в формате example@mail.ru
    - Валидное имя; пробел в поле телефон; валидная почта в формате example@mail.ru
    - Валидное имя; пустое поле телефон; валидная почта в формате example@mail.ru

    *Негативные сценарии проверки поля Электронная почта*

    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта, содержащая кириллицу в формате пример@mail.ru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта, содержащая прочие спецсимволами в имени акккаунта или в доменной части (все, кроме цифр, дефиса, знак подчеркивания, точка) в формате example?example@mail.ru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта без точек в доменной части в формате example@mailru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта без @ в доменной части в формате examplemail.ru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта, превыщающая допустимое количество символов
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта с пробелами в имени аккаунта в формате ex ample@mail.ru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта с пробелами в доменной части в формате example@ma il.ru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта без имени аккаунта в формате @mail.ru
    - Валидное имя; телефон в формате +7 (999) 999-99-99; почта без доменной части в формате example

    **Итого**: для проверки сценариев перехода на страницу курса "Тестировщик ПО" потребуется 5 автотестов, для проверки сценариев перехода к форме записи на курс "Тестировщик ПО" - 3 автотеста, для проверки как позитивных, так и негативных сценариев заполнения и отправки формы записи на курс "Тестировщик ПО" - 38 автотестов (при необходимости проверить каждый недопустимый спецсимвол в соответствующих полях это количество может еще увеличиться). 


## Перечень используемых инструментов с обоснованием выбора
- Java 11 - язык программирования для написания автотестов
- IntelliJ IDEA - интегрированная среда разработки, подходит для Java
- Gradle - система автоматической сборки
- Appveyor - распределенный веб-сервис непрерывной интеграции, предназначенный для сборки и тестирования программного обеспечения
- Git - распределенная система управления версиями
- GitHub - сервис для хранения кода
- Allure - фреймворк, предназначенный для создания визуально наглядной картины выполнения тестов
- JUnit5 - фреймворк, предназначенный для тестирования ПО
- Selenide - библиотека, предназначенная для UI тестирования веб-приложений
- Faker - библиотека для генерации фейковых данных
- Lombok - библиотека для автоматической генерации кода
- Docker+Docker-compose - система контейнеризации, необходимо для подключения к базе данных
- SQL - язык программирования для работы с базой данных
- Apache Commons DbUtils - набор классов, которые позволят проще работать с JDBC
- DBeaver - десктопное приложение для работы с базой данных
- HTML - язык разметки документов для просмотра веб-страниц в браузере, необходим для понимания структуры веб-страницы и написания локаторов для элементов страницы


## Перечень необходимых разрешений/данных/доступов
- Разрешение от ООО "Нетология" на проведение автотестов на сайте https://netology.ru/
- Доступ к API сайта
- Доступ к базе данных, куда поступают сведения о записанных на курс
- Техническое задание и иная докусентация с требованиями


## Перечень и описание возможных рисков при автоматизации
1. При изменении элементов на сайте, придется переписывать локаторы в автотестах, а то и вовсе полностью переписывать некоторые тесты
2. Невозможно автоматизировать все негативные сценарии, пользователь может повести себя непредсказуемо
3. Увеличение нагрузки на сервера и БД
4. Автоматизация с нуля может привести к гораздо большему расходу времени для подготовки всех необходимых инструментов тестирования
5. Разработчики могут отказаться фиксить маленькие баги, в таком случае полная автоматизация была не нужна
6. Если в команде нет тестировщиков с необходимыми знаниями для автоматизации, то необходимо привлечение новых сотрудников или обучение уже имеющихся, оба варианта предполагают увеличение затрат и времязатратность


## Перечень необходимых специалистов для автоматизации
- Инженер по автоматизированному тестированию, который владеет всем перечнем инструментов тестирования. Это может быть инженер без опыта, а также инженер с опытом автоматизированного тестирования около 1 года.


## Интервальная оценка с учётом рисков (в часах)
Необходимое время для автоматизации тестирования возможности записи на обучение профессии "Тестировщик ПО" - 80 часов (или 10 рабочих дней). В это время входит анализ документации и требований, получение всех разрешений, подключение всех необходимых инструментов, подключение к БД, написание автотестов, необходимая правка, написание сопутствующей документации (тест-план, тест-кейсы/чек-листы, при необходимости баг-репорты, отчет о тестировании).






