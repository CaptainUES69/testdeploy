# **Для корректного запуска требуется:**
## 1) Создание зависимостей

**Windows**
```
Python -m venv venv
venv/scripts/activate
pip install -r req.txt
```
**Linux**
```
cd backend
Python -m venv venv
source venv/bin/activate
pip install -r req.txt
```
## 2) Создание .env файл в папке src с содержимым вида:
```
DBROOT = 'sqlite+aiosqlite:///src/db.sqlite3'
HASH_KEY = 'Here is hash key'
FPATH = "(ДИСК)\wsforum\frontend"
```
## 3) Запуск приложения
```
Python -m src.main
```
#   t e s t d e p l o y  
 #   t e s t d e p l o y  
 