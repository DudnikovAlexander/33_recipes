<h2 align="center">Справочник рецептов</h2>
Группа ЦПИбв-51
Вариант: 33 
Тема: Справочник рецептов

Шаблон: https://freehtmlthemes.ru/categories/food/template-587

### Инструменты разработки

**Стек:**
- Python >= 3.10
- Django >= 4.1.1
- sqlite3

## Разработка

##### 1) Клонировать репозиторий

    git clone https://github.com/DudnikovAlexander/33_recipes.git

##### 2) Создать виртуальное окружение

    python -m venv venv
    
##### 3) Активировать виртуальное окружение

##### 4) Устанавливить зависимости:

    pip install -r requirements.txt

##### 5) Выполнить команду для миграций

    python manage.py migrate
    
##### 6) Создать суперпользователя

    python manage.py createsuperuser
    
##### 7) Запустить сервер

    python manage.py runserver