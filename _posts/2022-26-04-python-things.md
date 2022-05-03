---
title: Неочевидные вещи в Python
tags: python
mathjax: true
---

Интересные и неочевидные конструкции в Python

<!--more-->

---

## Почему так?

```python
>>> data = {
  'test': {
    'test1' 'test2'
  }
}
>>>
>>> data
{'test': {'test1test2'}}
```
P.S. excepted syntax error


## Какой тип у type()? А у type(type())?
```python
type(1)
<class 'int'>
type(type(1))
<class 'type'>
type(type(type(1)))
<class 'type'>
```
