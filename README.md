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



Output:
![image](https://user-images.githubusercontent.com/62955737/110631230-4c660d00-81cc-11eb-886b-c3606a9e012e.png)
