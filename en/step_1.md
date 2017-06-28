There is a built-in module in the Python programming language called `random`. This module contains lots of useful methods for playing around with random numbers. One of its methods, called `choice`, allows the computer to choose a random item from a list.

If you want to use it, first import the `choice` method from the `random` library, and then create a list to use.

```python
from random import choice

my_list = [1, 3, 5, 7, 9]

my_num = choice(my_list)
```

You can see what the value of the `my_num` variable is by typing its name into the Python shell.

```python
>>> my_num
3
>>>
```

Any data that you can place inside a list can be selected with `choice()`. For instance, you might want to use strings:

```python
from random import choice

greetings = ['Hello there', 'How are you?', "What's up", 'Yo!']
			
my_greeting = choice(greetings)
```


