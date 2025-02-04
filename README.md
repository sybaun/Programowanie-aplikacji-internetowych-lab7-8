# Programowanie-aplikacji-internetowych-lab7-8

# Lab 7
## Instrukcje Uruchomienia Aplikacji

1. **Pobierz repozytorium z GitHub**:
```
git clone https://github.com/sybaun/Programowanie-aplikacji-internetowych-lab7-8
```

2. **Wchodzimy do folderu aplikacji**:
```
cd Programowanie-aplikacji-internetowych-lab7-8\book_catalog
```

3. **Instalujemy zależności**:
```
pip install django
```

4. **Uruchamiamy serwer Django**:
```
py manage.py runserver
```
---
# Lab 8
## Uruchimianie testów

1. **Instalujemy zależności**:
```
pip install selenium
pip install webdriver-manager
```
2. **Komenda dla uruchamienie wszystkich testów odrazu**:
```
py manage.py test books
```
 3. **Testy oddzielnie**:
```
1. py manage.py test books.tests.test_views
2. py manage.py test books.tests.test_models
3. py manage.py test books.tests.test_acceptance (robić przy uruchomionej aplikacji)
4. py manage.py test books.tests.test_integration
```
