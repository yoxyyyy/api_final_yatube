API_Final - финальная версия API для yatube. 

Запуск проекта:

-Клонировать репозиторий и перейти в него в командной строке:
git clone (ссылка на гит)
```console
cd ... (Заходим в проект)
```
- Cоздаем и активируем виртуальное окружение:
python3.7 -m venv venv
```console
source venv/bin/activate
```
- Установливаем зависимости из файла requirements.txt:
```console
pip install -r requirements.txt
```
- Обновляем
```console
python3.7 -m pip install --upgrade pip
```
- Выполняем миграции:
```console
python3.7 manage.py migrate
```
- Запускаем проект:
```console
python manage.py runserver
```