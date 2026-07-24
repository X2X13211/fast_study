---
{"dg-publish":true,"permalink":"/selenium-python/poluchenie-tekushhego-url-straniczy/","dg-note-properties":{}}
---

В дальнейшем, вам пригодится команда для получения URL-адреса страницы из адресной строки браузера, например для того чтобы убедиться в том, что действительно открыта нужная вам веб-страница.  
  
Это можно сделать обратившись к атрибуту **current_url**.

```undefined
driver.current_url
```

Для удобства Вы можете записать его в переменную для дальнейшего использования:

```bash
PAGE_URL = driver.current_url # Получаем текущий URL-адрес в переменную

print(PAGE_URL) # Выводим значение переменной
```
[[selenium_python/Валидация данных - assert\|Валидация данных - assert]]