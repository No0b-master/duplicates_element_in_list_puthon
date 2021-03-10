# duplicates in a list in python using function 


unique = []
numbers=[]
n = int(input('No of elements : '))
for i in range(0,n):
    element=int(input(">>>"))
    numbers.append(element)


def duplicate(numbers):
        for number in numbers:
            if number not in unique:
                unique.append(number)
        return unique
print(f'list after removing duplicates :  {duplicate(numbers)}')

