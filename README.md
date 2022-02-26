# Учебный проект на Django: сайт с путешествиями
На данный момент реализована базовая функциональность сайта согласно заданию 1-ой недели курса.  
- Маршрутизация страниц тура `tour/<int:tour_id>`: каждая страница тура отличается от другой заголовком. При выборе несуществующего тура возвращается код ответа 404.
- Маршрутизация страниц отправления из города `departure/<str:departure_short_name>`: каждая страница отправления из города отличается от другой заголовком. При выборе несуществующего города отправления возвращается код ответа 404.  


## Развертывание проекта 

```shell
git clone https://github.com/che-a/stepik_tours.git
cd stepik_tours
python -m venv env
source env/bin/activate
python -m pip install --upgrade pip setuptools wheel
python -m pip install -r requirments.txt

# Запуск отладочного веб-сервера
python manage.py runserver
```
