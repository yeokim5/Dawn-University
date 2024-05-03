

pure functions
return value

side effect functions
no return -> return None
ex) print()


**Using Python***
- python -i ex.py : run interactily
- python -m doctest ex.py
- python -m doctest -v ex.py for hw


abstraction of function



**Q&A**
- don't just press next next next.
try to guess and if it's correct good if not there's misunderstanding between your thought and the concept. that part is where you need understanding

- global variable is kinda suck it can get things confusing



# **LAB 2***

using ok:
- python ok -q function : run doctest
- python ok -v: all test
- python ok --submit

**Topics**
- functions: operator, operand
- print and return

When Python evaluates `(1+1) and 1`, it checks both operands. Since both operands are truthy, the `and` operator returns the second operand, which is `1`.

both operands are False. Since the left operand is already False, Python doesn't need to evaluate the right operand, and it returns False.


----


**Lab1 틀린거**

Control
```
>>> def how_big(x):
...     if x > 10:
...         print('huge')
...     elif x > 5:
...         return 'big'
...     elif x > 0:
...         print('small')
...     else:
...         print("nothin")
>>> how_big(7)
? big
-- Not quite. Try again! --

? 'big'
-- OK! --

-------------------------------------------------------------------------------
>>> True and 13
? True
-- Not quite. Try again! --

? False
-- Not quite. Try again! --

? 13
-- OK! --
-------------------------------------------------------------------------------
>>> positive = 28
>>> while positive: # If this loops forever, just type Infinite Loop
...    print("positive?")
...    positive -= 3
? positive
-- Not quite. Try again! --

? Infinite Loop
-- OK! --
-------------------------------------------------------------------------------
>>> False or 0
? False
-- Not quite. Try again! --

? 0
-- OK! --
-------------------------------------------------------------------------------
>>> True and 0  # If this errors, just type Error.
? False
-- Not quite. Try again! --

? True
-- Not quite. Try again! --

? 0 
-- OK! --
-------------------------------------------------------------------------------
>>> 0 or False or 2 or 1 / 0  # If this errors, just type Error.
? 0
-- Not quite. Try again! --

? True
-- Not quite. Try again! --

? 2
-- OK! --
-------------------------------------------------------------------------------
>>> (1 + 1) and 1  # If this errors, just type Error. If this is blank, just type Nothing.
? 2
-- Not quite. Try again! --

? True
-- Not quite. Try again! --

? 1
-- OK! --
-------------------------------------------------------------------------------
>>> (True or False) and False  # If this errors, just type Error. If this is blank, just type Nothing.
? True
-- Not quite. Try again! --

? True
-- Not quite. Try again! --

? False
-- OK! --
-------------------------------------------------------------------------------
Q: In the following traceback, what is the most recent function call?
Traceback (most recent call last):
    File "temp.py", line 10, in <module>
      f("hi")
    File "temp.py", line 2, in f
      return g(x + x, x)
    File "temp.py", line 5, in g
      return h(x + y * 5)
    File "temp.py", line 8, in h
      return x + 0
  TypeError: must be str, not int
Choose the number of the correct choice:
0) g(x + x, x)
1) h(x + y * 5)
2) f("hi")
? 2
-- Not quite. Try again! --

Choose the number of the correct choice:
0) g(x + x, x)
1) h(x + y * 5)
2) f("hi")
? 1
-- OK! --
-------------------------------------------------------------------------------

```

Veritasiness

Debugging Quiz


