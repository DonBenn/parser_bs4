# Парсер [документов PEP](https://peps.python.org/) с ипользованием BeatufilSoup4

Парсер ищет все [PEP](https://peps.python.org/) правила, подсчитывает количество
определенных статусов и выводит данные в CSV файл, либо в таблицу в терминале. 
Выбор запуска происходит через аргументы командной строки.

## Используемые технологии:

Python 3.9, BeatufilSoup4, requests-cache

## Как запустить проект

Клонировать репозиторий и перейти в него в командной строке:


```bash
git clone git@github.com:DonBenn/parser_bs4.git
```

## Cоздать и активировать виртуальное окружение:
```bash
cd parser_bs4/
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt
```

## Для запуска используйте команду
```bash
cd src/
python main.py [-h] [-c] [-o {pretty,file}] {whats-new,latest-versions,download,pep}
```

## Автор

Bessonov Denis (https://github.com/DonBenn)
