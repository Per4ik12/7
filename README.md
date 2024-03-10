# 7
n = int(input("Введите число N: "))
count_zero = 0
for i in range(n):
    number = int(input("Введите число: "))
    if number == 0:
        count_zero += 1
print(f"Количество нулей: {count_zero}")
