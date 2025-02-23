---
date:
    created: 2025-10-01
categories:
    - Ciberseguridad
    - Radar
    - Divulgación
tags:
    - tag1
    - tag2
authors: 
    - david
    
---
![K](./img/test.png)

# CÓDIGO.MD


Primer resumen

<!-- more -->

``` py title="bubble_sort.py" linenums="1" hl_lines="4-5"
def bubble_sort(items):
    for i in range(len(items)): 
        for j in range(len(items) - 1 - i): # (1)
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.

Esto es un ejemplo de `#!python range()`código en la línea

PRUEBA DE ANOTACIONES

``` yaml
theme:
  features:
    - content.code.annotate # (2)
```

1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be written in Markdown.