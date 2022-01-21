# CreateRofloCode
My beginner small python projects
#engcode
#byYama
import time



name = ['XJCompany', 'JavaCompany', 'YamaCompany']
print(name)
x = str(input("Choose a name for your company: "))
if x == 'XJCompany':
    print("You have selected the name XJCompany from the list\'name\'")
elif x == 'JavaCompany':
    print("You have selected the name JavaCompany from the list \'name\'")
    if x == 'YamaCompany':
        print("You have selected the name YamaCompany from the list \'name\'")

time.sleep(1)
print("Your task is to choose an employee who interferes with the work of this company, and you can also choose how to fire him")
time.sleep(1)
print("Names of employees.")
name2 = ['Ivan', 'Masha', 'Igor']
print(name2)
y = str(input("select an employee: "))
if y == 'Ivan':
    print("You have chosen Ivan's employee.")
if y == 'Masha':
    print("You have chosen Masha employee.")
elif y == 'Igor':
    print("You have chosen Igor's employee.")
time.sleep(1)
print("how do you want to fire an employee?")
time.sleep(1)
print("Scream")
time.sleep(1)
print("Dismiss the cute")
time.sleep(1)
print("dismiss quietly")
time.sleep(1)
i = str(input("how do you want to fire an employee?:"))
if i == "Scream":
    print("You punished an employee!")
if i == "Dismiss the cute":
    print("You punished an employee!")
elif i == "dismiss quietly":
    print("You punished an employee!")
time.sleep(1)
print("Вы наказали сотрудника! Игра окончена)")
time.sleep(2)










#бонусный разговор специально на русском)
#bonus conversation, specially in Russian)
print("Вы - Эй", y, "подойки ко мне, я хочу сказать что ты очень хорошо постарался на этой неделе, но ты УВОЛЕН!!!!")
time.sleep(2)
print("Сотрудник - Ч-Что??? Я же старался1!! Я так пахал на эту чертову", x, "и после этого вы хотите сказать что я уволен?")
time.sleep(2)
print("Вы - Да ты уволен, проваливай пока я не разозлился!")
time.sleep(1)
print("The End :D")
