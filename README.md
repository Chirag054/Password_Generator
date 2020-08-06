# Password_Generator

import string
import random

a: tuple = random.choice(string.ascii_letters)
b: tuple = random.choice(string.ascii_lowercase)
c: tuple = random.choice(string.ascii_uppercase)
d: tuple = random.choice(string.digits)
e: tuple = random.choice(string.punctuation)


for i in range(7):
    value = random.choice(a+b+c+d+e)
    print(value,end="")
