immutable_var = (1, 'строка', 3.14, True)
print("Кортеж immutable_var:", immutable_var)
try:
    immutable_var[0] = 2
except TypeError as e:
    print("Ошибка при попытке изменения кортежа:", e)
mutable_list = [1, 'строка', 3.14, True]
print("Исходный список mutable_list:", mutable_list)
mutable_list[0] = 2
mutable_list[1] = 'новая строка'
print("Измененный список mutable_list:", mutable_list)
