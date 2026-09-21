Отчёт по курсовой работе 
«Создание сайта с использованием MkDocs»

Цель работы
Создать сайт организации с использованием MkDocs и языка разметки Markdown.

Ход работы
1. Установка
python -m pip install mkdocs mkdocs-material

2. Создание проекта
mkdir my-personal-site
cd my-personal-site
python -m mkdocs new .

3. Настройка mkdocs.yml
site_name: КСК "Аллюр"

site_description: Страница организации

site_author: Попинова Екатерина

Тема: Material

Цвета: brown + deep orange

Features: navigation.tabs, navigation.sections, navigation.top, search.highlight

Соцсети в футере: VK, Telegram

4. Созданные страницы
Страница	Файл
Главная	index.md
О клубе	about.md
Услуги	services.md
Наши лошади	horses.md
Контакты	contacts.md
Элементы Markdown: заголовки, списки, таблицы, ссылки, изображения, эмодзи.

5. Изображения
Создана папка docs/images/, добавлены картинки.

6. Тестирование
python -m mkdocs serve
Сайт: http://127.0.0.1:8000/ksk-allyur/

Проверено: все страницы, навигация, поиск, переключение тем

Выводы
Освоен MkDocs — инструмент для создания статических сайтов из Markdown. Настроена тема Material, создан многостраничный сайт с навигацией, поиском и адаптивным дизайном. Сайт опубликован на GitHub Pages.

## Скриншоты

### 1. Главная страница

![Главная страница](images/01_main.png)

### 2. Страница «О клубе»

![О клубе](images/02_about.png)

### 3. Страница «Услуги»

![Услуги](images/03_services.png)

### 4. Страница «Наши лошади»

![Наши лошади](images/04_horses_1.png)

![Наши лошади](images/05_horses_2.png)

### 5. Страница «Контакты»

![Контакты](images/06_contacts.png)

### 6. Тёмная тема

![Тёмная тема](images/07_dark_theme.png)

### 7. Работа поиска

![Поиск](images/08_search.png)
