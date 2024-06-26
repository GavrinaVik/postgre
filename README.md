# postgre
Тестовое задание
- 1 задание
    
    Вы подключаетесь к команде разработки web интернет-магазина в роли QA инженера.
    
    Через данный сайт посетитель может:
    
    - Просматривать каталог товаров;
    - Добавлять заинтересовавшие товары в корзину;
    - Оформить заказ;
    - Выбрать способ доставки;
    - Оплатить заказ онлайн через сторонний сервис.
    
    На данный момент разрабатывается первая альфа-версия, которая будет готова через две недели. Само приложение должно быть выпущено через 3 месяца. После выпуска приложения выделяется 1 месяц на поддержку.
    
    Результатом выполнения задания должен быть отчёт/план/стратегия в свободной форме, в котором весь период разработки разбит на этапы, по пунктам описаны ваши действия на том или ином этапе. Он должен быть максимально конкретным, презентабельным и развёрнутым. Конкретные тест-кейсы приводить не нужно, но описать, как вы будете тестировать функционал - стоит. Также стоит указать сроки (понедельно), ресурсы (имеющиеся и сторонние) и способы их использования.
    
    В данном задании необходимо применить знания теории и методологии тестирования:
    
    - Пирамида тестирования
    - Виды/Типы тестирования
    - Уровни тестирования
    - Тест-дизайн
    - Тестовая документация
    - Метрики качества
    - Жизненный цикл разработки и тестирования
    - Оценка трудоемкости
    - Управление рисками
    - Анализ требований
    - Решение
        - Тест- план
            
            Жизненный цикл разработки и тестирования для создания интернет-магазина  включает следующие этапы:
            
            1. Планирование и анализ требований:
                - Определение бизнес-требований и целей интернет-магазина.
                - Сбор и анализ требований пользователей.
                - Подготовка технического задания и плана разработки.
            2. Проектирование:
                - Разработка структуры и дизайна интерфейса интернет-магазина.
                - Проектирование базы данных для хранения информации о продуктах, заказах и пользователях.
                - Определение функциональности и основных компонентов интернет-магазина.
            3. Разработка:
                - Написание и тестирование кода для реализации функциональности интернет-магазина.
                - Интеграция компонентов и модулей.
                - Развертывание и настройка серверной инфраструктуры.
            4. Тестирование:
                - Модульное тестирование отдельных компонентов и модулей.
                - Интеграционное тестирование взаимодействия между компонентами.
                - Системное тестирование функциональности, производительности, безопасности и совместимости.
                - Приемочное тестирование с участием заказчика.
            5. Внедрение и поддержка:
                - Запуск интернет-магазина и его реклама.
                - Поддержка и обновление функциональности и контента.
                - Мониторинг и анализ работы интернет-магазина для улучшения пользовательского опыта.
            
            **Следует учесть следующие риски:**
            
            Защита от кибератак и ддос атак
            
            Финансовые риски
            
            Риски с логистикой
            
            Риски репутации
            
            Юридические риски
            
            **Продукт и среда тестирования**
            
            | Среда | Продукт |
            | --- | --- |
            | веб сайт | интернет -магазин |
            | ОС | Windows 10 |
            | ПК | Huawei |
            | моб. устройство | Galaxy A53 5G |
            | версия | One UI 6.0, Android 14 |
            
            **Требования к функционалу (Анализ требований)**
            
            | № | Требование | Уточнение | Комментарий |
            | --- | --- | --- | --- |
            | 1 | Просматривать каталог товаров | Каким образом это должно быть реализовано? | Каталог будет разбит по вкладкам, блокам, дизайн макет |
            | 1.1 |  | скрол верт/гориз, табуляция, пагинация | листание страниц/картинок, переключение вкладок |
            | 1.2 |  | выпадающие списки, фильтрация, чекбоксы | необходим функционал и логика элементов |
            | 2 | Добавлять заинтересовавшие товары в корзину | Каким способом? Кнопка, перетаскивание, плюсик | будет ли оповещение в корзине или визуальное сопровождение |
            | 2.1 |  | возможность увеличить/уменьшить кол-во, удалить? | дизайн-макет, макс кол-во |
            | 2.2 |  | требуется ли авторизация? |  |
            | 3 | Оформить заказ | отдельная страница, попап с формой? | в какой момент она появляется, скрывается\нет, статична/нет |
            | 3.1 |  | какие поля? | обязательные/необязательные, макет |
            | 3.2 |  | есть возможность изменить заказ? | добавить, удалить, поменять. Запись будет сохранена или нет |
            | 3.3 |  | какие данные валидные | что происходит при невалидных данных |
            | 4 | Выбрать способ доставки | какие виды доставки осуществляет компания | самовывоз, курьер, междугородные/международные виды транспорта, почта |
            | 4.1 |  | обязательные поля | формат адреса |
            | 4.2 |  | есть ли калькулятор цены | его вид и его реализация в макете |
            | 4.3 |  | возможность менять способ доставки | происходит изменение суммы/нет |
            | 4.4 |  | доп услуги | упаковка подарочная, открытка, шарики |
            | 4.5 |  | в какой форме реализована | отдельная модалка, страничка |
            | 4.6 |  | есть ли отчет и уведомления? | если есть в какой форме, смс, звонок, пуш, ссылка |
            | 5 | Оплатить заказ онлайн через сторонний сервис | какой сервис? | какие валюты принимает, какие есть на сайте |
            | 5.1 |  | какие типы карт принимает | депозит, мастер, виза |
            | 5.2 |  | доп услуги | промокод, кредит, сертификат, скидка |
            | 5.3 |  | как осуществляется отчет об оплате | возврат, отмена, чек |
            | 5.4 |  | контроль за статусами | полностью прозрачный, ссылка на этапы заказа |
            |  |  | Какие валюты? | какие сервисы, если несколько, то какие условия и границы |
        - Тестовая документация
            
            Чек-листы:
            
            - Чек лист просматривания каталога товаров
                
                
                | № | Проверка | Ожидаемый результат | комментарии |
                | --- | --- | --- | --- |
                | 1 | Проверить наличие всех категорий товаров в каталоге. | все есть | Кол-во категории соответствует ТЗ |
                | 2 | Убедиться, что все товары имеют название и описание | все есть | Форма соответствует ТЗ |
                | 3 | Проверить наличие изображений для каждого товара | все фото загружены, открываются (увеличиваются) |  |
                | 4 | Указать цену и наличие товара на складе | есть |  |
                | 5 | Проверить правильность указания бренда и модели товара | все ок |  |
                | 6 | Убедиться, что все товары отсортированы по категориям и подкатегориям | все ок |  |
                | 7 | Проверить наличие фильтров для удобного поиска товаров | все ок | соответствует ТЗ |
                | 8 | Убедиться, что каждый товар имеет уникальный идентификатор | все ок | Данные в БД |
                | 9 | Проверить наличие кнопки "Добавить в корзину" для каждого товара и то что она работает | все ок |  |
                | 10 | Убедиться, что каталог товаров отображается корректно на всех устройствах (компьютеры, планшеты, мобильные телефоны) и разные браузеры, а также расширения экранов | все ок |  |
            - Чек лист добавления заинтересовавших товаров в корзину
                
                
                | № | Проверка | Ожидаемый результат | Комментарий |
                | --- | --- | --- | --- |
                | 1 |  Нажать на кнопку под выбранным товаром | кнопка работает, товар добавляется в корзину |  |
                | 2 | Убедиться, что товар успешно добавлен в корзину и отображается количество выбранных единиц | товар добавлен в корзину, кол-во верное |  |
                | 3 | Проверить правильность информации о товаре в корзине (название, цена, количество) | Ин-фа отображается верно, цена и кол-во соответствует |  |
                | 4 | Проверить возможность изменения количества товара в корзине | изменения осуществляются |  |
                | 5 | Убедиться, что общая сумма заказа автоматически пересчитывается при изменении количества товаров | цена пересчитывается | скидки если есть применяются и пересчитываются см ТЗ |
                | 6 | Проверить наличие кнопок ("Очистить корзину"), ("Продолжить покупки") и ("Оформить заказ”) | есть в наличии | согласно ТЗ |
                | 7 | Убедиться, что выбранный товар сохраняется в корзине при переходе на другие страницы или при выходе из магазина и входе обратно | сохраняется |  |
                | 8 | Проверить возможность удаления товара из корзины 1 или нескольких товаров | удаляется |  |
                | 9 | Проверить корректность отображения информации о товарах в корзине на всех устройствах (компьютеры, планшеты, мобильные телефоны), браузеры, расширения | ок |  |
                | 10 | Убедиться, что после добавления товара в корзину возможно продолжить покупки или оформить заказ | все ок |  |
            - Чек лист оформления заказа
                
                
                | № | Проверка | Ожидаемый результат | Комментарий |
                | --- | --- | --- | --- |
                | 1 | Нажать на кнопку "Оформить заказ" в корзине или на соответствующей странице. | открывается форма |  |
                | 2 |  Проверить, что отображается форма оформления заказа с полями для ввода контактной информации (имя, телефон, адрес доставки). | форма соответствует ТЗ |  |
                | 3 | Убедиться, что есть возможность выбора способа доставки (курьерская доставка, самовывоз, доставка почтой и т.д.). | есть выпадающий список, выбор работает |  |
                | 4 | Проверить наличие выбора способа оплаты (наличными, картой, электронными деньгами и пр.). | есть выпадающий список, выбор работает |  |
                | 5 | Убедиться, что есть возможность указать комментарии к заказу (дополнительные пожелания к доставке и пр.). | поле активно, кол-во символов ограничено согласно ТЗ |  |
                | 6 |  Проверить корректность заполнения всех обязательных полей формы заказа. | без обязательных заполненных полей форма не работает |  |
                | 7 | Убедиться, что после оформления заказа пользователь получает подтверждение с информацией о заказе (номер заказа, сумма, способ доставки и оплаты). | приходит смс, пуш сообщение в соц сеть или на почту, согласно ТЗ |  |
                | 8 | Проверить, что пользователю предоставляется возможность отслеживать статус своего заказа (обработка, доставка, выполнен и т.д.). | в личном кабинете на сайте или на почте есть возможность отслеживать статусы | согласно ТЗ |
                | 9 | Проверить корректность отображения информации о заказе на всех устройствах (компьютеры, планшеты, мобильные телефоны), браузеры, расширения. | все ок |  |
                | 10 | Убедиться, что после оформления заказа пользователю предоставляется возможность вернуться к покупкам или перейти на главную страницу магазина." | есть возможность |  |
            - Чек лист выбора способа доставки
                
                
                | № | Проверка | Ожидаемый результат | Комментарий |
                | --- | --- | --- | --- |
                | 1 | Проверить, что на странице оформления заказа есть раздел выбора способа доставки. | есть |  |
                | 2 | Убедиться, что доступны различные варианты доставки (курьерская доставка, самовывоз, почтовая доставка и т.д.) | доступны |  |
                | 3 | Проверить условия и сроки доставки для каждого способа | все работает |  |
                | 4 | Убедиться, что указаны стоимость доставки и возможность бесплатной доставки при определенной сумме заказа | если это есть в ТЗ |  |
                | 5 | Проверить возможность выбора удобного для клиента времени и даты доставки  | есть возможность |  |
                | 6 | Убедиться, что есть возможность указать адрес доставки и контактные данные получателя. | есть возможность | есть в подсказках адреса |
                | 7 | Проверить наличие дополнительных услуг  | есть возможность | согласно ТЗ |
                | 8 | Убедиться, что клиенту предоставляется информация о возможности отслеживания статуса доставки | есть информационное оповещение |  |
                | 9 | Проверить, что клиенту доступна возможность изменить способ доставки до оформления заказа | есть возможность | согласно ТЗ |
                | 10 | Убедиться, что после выбора способа доставки клиент может продолжить процесс оформления заказа или вернуться к выбору товаров." | есть возможность |  |
            - Чек лист оплаты заказа онлайн через сторонний сервис
                
                
                | № | Проверка | Ожидаемый результат | Комментарий |
                | --- | --- | --- | --- |
                | 1 | Убедиться, что на странице оформления заказа есть раздел выбора способа оплаты | есть |  |
                | 2 | Проверить, что доступны различные способы оплаты (картой, электронными деньгами, банковским переводом, разные виды карт) | есть | гугл плей, яндекс плей - если есть в ТЗ |
                | 3 | Убедиться, что указаны все необходимые данные для оплаты (номер карты, имя владельца, срок действия, CVV-код и пр.) | есть, все обязательные |  |
                | 4 | Проверить, что страница оплаты защищена SSL-сертификатом и имеет безопасное соединение (https://). | ок |  |
                | 5 | Убедиться, что процесс оплаты интуитивно понятен и прост для пользователя. | ок | есть подсказки, согласно ТЗ |
                | 6 |  Проверить, что после ввода данных для оплаты и нажатия кнопки \"Оплатить\" пользователь получает подтверждение об успешной оплате. | получает | чек приходит на почту |
                | 7 | Убедиться, что клиенту доступна информация об успешной оплате и деталях заказа (номер заказа, сумма, способ доставки и пр.). | доступна |  |
                | 8 | Проверить возможность отмены оплаты или изменения способа оплаты до завершения процесса оплаты. | есть  |  |
                | 9 | Убедиться, что после оплаты заказа пользователю предоставляется возможность продолжить покупки или вернуться на главную страницу магазина. | есть |  |
                | 10 | Проверить корректность отображения информации об оплате на всех устройствах (компьютеры, планшеты, мобильные телефоны), разные браузеры. | есть |  |
        - Тестирование
            
            Примеры тест-кейсов
            
            1. **Тест-кейс: Проверка наличия всех категорий товаров в каталоге**
            - Шаги:
                1. Зайти на главную страницу интернет магазина.
                2. Перейти в раздел каталога товаров.
                3. Проверить наличие всех категорий товаров.
            - Ожидаемый результат: Все категории товаров присутствуют в каталоге.
            1. **Тест-кейс: Проверка информации о товаре в корзине**
            - Шаги:
                1. Убедиться, что товар успешно добавлен в корзину.
                2. Проверить правильность информации о товаре в корзине (название, цена, количество).
            - Ожидаемый результат: Информация о товаре в корзине соответствует выбранному товару.
            1. **Проверка функциональности кнопки "Оформить заказ":**
            - Шаги:
                
                 1. Зайти в корзину.
                
                 2. Нажать на кнопку "Оформить заказ".
                
            - Ожидаемый результат: Открывается страница оформления заказа.
            1. **Проверка функциональности кнопки "Оформить заказ":**
            - Шаги:
                
                 1. Найти кнопку "Оформить заказ" в корзине или на соответствующей странице.
                
                2. Нажать на кнопку "Оформить заказ".
                
            - Ожидаемый результат: Страница оформления заказа открывается.
            1. **Проверка получения подтверждения об успешной оплате**
            - Шаги:
                1. Ввести данные для оплаты и нажать кнопку "Оплатить".
            - Ожидаемый результат: Пользователь получает подтверждение об успешной оплате.
            
            Оформление багов производится в багтрекинговой системе либо в любом документе установленном на проекте по форме:
            
            | № | Название |  |
            | --- | --- | --- |
            | 1 | Приоритет | P |
            |  | Серьезность | S |
            |  | Шаги воспроизведения | 1.  |
            |  |  | 2. |
            |  | Ожидаемый результат |  |
            |  | Фактический результат |  |
            
            ---
            
            ## Виды тестирования:
            
            - Тестирование требований
            - Функциональное
            - UX\UI
            - Интеграционное тестирование
            - API тестирование
            - Кроссбраузерное
            - Кроссплатформенное
            - Мобильное тестирование
            - Нагрузочное тестирование
            - Тестирование безопасности
            - Приемочное тестирование
        - Отчет
            
            **Для выводов использовать метрики**
            
            1. Покрытие требований тестированием: 100%
            2. Успешное прохождение тест-кейсов: 100%
            3. Характеристики найденных дефектов по Серьезности-0
            4. Характеристики найденных дефектов по Приоритету-0
            
            | Период проведения работ над тестированием проекта | сроки |
            | --- | --- |
            | Начало тестирования проекта | 27.04.2024 |
            | Окончание тестирования проекта | 11.05.2024 |
- 2 задание
    1. Установить PostgreSQL (желательно в Docker)
    
    Если через Docker - описать какие команды использовал
    
    1. Создать БД academy.
    
    Приложить скрипт
    
    1. Добавить таблицы по приложенной схеме рис. 1 (названия полей, связи между таблицами должны соответствовать схеме, остальное (ограничения целостности, уникальность, значения по умолчанию, проверки, типы данных) на усмотрение стажера).
    
    Приложить скрипт
    
    Рисунок 1: схема таблиц базы данных academy
    
    https://lh7-us.googleusercontent.com/ioL_3LipyVGDWvAaN9QJaJw-6Nq5vjY1nDiteZ7EHaSHXShzALJZ17XC8hBgj1qGNaunMjvTE65EDL2cjh5KwhWJ9hqRnRBZFB2kCqfCU8yn9FhxEEuvg6GF7f0LE15nE54uGhKnPeYFWevgtUZw6w
    
    1. Добавить несколько записей в таблицы.
    
    Приложить скрипт
    
    1. Написать запрос, который возвращает всех студентов, которые еще не сдали ни одного экзамена.
    
    Приложить скрипт
    
    1. Написать запрос, который возвращает список студентов и количество сданных им экзаменов. Только для студентов, у которых есть сданные экзамены.
    
    Приложить скрипт
    
    1. Вывести список курсов со средним баллом по экзамену. Список отсортирован по убыванию среднего балла.
    
    Приложить скрипт
    
    8*. Сгенерировать скрипт, который наполняет таблицы произвольными данными (можно с помощью psql, можно с помощью любого языка программирования).
    
    Приложить скрипт генерации данных
    
    - Решение
        
        Скрипты
        
        - Создание базы
            
            CREATE DATABASE academy;
            
        - Создание таблиц
            
            CREATE TABLE Students (s_id integer PRIMARY KEY, name text, start_year integer);
            INSERT INTO Students (s_id, name, start_year)
            VALUES
            (24123, 'Yuka', 2024),
            (22789, 'Tea', 2022),
            (21023, 'Lev', 2020);
            
            CREATE TABLE Course (s_no integer PRIMARY KEY, title text, hours integer );
            INSERT INTO Course (s_no, title, hoursr)
            VALUES
            (13, 'English', 180),
            (21, 'Latin', 360),
            (10, 'mathematics', 200);
            
            CREATE TABLE Exams (s_id integer REFERENCES Students (s_id), s_no integer REFERENCES Course (s_no), score integer, PRIMARY KEY (s_id, s_no));
            
            INSERT INTO Exams (s_id, s_no, score)
            VALUES
            (24123, 13, 5),
            (22789, 21, 3),
            (21023, 10, 4);
            
        - Запрос, который возвращает всех студентов, которые еще не сдали ни одного экзамена.
            
            SELECT s_id, name FROM Students
            WHERE s_id NOT IN (SELECT s_id FROM Exams);
            
        - Запрос, который возвращает список студентов и количество сданных им экзаменов. Только для студентов, у которых есть сданные экзамены.
            
            SELECT [s.name](http://s.name/), COUNT(e.s_id) AS exams_passed
            FROM Students s
            JOIN Exams e ON s.s_id = e.s_id
            GROUP BY s.s_id, [s.name](http://s.name/);
            
        - Список курсов со средним баллом по экзамену. Список отсортирован по убыванию среднего балла.
            
            SELECT c.title, AVG(ex.score)
            FROM course AS c
            LEFT JOIN Exams AS ex ON ex.s_no = c.s_no
            WHERE ex.score IS NOT NULL
            GROUP BY c.title;
            
        
        python команды такие, но как их вписать в скрипт не знаю
        
        import random
        import string
