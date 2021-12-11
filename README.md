Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

'''
git clone https://github.com/MSonini/api_final_yatube.git
cd api_final_yatube
'''

Cоздать и активировать виртуальное окружение:

python -m venv venv
source venv/bin/activate


Установить зависимости из файла requirements.txt:

pip install -r requirements.txt
Выполнить миграции:

python3 manage.py migrate
Запустить проект:

python3 manage.py runserver
