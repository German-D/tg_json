<h2>Телеграм бот с функцией валидации и бьютифаера JSON</h2>

> **Статус проекта:**
>
> 🟢 Поддерживается (активный) 

## Цели и Задачи
Помочь тестировщику быстрее проверить JSON на нарушение синтаксиса

Этот бот при получении JSON:
* Проверяет на ошибки синтаксиса
* Возвращает JSON в удобочитаемом формате

## 🖼 Скриншоты

Стартовое меню:

![image](https://raw.githubusercontent.com/German-D/tg_json/main/static/menu.png)

После отправки JSON c ошибкой:

![image](https://raw.githubusercontent.com/German-D/tg_json/main/static/syntax.png)

Пример работы бтютифаера:

![image](https://raw.githubusercontent.com/German-D/tg_json/main/static/beautifaer.png)


## 💻 Технологии

* Python
* Библиотека `telebot`

## ⏬ Установка на локальном компьютере

Клонируем удалённый репозиторий на локальную машину:

```markdown
git clone git@github.com:German-D/tg_json.git
```
Создать бота и через [@BotFather](https://t.me/BotFather) и вставить в проекте свой токен от бота

Создаём виртуальное окружение внутри папки проекта.
Далее команды для MacOS (для windows инуструкция [есть вот тут](https://realpython.com/python-virtual-environments-a-primer/#create-it))

``` markdown
python3 -m venv venv
```

``` markdown
source venv/bin/activate
```
Устанавливаем библиотеки

``` markdown
python3 -m pip install pyTelegramBotAPI
```


Запускаем
``` markdown
python3 json_bot.py
```

## Автор

Герман Дольников (Телеграм @dolnikov)
