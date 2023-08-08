---
title: Керівництво по стилю
author: Ezequiel Bruni, Krista Burdine
contributors: Steven Spencer
tags:
  - contribute
  - керівництво по стилю
---

# Керівництво по стилю Rocky Linux Documentation

*Rocky Linux — це корпоративний Linux, який найшвидше розвивається у світі, його документація також зростає в геометричній прогресії завдяки таким учасникам, як ви. Ваш вміст вітається в будь-якому форматі, і стилісти документів RL допоможуть вам узгодити його зі стандартами, викладеними тут.*

## Вступ

### Про

*Нові внески вітаються, щоб виростити це місце в Інтернеті для інформації про використання Rocky Linux. Ви можете створювати документи у зручному для вас форматі, а команда документації працюватиме з вами або іншим чином допоможе відформатувати їх, щоб вони виглядали та відчувалися частиною родини Rocky.*

У цьому посібнику описано стандарти стилю англійської мови, щоб **покращити читабельність, виділити виняткові випадки** та **поліпшити переклад** у документації Rocky Linux. Щодо запитань про стиль, які не розглядаються в цьому посібнику, зверніться до наступного:

* [Merriam Webster Dictionary](https://www.merriam-webster.com/)
* [Chicago Manual of Style (CMOS), 17th ed.](https://www.chicagomanualofstyle.org/home.html)

### Зробити внесок

Для повнішого розуміння того, як робити внески, зверніться до наших відповідних посібників:

* [Rocky Linux Contribution Guide](https://docs.rockylinux.org/guides/contribute/) містить вимоги до системи та програмного забезпечення для початку роботи.
* [Посібник для перших учасників Rocky Linux](../beginners/) для ознайомлення з GitHub, нашою базою документації.
* [Форматування Rocky Docs](../rockydocs_formatting/) для структури Markdown.

## Рекомендації щодо стилю

*Метою документації RL є використання чіткої та узгодженої мови для доступності та сприяння поточним перекладам.*

### Граматика і пунктуація

**Ознаки технічного написання**, як зазначено в Чиказькому посібнику зі стилю, включають наступне:

* Подвійні лапки («стиль Чикаго»), а не одинарні лапки («стиль Оксфорд»).
* Крапки та коми беруться в лапки “ось так,” а не “ось так”.
* Тире {shift}+{option}+{-} не має пробілів ні перед, ні після, як це, і є кращим для фраз у дужках.
* Використовуйте послідовну кому перед «і» в списку з трьох елементів: «Горошок, гірчиця та морква».
* Заголовки, як правило, мають бути написані з великої літери: перше й останнє слова, а також усі іменники, займенники, дієслова та прислівники пишуться з великої літери. Якщо ваш документ краще працює з великими літерами в стилі речень, можливо, через те, що ви часто посилаєтеся на акроніми, зробіть це узгодженим у всьому документі.
* Заголовки не потребують крапки чи крапки з комою наприкінці, навіть якщо вони вживаються з великої літери, якщо вони не закінчуються абревіатурою.

### Голос і тон

* **Проста мова.** Це можна описати як *менш розмовний* стиль. Більшість нашої документації відповідає цьому стандарту.
    * Уникайте метафор і ідіом.
    * Скажіть те, що ви маєте на увазі, якомога меншою кількістю слів.
    * Визначте та уникайте непотрібних технічних термінів. Подумайте, що ваша аудиторія – це переважно люди, які певною мірою знайомі з предметом, але можуть не бути експертами в цьому предметі.
    * Винятки для простої мови:
        * Більш розмовний стиль підходить для документації, адресованої новачкам або початківцям, або для написання вмісту, як-от дописів у блогах.
        * Більш формальний або стислий стиль формулювання підходить для документації, адресованої досвідченим користувачам, або документації API (інтерфейс прикладного програмування).
* **Інклюзивна мова.**
    * Використання мови розвивається з часом. Деякі слова еволюціонували, щоб нести негативні конотації, тому документацію слід переписати, щоб використовувати нові слова.
        * *Master/slave* стає *primary/secondary* або узгодженим організаційним стандартом.
        * *Blacklist/whitelist* стає *blocklist/allowlist* або узгодженим організаційним стандартом.
        * Під час створення документації ви можете подумати про інші відповідні приклади.
    * Говорячи про особу *невідомої* або *небінарної* статі, зараз вважається прийнятним використовувати "вони" як займенник однини.
    * Говорячи про свої здібності, формулюйте відповіді як *здібності*, а не *обмеження.* Наприклад, якщо вам цікаво, чи ми маємо документацію про запуск Steam на Rocky Linux, відповідь не просто «ні». Скоріше, «Здається, це чудове місце для вас, щоб створити щось, щоб додати до нашого дерева!»
* **Уникайте скорочень.** Це допомагає з перекладом. Винятком є написання чогось у більш розмовному тоні, як-от публікації в блозі чи вітальні інструкції для нових учасників спільноти.

## Форматування

### Дати

Якщо можливо, використовуйте назву місяця у форматі {day} {Month} {year}. Однак {Month} {day}, {year} також прийнятний для вирішення проблем із чіткістю чи виглядом. У будь-якому випадку, щоб уникнути плутанини, пишіть назви місяців, а не серію чисел. Наприклад: 24 січня 2023 р., але 24 січня 2023 р. також прийнятно, причому обидва варіанти краще, ніж 1/24/2023 або 24/01/2023.

### Одноетапні процедури

Якщо у вас є процедура лише з одним кроком, використовуйте маркер, а не номер. Наприклад:

* Реалізуйте цю ідею і рухайтеся далі.

### Мова графічного інтерфейсу

* Текстові інструкції щодо інтерфейсу користувача: описуючи команду, яку потрібно ввести в інтерфейс користувача, використовуйте слово «enter», а не «put» або «type». Використовуйте блок коду, щоб написати команду (тобто встановити її зворотними галочками):

*Приклад тексту Markdown* `У полі **повідомлення про фіксацію** введіть update_thisdoc.`

* Назви елементів інтерфейсу користувача: **жирним шрифтом** назви елементів інтерфейсу, таких як кнопки, пункти меню, назви діалогових вікон тощо, навіть якщо це слово не можна натиснути:

*Example Markdown text* `In the **Format** menu, click **Line Spacing**.`

## Структура

### Початковий вміст кожного посібника або сторінки/розділу книги

* **Анотація.** Коротка інформація про те, чого очікувати від цієї сторінки
* **Цілі.** Маркірований список того, що ця сторінка передасть читачеві
* **Навички** необхідні/вивчені.
* **Рівень складності.** 1 зірка для легкого, 2 для середнього тощо.
* **Час читання.** Щоб визначити це число, розділіть слова у вашому документі на швидкість читання 75 слів на хвилину.

### Застереження

У Markdown попередження — це спосіб помістити інформацію у вікно, щоб виділити її. Вони не є важливими для документації, але є інструментом, який може бути вам корисним. Дізнайтеся більше про застереження в нашому [документі про форматування Rocky](../rockydocs_formatting/).

## Доступність

*Наступні стандарти покращують доступ до нашої документації для тих, хто користується такими засобами, як програми зчитування з екрана.*

### Зображення

* Надайте текстові описи в тексті заміщення або підписах для кожного нетекстового елемента, наприклад діаграм, зображень або значків.
* По можливості уникайте скріншотів із текстом.
* Зробіть альтернативний текст значущим, а не просто описовим. Для значків дій, наприклад, введіть опис функції, а не опис її вигляду.

### Посилання

* Зробіть посилання описовими, щоб було зрозуміло, куди вони ведуть із тексту чи контексту. Уникайте гіперпосилань із назвами на зразок «клацніть тут».
* Переконайтеся, що всі посилання працюють, як описано.

### Таблиці

* Створюйте таблиці в логічному порядку зліва направо, зверху вниз.
* Уникайте порожніх клітинок у верхній або лівій частині таблиці.
* Уникайте об’єднаних клітинок, які охоплюють кілька стовпців.

### Кольори

* Деяким елементам у Markdown, наприклад попередженням, призначено колір, щоб полегшити візуальне розуміння. Загалом, вони також мають присвоєну назву; наприклад, застереження «небезпека» відображає червону рамку, але також містить дескриптор «небезпека», вбудований в опис. Але, створюючи спеціальне попередження, майте на увазі, що колір не може бути єдиним засобом передачі команди або рівня попередження.
* Будь-яка команда, яка містить сенсорний напрямок, як-от *вище* або *нижче*, *колір*, *розмір*, *візуальне розташування* на сторінці тощо, також має включати напрямок, який можна передати лише текстовим описом.
* Створюючи графічний елемент, переконайтеся, що існує достатній контраст між кольорами переднього плану та фону, щоб програмі зчитування з екрана було легко інтерпретувати його.

### Заголовки

* Використовуйте всі рівні заголовків, не пропускаючи рівні.
* Розташуйте весь матеріал під заголовками, щоб полегшити читання.
* Пам’ятайте, що в Markdown можна використовувати лише один заголовок першого рівня.

## Підсумок

У цьому документі викладено наші стандарти внеску, зокрема **інструкції щодо стилю**, те, як **структурувати** ваш документ, і способи включення **інклюзивність** і **доступність** до тексту. Це стандарти, до яких ми прагнемо. У міру своїх можливостей пам’ятайте про ці стандарти під час створення та редагування документації.

Однак — і не пропустіть це застереження — **ставтеся до цих стандартів як до інструменту, а не як до перешкоди.** У дусі інклюзивності та доступності ми хочемо переконатися, що ваш внесок має плавне входження в сімейне дерево Роккі. Ми є дружньою командою документалістів і стилістів, які допомагають вам, і ми допоможемо привести ваш документ у його остаточний вигляд.

Ви готові? Давайте розпочнемо!