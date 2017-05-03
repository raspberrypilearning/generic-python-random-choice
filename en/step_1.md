## Choosing random items from a list in Python

There is a built-in module in the Python programming language called `random`. This module contains lots of useful methods for playing around with random numbers. One feature of the module is the ability to allow the computer to choose a random item from a list.

To use this feature you must first import the `choice` method from the `random` class, and then create a list to use.

```python
from random import choice

my_list = [1, 3, 5, 7, 9]

my_num = choice(my_list)
```

You can then see what the value of `my_num` is by typing the name into the Python shell.

```python
>>> my_num
3
>>>
```

Any data that can be placed inside a list can be selected with `choice()`. For instance, you might want to use strings:

```python
from random import choice

greetings = ['Hello there',
	         'How are you?',
		     "What's up",
			 'Yo!']
			
my_greeting = choice(greetings)
```


