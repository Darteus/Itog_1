# Itog_1
## Создание репозитория на ГитХаб
## Блок-схема решения
<img width="799" alt="Снимок экрана 2023-11-18 в 17 57 58" src="https://github.com/Darteus/Itog_1/assets/138676156/cd952f11-e605-4264-b748-fc6c2fe9664f">
## Описание решения. Код решения
1) Создаем первоначальный массив 
- ввод числа (длина массива)
- ввод элементов массива

'''
Задача: Написать программу, которая из массива строк формирует новый массив из строк, длина которых <= 3 символам.
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“Russia”, “Denmark”, “Kazan”] → []
'''
- count_list = int(input('Введите количество элементов исходного списка: '))
- start_list = []
- for i in range(count_list):
    start_list.append(input('Введите элемент исходного списка: '))
  
2) Создаем функцию, решающую поставленную задачу, с формированием нового массива
   def new_list(list):
    final_list = []
    for element in list:
        if len(element) <= 3:
            final_list.append(element)
    return final_list
3) Вывод результата. Проверка решения
   print(start_list, '-> ', end ='')
   print(new_list(start_list))

<img width="1470" alt="Снимок экрана 2023-12-09 в 07 59 42" src="https://github.com/Darteus/Itog_1/assets/138676156/6fdcd154-9dce-4129-9a77-b748d3afc662">
