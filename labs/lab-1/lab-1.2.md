---
layout: default_no_header
title: Подсчёт слов
---

> Каждое приключение требует первого шага.

## Теория  

Вам предоставлен текст "Алиса в стране чудес" на английском языке. Чтобы открыть этот файл, напишите следуюую программу

```python
with open('alice.txt', 'r') as file:
    text = file.read()

print(text)
```

## Задача  

Требуется открыть файл `alice.txt` и вывести 20 наиболее встречающихся в нём слов.

<a class="btn-download" href="{{site.baseurl}}/resources/labs/lab-1/alice.txt">Скачать текст</a>


