API_Final - финальная версия API для yatube. 

Запуск проекта:

-Клонировать репозиторий и перейти в него в командной строке:
git clone (ссылка на гит)
cd ... (Заходим в проект)
- Cоздаем и активируем виртуальное окружение:
python3.7 -m venv venv
source venv/bin/activate
- Установливаем зависимости из файла requirements.txt:
pip install -r requirements.txt
- Обновляем
python3.7 -m pip install --upgrade pip
- Выполняем миграции:
python3.7 manage.py migrate
- Запускаем проект:
python manage.py runserver