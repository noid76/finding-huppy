# python easy game not pygame
# finding huppy
print('hi my name is huppy you need to find me HIiIHIHII')
print('1_1 1_1 1_1 1_1 1_1 ')
print("please choose a number")
huppy = int(input('"1", "2", "3", "4", "5": '))
import random
huppy_position = random.randint(1,5)

if huppy_position == huppy:
    print("aaaa! why you can find me!")
elif huppy_position != huppy:
    print(f"haha you cannot find me! btw im at {huppy_position}")
