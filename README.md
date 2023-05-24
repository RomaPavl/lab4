# lab4
## Створення та налаштування проекту за допомогою pipenv

python version 3.8.10

flask version 2.3.2

## Завантаження 


Створивши пустий проект, далі додаємо залежності, якими будемо користуватись:
```commandline
pipenv install flask
pipenv install waitress
```
Щоб наше середовище стало активним, то потрібно ввести наступну команду:

```pipenv shell```
## Запуск сервера
Щоб подивитись результат нашої програми, нам потрібно заупустити сервер WSGI:
```waitress-serve --host 127.0.0.1 serve:cfaw```
За допомогою декоратора ```@app.route("/api/v1/hello-world-4")``` реалізуємо адресу.
Перейшовши на неї, бачимо текст "hello world 4"
http://localhost:5000/api/v1/hello-world-4


