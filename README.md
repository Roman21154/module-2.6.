n = int(input("ВВедите число от 3 до 20: "))
result: str = ''
for a in range(1, 21):
    for b in range(a + 1, 21):
        if n % (a + b) == 0 :
            result += str(a) + str(b)

print(result)
