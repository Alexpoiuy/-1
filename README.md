m = int(input("Введите трёхзначное число: "))
number = m//100 + (m%100)//10 + m%10
print(number)