---

theme: simple
paginate: true
header: 'Header'
footer: 'Footer'

---
<!-- _class: lead -->
# Sample slide deck
Sample slide deck converted from MarkDown by Marp Next.   

@ttyskg

---

## List structures
test text text
* List
* List
* List
  * Sublist
  * Sublist

---

## Table

|      | col1 | col2 | col3 |
| ---- | ---- | ---- | ---- |
| row1 | item | item | item |
| row2 | item | item | item |
| row3 | item | item | item |

---

## Figure insert

This is my icon.

![](./img/icon.png)

Cute owl!

---

## Code block
FizzBuzz by Python.
```python
def FizzBuzz(n):
    for i in range(n):
        num = i + 1
        if (num % 15) == 0:
            print('FizzBuzz')
        elif (num % 5) == 0:
            print('Buzz')
        elif (num % 3) == 0:
            print('Fizz')
        else:
            print(num)
```
---

## Math block

Marp Next support KaTex format to wirte Math equations.

$$
\frac{\partial \theta}{\partial t}= \frac{\partial}{\partial z}
\left[ K(\theta) \left (\frac{\partial \psi}{\partial z} + 1 \right) \right]
$$

