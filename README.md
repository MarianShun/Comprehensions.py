# Comprehensions.py
import sys

C = sys.argv[1:]

def spaces(i):
    return ' '*(7-len(i))

for i in C:
    if '/'<i<':':
        print(spaces(i), i, ':', float(i)*9/5+32)
    else:
        print(spaces(i), i, ':', 'Not a number')
