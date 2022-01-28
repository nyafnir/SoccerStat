# Задание
Разработать приложение (сайт) просмотра статистики ведущих европейских турниров по футболу.

# Условия
1. Фреймворк React. Допускается использовать: Любые UI библиотеки (Оценивается
рациональность выбора)
2. Наличие страниц:
- Список лиг/соревнований
- Список команд
- Календарь лиги - список матчей лиги/соревнования
- Календарь одной команды - список матчей команды  
3. Особенности:
- На страницах календаря можно указать фильтр по дате (с, по)
- На страницах списка можно найти сущность по текстовому поиску.
- После обновления страницы данные (год, команда, поисковой запрос) должны
сохраняться, т.е. параметры должны быть отображены в адресной строке
(роутинг либо GET параметры)
4. В качестве публичного API для получения данных рекомендуется использовать
https://www.football-data.org/. Это API содержит ограничения на бесплатном
тарифе, пользователю необходимо корректно сообщать о том, что данные не
получены. Кандидат может использовать любое другое API при условии, что
оно позволит получить необходимые для выполнения задания данные

# Требования к сдаче ТЗ
Проект должен быть выложен на репозиторий GitHub, код должен быть чистым
(желательно использовать линты и prettier для автоматического контроля), в индекс не
должны попадать временные файлы, файлы настроек проекта и библиотек.
Ключи к API не должны быть захардкожены - это значит что они должны быть
вынесены в переменные окружения, в самом коде ключа быть не должно.
Плюсом к сдаче приложения будет настроенный деплой на gh-pages
Категории оценки:
- функционал (удобство интерфейса, полнота выполнения пунктов ТЗ)
- верстка (корректность отображения в браузере, наличие адаптивной версии)
- код (чистота кода, рациональность использования библиотек, уровень
проработки архитектуры)

# Процесс разработки
- [x] Прототипирование: `SoccerStat.epgz` (Pencil)
- [x] Дизайн: `SoccerStat.fig` (Figma)
- [x] Выбор среды: Create React App  
- [ ] Размещение конфигурации отдельно
- [ ] Использование linter-а и Prettier
- [ ] Создание экрана (главного): Список лиг/соревнований
- [ ] Создание экрана: Список команд
- [ ] Создание экрана: Календарь лиги
- [ ] Создание экрана: Календарь одной команды
- [ ] Особенность: На страницах календаря фильтр по дате
- [ ] Особенность: На страницах списка сделать поиск
- [ ] Особенность: Отражение переходов в адресной строке
- [ ] API: Сообщать о том, что данные не получены
- [ ] Адаптация под мобильный браузер
- [ ] Бонус: Deploy на gh-pages