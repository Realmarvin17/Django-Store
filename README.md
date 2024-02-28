# **Веб приложение Django Store** 

#### **Стек**
![python version](https://img.shields.io/badge/Python-3.10-green)
![django version](https://img.shields.io/badge/Django-4.1-green)




<details>
<summary>
<b>Запуск проекта в dev-режиме 
</summary>
Инструкция ориентирована на операционную систему windows и утилиту git bash.<br/>
Для прочих инструментов используйте аналоги команд для вашего окружения.

1. Клонируйте репозиторий и перейдите в него в командной строке:

```
git clone git@github.com:Realmarvin17/Django-Store.git
```

2. Установите и активируйте виртуальное окружение
```
python -m venv venv
``` 
```
source venv/Scripts/activate
```
```
cd store
```
3. Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
```

4. В папке с файлом manage.py выполните миграции:
```
python manage.py migrate
```

5. В папке с файлом manage.py запустите сервер, выполнив команду:
```
python manage.py runserver
```
