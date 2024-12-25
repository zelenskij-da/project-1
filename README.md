# project-1
вторая ветка
Описание кода:
#Код из задания 6.2 курса
#Импортируем библиотеку пандас
import pandas as pd
def row_col_num(file):
    data = pd.read_csv(file)
    #Разделяем данные на столбцы и строки
    data.shape
    #Применяем к переменным значения количества строк и столбцов
    rows = data.shape[0]
    cols = data.shape[1]
    #Выводим значения
    return f'В таблице {rows} строк и {cols} столбцов'
