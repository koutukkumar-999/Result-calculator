# Result-calculator
#That is a mini result calculator
result = input('enter result')
result = int(result)
if result == 100:
    print('gradeb = A+')
elif 90 <= result < 100:
    print('grade = A')
elif 70 <= result < 90:
    print('grade = B')
elif 50 <= result < 70:
    print('grade = C')
elif 30 <= result < 40:
    print('grade = D')
else:
    print('fail')
