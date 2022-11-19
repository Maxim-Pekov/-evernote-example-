# evernote-example

Этот проект создан для работы с интернет ресурсом по созданию заметок [https://www.evernote.com](https://www.evernote.com). 

Проект содержит три скрипта и вспомогательные файлы:
* `add_note2journal.py` - Запрашивает дату, после проверяет ее на валидность, и создает заметку по шаблону с указанием даты и дня недели.
* `dump_inbox.py` - Запрашивает кол-во заметок, содержимое которых нужно вывести в консоль.
* `list_notebooks.py` - Возвращает список всех блокнотов в учетной записи.
* `config.py` - Вспомогательный скрипт для получения персональных данных пользователя для доступа к Api.

## Как он работает:

1. `add_note2journal.py`
   Вы запускаете скрипт командой ниже, параметр <"YYYY-MM-DD"> - это дата которая должна быть в указанном формате.

```python
python3 add_note2journal.py <"YYYY-MM-DD">
```
2. `dump_inbox.py` Вы запускаете скрипт командой ниже, с указанием необязательных аргументов. Скрипт выведет в консоль
                  содержимое столько заметок, сколько запрашивали. По умоланию выведет 10ть заметок.                  
   
```python
python3 dump_inbox.py <Кол-во заметок>
```

3. `list_notebooks.py`
   Вы запускаете скрипт командой ниже, в консоль будет выведен список всех блокнотов в учетной записи 
и идентификационный код этого блокнота.

```python
python3 list_notebooks.py
```

4. `config.py`
   Вспомогательный скрипт для получения персональных данных пользователя для доступа к Api. Для его работы нужно создать 
   в корне проекта файл `.env` и внутри него прописать свои данные, см. образец ниже

```python
EVERNOTE_CONSUMER_SECRET = <your_code>
EVERNOTE_CONSUMER_KEY = <your_key>
EVERNOTE_PERSONAL_TOKEN = <your_personal_token>
JOURNAL_NOTEBOOK_GUID = GUID
JOURNAL_TEMPLATE_NOTE_GUID = GUID
INBOX_NOTEBOOK_GUID = GUID
```
## Установка

Используйте данную инструкцию по установке этого скрипта

1. Установить

```python
git clone https://github.com/Maxim-Pekov/evernote-example.git
```

2. Создайте виртуальное окружение:

```python
python -m venv venv
```

3. Активируйте виртуальное окружение:
```python
.\venv\Scripts\activate`    # for Windows
```
```python
source ./.venv/bin/activate    # for Linux
```

4. Перейдите в `evernote-example` директорию.

3. Установите зависимости командой ниже:
```python
pip install -r requirements.txt
```

---

## About me

[<img align="left" alt="maxim-pekov | LinkedIn" width="30px" src="https://img.icons8.com/color/48/000000/linkedin-circled--v3.png" />https://www.linkedin.com/in/maxim-pekov/](https://www.linkedin.com/in/maxim-pekov/)
</br>

[<img align="left" alt="maxim-pekov" width="28px" src="https://upload.wikimedia.org/wikipedia/commons/5/5c/Telegram_Messenger.png" />https://t.me/MaxPekov/](https://t.me/MaxPekov/)
</br>

[//]: # (Карточка профиля: )
![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Maxim-Pekov&theme=solarized_dark)

[//]: # (Статистика языков в коммитах:)

[//]: # (Статистика языков в репозиториях:)
![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Maxim-Pekov&theme=solarized_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Maxim-Pekov&theme=solarized_dark)


[//]: # (Статистика профиля:)

[//]: # (Данные по коммитам за сутки:)
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Maxim-Pekov&theme=solarized_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Maxim-Pekov&theme=solarized_dark)

[//]: # ([![trophy]&#40;https://github-profile-trophy.vercel.app/?username=Maxim-Pekov&#41;]&#40;https://github.com/ryo-ma/github-profile-trophy&#41;)

