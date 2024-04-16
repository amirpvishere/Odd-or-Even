# Odd-or-Even
def num(x):
    x = int(x)
    if x % 2 == 0:
        print('Your number is even')
    else:
        print('Your number is odd')
while True:
    x = input('Enter a number: ')
    num(x)
