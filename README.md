# task4exercises

EX1:
n=[12,14,16,18,20]
print("List created!")
print(n)
n.insert(3,17)
print("List after adding an item to the list:")
print(n)
n.remove(14)
print("List after deleting an item from the list:")
print(n)
print("The largest number in the list:")
n1=max(n)
print(n1)
print("The smallest number in the list:")
n2=min(n)
print(n2)

OUTPUT FOR EX1:
C:\Users\Dell\PycharmProjects\pythonProject\venv\Scripts\python.exe C:/Users/Dell/PycharmProjects/pythonProject/task4ex1.py
List created!
[12, 14, 16, 18, 20]
List after adding an item to the list:
[12, 14, 16, 17, 18, 20]
List after deleting an item from the list:
[12, 16, 17, 18, 20]
The largest number in the list:
20
The smallest number in the list:
12

Process finished with exit code 0




EX2:
ntuple=(20,21,22,23,24,25)
print("Tuple before reversing:")
print(ntuple)
ntuple=tuple(reversed(ntuple))
print("Tuple after reversing:")
print(ntuple)

OUTPUT FOR EX2:
C:\Users\Dell\PycharmProjects\pythonProject\venv\Scripts\python.exe C:/Users/Dell/PycharmProjects/pythonProject/task4ex2.py
Tuple before reversing:
(20, 21, 22, 23, 24, 25)
Tuple after reversing:
(25, 24, 23, 22, 21, 20)

Process finished with exit code 0





EX3:
ntuple=("friday",16)
print("Tuple created!")
print(ntuple)
nlist=list(ntuple)
print("Converted list from tuple:")
print(nlist)

OUTPUT FOR EX3:
C:\Users\Dell\PycharmProjects\pythonProject\venv\Scripts\python.exe C:/Users/Dell/PycharmProjects/pythonProject/task4ex3.py
Tuple created!
('friday', 16)
Converted list from tuple:
['friday', 16]

Process finished with exit code 0
