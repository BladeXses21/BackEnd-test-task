# Завдання тестового завдання
```1angular2html
Це тестове завдання з метою оцінки навичок веб-розробки. 
Мета завдання - створити REST API, що надасть можливість керувати повідомленнями між двома користувачами.
```
## Опис завдання
```angular2html
Ми повинні надати додатку 2 моделі:
- Thread (поля - учасники, створено, оновлено)
- Message (поля - відправник, текст, тред, створено, прочитано)

Тред не може мати більше 2 учасників.

1. Необхідно реалізувати REST-точки для:
    - створення (якщо тред з певними користувачами існує - просто повернути його);
    - видалення треду;
    - отримання списку тредів для будь-якого користувача;
    - створення повідомлення та отримання списку повідомлень для треду;
    - позначення повідомлення як прочитаного;
    - отримання кількості непрочитаних повідомлень для користувача.

2. Налаштування Django адміністратора.
3. Надати пагінацію (LimitOffsetPagination), де це необхідно.
4. Валідація URL-адреси обов'язкова, коментарі вітаються.
5. Додати файл README.md з описом того, як запустити тестове завдання.
6. Створити дамп бази даних для завантаження тестових даних.
7. Надати доступ до проекту в GIT-репозиторії. (Публічний доступ)
```
### Вимоги:
```angular2html
Djangо, DRF
аутентифікація Simple JWT або Django Token;
база даних - SQLite.
```
## suport_education

### Project setup
#### встановіть python3 найновішої версії
#### добавте та активуйте virtualenv
```
pip install virtualenv
```
#### встановити залежності 
```
pip install -r requirements.tx
```
#### провести міграції 
```
python manage.py makemigrations
python manage.py migrate
```
#### запустити локальний сервер
```
python manage.py runserver
```
створіть два супер користувача
```
python manage.py createsuperuser
```
## project work

[перейдіть на сайт](http://localhost:8000).
#### в першому полі вводите ім'я першого юзера (себе)
#### в другому полі вводите ім'я другого юзера 
#### після цього вас перекидає в thread з користувачем.
