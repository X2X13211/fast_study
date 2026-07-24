---
{"dg-publish":true,"permalink":"/selenium-python/poisk-elementov-bez-by/","dg-note-properties":{}}
---

Ранее мы использовали стандартные методы, затем научились использовать пакет **By,** но существует еще один способ, как по мне, он максимально прост, понятен и удобен.  
  
Тут все просто, сразу приведу пример:

```bash
driver.find_element("id", "login_field")
```

То есть вместо пакета **By**, мы используем текстовые значения и нет необходимости делать какие либо дополнительные импорты.  
  
Список обозначений для использования вместо **By**:

```ini
ID = "id"
XPATH = "xpath"
LINK_TEXT = "link text"
PARTIAL_LINK_TEXT = "partial link text"
NAME = "name"
TAG_NAME = "tag name"
CLASS_NAME = "class name"
CSS_SELECTOR = "css selector"
```
[[selenium_python/Что такое Xpath и как с ним работать\|Что такое Xpath и как с ним работать]]