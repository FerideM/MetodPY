# MetodPY

![](https://pluralsight.imgix.net/paths/python-7be70baaac.png?w=100)   
> _«Высокоуровневый язык программирования, в основе проектировния которого лежит философия о читабельности кода и синтаксисе, позволяющем программистам выражать свои идеи в нескольких строках кода»._ - Гвидо ван Россум, создатель языка Python.


Причины изучать Python


## Синтаксис
- Переменные
```
#integer
one = 1

# booleans
true_boolean = True
false_boolean = False

# string
name = "Sam"

# float
book_price = 15.80
```
- Математичексие операции
```
a+b
a*b
a/b
a%b #mod(a,b)
a**2 #pow(a,2)

```
- Импортирование библиотек и функций
```
import math
ptint(math.pi) #3.141592653589793

from math import pi
ptint(pi) #3.141592653589793

import math as m
ptint(m.pi) #3.141592653589793

from math import pi as PI
ptint(PI) #3.141592653589793
```
- Условия
```
if 1 > 2:
  print("1 is greater than 2")
elif 2 > 1:
  print("1 is not greater than 2")
else:
  print("1 is equal to 2")
```
- Циклы 
```
#while loop
num = 1
while num <= 10:
    print(num)
    num += 1

#for loop
for i in range(1, 11):
  print(i)
```
- Списки
```
my_integers = [5, 7, 1, 3, 4, 'Hello']
print(my_integers[1]) # 7
print(my_integers[5]) # Hello

#add to a List
bookshelf = []
bookshelf.append("The Effective Engineer")
bookshelf.append("The 4 Hour Work Week")
print(bookshelf[0]) # The Effective Engineer
```
- Словари

Структура данных с доступом не по индексу, а по ключу.
```
dictionary_tk = {
  "name": "Leandro",
  "nickname": "Tk",
  "nationality": "Brazilian",
  "age": 24
}

print("My name is %s" %(dictionary_tk["name"])) # My name is Leandro
print("But you can call me %s" %(dictionary_tk["nickname"])) # But you can call me Tk
print("And by the way I'm %i and %s" %(dictionary_tk["age"], dictionary_tk["nationality"])) # And by the way I'm 24 and Brazilian
```
_Name, nickname, nationality, age_ - Ключи

_Leandro, Tk, Brazilian, 24_ - Значения.
```
dictionary_tk = {
  "name": "Leandro",
  "nickname": "Tk",
  "nationality": "Brazilian"
}
#add to a Dictionary
dictionary_tk['age'] = 24

print(dictionary_tk) # {'nationality': 'Brazilian', 'age': 24, 'nickname': 'Tk', 'name': 'Leandro'}
```

- Итераторы

Циклы по структуре данных.
```
#list
my_integers = [5, 7, 1, 3, 4, 'Hello']
for i in my_integers:
  print(i)
  
#dictionary
dictionary = { "some_key": "some_value" }

for key in dictionary:
    print("%s --> %s" %(key, dictionary[key]))    # some_key --> some_value
```
Метод _**iteritems**_:
```
#another way for dictionaries
dictionary = { "some_key": "some_value" }
for key, value in dictionary.items():
    print("%s --> %s" %(key, value))

# some_key --> some_value
```

