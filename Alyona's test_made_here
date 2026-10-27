N = input("Введите число N: ")
if N.isdigit():
    N = int(N)
    if N < 2:
        print("Число должно быть не меньше 2. Попробуйте ещё раз.")
    else:
        i = 2
        while i <= N:
            j = 2
            while j < i:
                if i % j == 0:
                    break
                j = j + 1
            if j == i:
                print(i)
            i = i + 1
else:
    print("Некорректный ввод")
