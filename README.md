# English

## Scrapy Parser

python 3.6

### Install

```bash
# Installing and running the virtual environment
python3 -m venv .env
source .env/bin/activate
# Install dependencies
pip install -r requirements.txt
```

### Settings

The custom_settings.py file should contain the settings necessary for the parser to work

- ALLOWED_DOMAINS = ['site.com']
- START_URLS = ['<https://site.com/users/index>']
- USER_LOGIN = 'login'
- USER_PASSWORD = 'password'

### Running

```bash
# We launch the corresponding parser from the folder. For example from the folder report
cd report
scrapy crawl report
# The collected data will be in the report.csv file
```

# Russian

## Parser на Scrapy

python 3.6

### Установка

```bash
# Устанавливаем и запускаем виртуальное окружение
python3 -m venv .env
source .env/bin/activate
# Инсталируем зависимости
pip install -r requirements.txt
```

### Настройки

В файле custom_settings.py должны храниться настройки необходимые для работы парсера

- ALLOWED_DOMAINS = ['site.com']
- START_URLS = ['<https://site.com/users/index>']
- USER_LOGIN = 'login'
- USER_PASSWORD = 'password'

### Запуск

```bash
# Запускаем из папки соответствующего парсера. Например из папки report
cd report
scrapy crawl report
# Собранные данные будут в файле report.csv
```
