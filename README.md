# ml

Имеется датасет с объявлениями о продаже квартир в городе Новосибирске. 

В таблице всего 15000 строк, соответствующих разным квартирам, и 37 столбцов с признаками.

После удаления выбросов: 13836 строк

Категориальные признаки: Тип рынка и Функциональная зона


![image](https://github.com/user-attachments/assets/549d783c-0013-46a9-9816-4908dbb4350d)
![image](https://github.com/user-attachments/assets/0644ce5d-633f-4330-afcc-56cf50468a6b)



# Результат работы модели:

MdAPE для линейной регрессии: 15.28%

MdAPE для Лассо регрессии: 15.29%

MdAPE для Ридж регрессии: 15.29%

Среднеквадратическое отклонение: 867427656.23

R-квадрат: 0.30

# K-NN:

![image](https://github.com/user-attachments/assets/7cf8e96d-f3dc-4e7b-a9bd-6dcaacbce5af)


Среднеквадратическое отклонение: 508400682.25

R-квадрат: 0.59

MdAPE на обучающих данных: 7.53%

MdAPE на тестовых данных: 8.77%

# Дерево решений:


![image](https://github.com/user-attachments/assets/6b50cefc-1725-41be-b35e-3e9a6af4ee6e)


Среднеквадратическое отклонение: 442229835.49

R-квадрат: 0.64

MdAPE на обучающих данных: 7.01%

MdAPE для дерева принятия решений: 8.20%

Лучший результат показало дерево решений
