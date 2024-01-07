

# Wildberries parser

Парсит все товары продавца с сайта https://www.wildberries.ru/. Сохраняет поля: 'id', 'название', 'цена', 'бренд', 'скидка', 'рейтинг', 'id продаца', 'ссылки на изображения' в csv файл.


## Установка

Для работы требуется Python 3.10+. Скопируйте проект и установите зависимости:

```bash
  pip install -r requirements.txt
```

## Запуск

Запустите parser.py или вызовите ParseWB("https://www.wildberries.ru/catalog/27605639/detail.aspx").parse() 
Замените на любой другой товар при необходимости


