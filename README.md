# ITMO_ICT_WebDevelopment_tools_2023-2024

Репозиторий для реализации дистанционного обучения по дисциплине "Соедства Web-программирования".

[Учебный журнал](https://docs.google.com/spreadsheets/d/1FuO5V6SSLJBSHT9f92R_iFO8pDD7TuDjcgOWXgdYFSk/edit?usp=sharing) по дисциплине. Тут доступна информация о сроках сдачи работ, о текущей успеваемости студентов и описаны все материалы необходимые для реализации курса.

Составляющие финальной оценки:
- 60 баллов - лабы (их делать обязательно).
- 20 баллов - тесты.
- 20 баллов - дисскусии на практиках (1 доклад за семестр).

При выполнении всех лаб по дисциплине в срок + две недели - экзамен-автомат.

Все лабы необходимо сдать до сессии декабря, иначе есть риск, что преподаватель не успеет их проверить.

Если лабораторная работа выполнена не в срок, требуется получить допуск к ее защите. Для допуска необходимо выполнть задания на https://leetcode.com/. 1 неделя просрочки - 1 задание.

# Лабораторная работа 1. Реализация серверного приложения FastAPI.

Необходимо реализовать полноценное серверное приложение с помощью фреймворка FastAPI с применением дополнительных средств и библиотек. [Текст работы](https://rendex85.github.io/WebDevelopmentLabsDocs/lr2/lr2/)

# Лабораторная работа 2. Потоки. Процессы. Асинхронность.

Цель работы: понять отличия перечисленных понятий.

[Мануал о том, как работают потоки и какие у есть дополнительные функции у библиотеки thearding (на 08.04.2024 - дорабатывается](https://docs.google.com/document/d/1b4qjEsRi7VvMsDPu5z8JZ8yEedliFS0CiY2dVRAwVXc/edit?usp=sharing)

Мануал о том, как работать с процессами

Мануал об асинхронности

### Задание:

#### Задача 1. Различия между threading, multiprocessing и async в Python

**Задача:** Напишите три различных программы на Python, использующие каждый из подходов: threading, multiprocessing и async. Каждая программа должна решать считать сумму всех чисел от 1 до 1000000. Разделите вычисления на несколько параллельных задач для ускорения выполнения.

**Подробности задания:**
1. Напишите программу на Python для каждого подхода: threading, multiprocessing и async.
2. Каждая программа должна содержать функцию calculate_sum(), которая будет выполнять вычисления.
3. Для threading используйте модуль threading, для multiprocessing - модуль multiprocessing, а для async - ключевые слова async/await и модуль asyncio.
4. Каждая программа должна разбить задачу на несколько подзадач и выполнять их параллельно.
5. Замерьте время выполнения каждой программы и сравните результаты.


#### Задача 2. Параллельный парсинг веб-страниц с сохранением в базу данных
**Задача:** Напишите программу на Python для параллельного парсинга нескольких веб-страниц с сохранением данных в базу данных с использованием подходов threading, multiprocessing и async. Каждая программа должна парсить информацию с нескольких веб-сайтов, сохранять их в базу данных.

**Подробности задания:**
1. Напишите три различных программы на Python, использующие каждый из подходов: threading, multiprocessing и async.
2. Каждая программа должна содержать функцию parse_and_save(url), которая будет загружать HTML-страницу по указанному URL, парсить ее, сохранять заголовок страницы в базу данных и выводить результат на экран.
3. Используйте PostgreSQL или другую базу данных на ваш выбор для сохранения данных.
4. Для threading используйте модуль threading, для multiprocessing - модуль multiprocessing, а для async - ключевые слова async/await и модуль aiohttp для асинхронных запросов.
5. Создайте список нескольких URL-адресов веб-страниц для парсинга и разделите его на равные части для параллельного парсинга.
6. Запустите параллельный парсинг для каждой программы и сохраните данные в базу данных.
7. Замерьте время выполнения каждой программы и сравните результаты.

**Дополнительные требования:**
- Сделайте документацию, содержащую описание каждой программы, используемые подходы и их особенности.
- Включите в документацию таблицы, отображающие время выполнения каждой программы.
- Прокомментируйте результаты сравнения времени выполнения программ на основе разных подходов.

**Срок сдачи:** 13 мая 2024.

**Оценка:** Качество и эффективность реализации каждой программы, понимание особенностей threading, multiprocessing и async, анализ и сравнение времени выполнения программ на основе различных подходов.



## Сдача работ

Для сдачи работы в связи с переходом на дистанционную форму обучения введены дополднительные правила игры.

Все отчеты сохраняются в **markdown** и **mkdocs** (документы и презентации).

Все студенческие работы хранятся в папке **Students**
Для сдачи работы необходимо:

1. Зарегистрироваться на Git.
2. Сделать форк репозитория с заданиями в свой аккаунт (на странице https://github.com/TonikX/ITMO_ICT_WebDevelopment_tools_2023-2024 кнопка fork справа, сверху).
3. Установить Git на компьютер.
4. Открыть папку, где хранятся Ваши проекты. В контекстом меню нажать "Open Git Bash here". Склонировать форкнутый репозиторий на комьютер (git clone [https://github.com/ваш аккаунт/ITMO_ICT_WebDevelopment_tools_2023-2024](https://github.com/TonikX/ITMO_ICT_WebDevelopment_tools_2023-2024/)).
5. В файловой системе Вашего компрьютера в склонированном репозитории создать в папке students/группа Вашу личную папку в формате Фамилия_Имя латиницей (Пример **students/k3340/Petrov_Vasya**).
6. В личной папке сделать подпапку с текущей работой в формате lr_номер (Пример **students/k3340/Petrov_Vasya/Lr1**).
7. Записать в папку отчетные материалы.
8. Сделать коммит, описать его адекватно (Пример "был добавлен файл перезентация_петров.pdf"). Набрать команлы git add и git commit -m "название комита".
9. Сделать push в Ваш форкнутый репозиторий (git push).
10. Сделать пул-реквест в репозиторий преподавателя из вашего форкнутого, описать его. Структура заголовка пулреквеста: **Фамилия_Имя-Работа_Номер** (Пример: Петров_Василий-Лабораторная_работа_1).
11. Сделатб документацию в mkdocs и оставить ее в комментариях к пулреквесту.

