# lab4
## Створення та налаштування проекту за допомогою pipenv

python version 3.8.6

flask version 2.2.2

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

##ссилочки

https://github.com/shymanskyivm/Labs_For_Application_Programming/tree/main/Lab%206
https://github.com/shymanskyivm/Labs_For_Application_Programming/tree/main/Lab%207
https://github.com/shymanskyivm/Labs_For_Application_Programming/tree/main/Lab%208
https://github.com/shymanskyivm/Labs_For_Application_Programming/tree/main/Lab%209
