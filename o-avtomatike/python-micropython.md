---
description: программирование микроконтроллеров
---

# Python - Micropython

```python
// 
# Сохраните текст ниже в файл vashe_nazvanie.py
# набиретие в терминале python vashe_nazvanie.py
def fib(n):
    a, b = 0, 1
    while a < n:
        print(a, end=' ')
        a, b = b, a+b
        print()
fib(999999999)
#
fruits = ['Banana', 'Apple', 'Lime']
loud_fruits = [fruit.upper() for fruit in fruits]
print(loud_fruits)
#
print (1 / 2)

print (2 ** 3)

print (17 / 3)

print (17 // 3)
#
numbers = [2, 4, 6, 8]
product = 1
for number in numbers: product = product * number

print('The product is:', product)
#
print("Hello, I'm Python!") #py

name = input('What is your name?\\n')
print(f'Hi, {name}.')

```

{% hint style="info" %}
```
#Вывод будет таким - 
```

```
0 
```

```
1 
```

```
1 
```

```
2 
```

```
3 
```

```
5 
```

```
8 
```

```
13 
```

```
21 
```

```
34 
```

```
55 
```

```
89 
```

```
144 
```

```
233 
```

```
377 
```

```
610 
```

```
987 
```

```
1597 
```

```
2584 
```

```
4181 
```

```
6765 
```

```
10946 
```

```
17711 
```

```
28657 
```

```
46368 
```

```
75025 
```

```
121393 
```

```
196418 
```

```
317811 
```

```
514229 
```

```
832040 
```

```
1346269 
```

```
2178309 
```

```
3524578 
```

```
5702887 
```

```
9227465 
```

```
14930352 
```

```
24157817 
```

```
39088169 
```

```
63245986 
```

```
102334155 
```

```
165580141 
```

```
267914296 
```

```
433494437 
```

```
701408733 
```

```
['BANANA', 'APPLE', 'LIME']
```

```
0.5
```

```
8
```

```
5.666666666666667
```

```
5
```

```
The product is: 384
```

```
Hello, I'm Python!
```

```
What is your name?\nalexei        
```

```
Hi, alexei.
```
{% endhint %}
