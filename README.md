## Тестовое задание для Frontend Разработчика

**Задание:** Создание простого веб-приложения для управления заявками компании

**Описание:** 
Сделать SPA-приложение состоящее из 3-х страниц.
Макет состоит из бокового меню, заголовка страницы, виджета текущего сотрудника и основного контента. 
Пользователь имеет возможность переходить по страницам используя боковое меню. Меню состоит из 5-и пунктов: дашборд, новая заявка, мои заявки, согласованные заявки, отклоненные заявки.
Страница "Дашборд" состоит из 4-х диаграмм: линейный график курса валют в разрезе месяца, круговая диаграмма процентного выполнения kpi, гистограмма новых/текущих/закрытых заявок, линейчатая диаграмма.
Страница "Новая заявка" состоит из формы подачи. Форма подачи состоит из разных типов полей. Должны быть следующие типы полей в форме подачи: текстовое, цифровое, денежное, номер телефона по маске, выпадающий список, календарь, чек-бокс, радиокнопки. Все поля доступны для редактирования. Некоторые поля помечены как обязательные. Также должны быть 2 кнопки - отправить (активная) и очистить (неактивная). Кнопка "Очистить" становится доступной только при заполнении одного и более полей. При нажатии кнопки "Отправить" проверяется корректность заполнения формы. При корректном/некорректном заполнении выводится сообщение об успешной отправки с последующей очистной полей или о выявленных ошибках заполнения.
Страницы "мои/согласованные/отклоненные заявки" состоят из таблицы. Таблица содержит 10 столбцов, с шапкой и mock-данные. Таблица имеет пагинацию из 100 страниц. Каждая страница содержит 20 записей. Каждая запись содержит данные следующих типов: порядковый номер записи, ФИО, дата, текст, число, набор кнопок (редактировать, удалить). При удалении запрашивается подтверждение данного действия. При положительном варианте запись исчезает, с последующим переносом недостающей записи со следующей страницы пагинации и пересчётом порядковых номеров записей.
[Референтный дизайн](https://www.figma.com/file/XmDhPyJ8GaYRqTNcIrRptJ/Test?type=design&node-id=0-1&mode=design&t=hPYE2Jn7n1MWfhFV-0)

**Технические требования:**
1. Использование React.js для создания пользовательского интерфейса.
2. Использование TypeScript для типизации кода.
3. Использование Redux для управления состоянием приложения.
4. использованием библиотеки axios
5. Взаимодействие с HTTP API для сохранения задач (вы можете использовать любой общедоступный сервис или создать фейковый API).
6. Верстка должна быть выполнена с использованием HTML и CSS. Можете использовать css-фреймворк.
7. Реализация адаптивной верстки для корректного отображения.
8. Использование Git для контроля версий. Конечный результат на GitHub и предоставьте ссылку.
9. Создайте файл `Dockerfile` и `docker-compose.yaml` для возможности запуска приложения в контейнере с использованием Docker Compose.

**Оценка:**
Ваше задание будет оцениваться по следующим критериям:
- Качество кода и архитектура приложения.
- Работоспособность приложения.
- Адаптивная верстка.
- Использование TypeScript и Redux.
- Взаимодействие с HTTP API.
- Использование Git и наличие кода на GitHub.
- Использование Docker и Docker Compose.

Убедитесь, что вы предоставляете инструкции по запуску вашего приложения с использованием Docker Compose и любые другие необходимые детали.
