# list-operation-01-
# Accesing a list
fruit=["apple","Banana","cherry","guava"]
print(fruit[0])
print(fruit[-1])
print(fruit[:3])
print(fruit[:])
# modifying a list
fruit[3]="grapes"
print(fruit)
fruit[4]="mango"
print(fruit)
# Adding elements
fruit.append("Pine apple")
fruit.append("Custed apple")
fruit.insert(0,"Amla")
fruit.insert(1,"Bonda")
print(fruit)
# Removing an elements
fruit.remove("Amla")
fruit.remove("Bonda")
fruit.pop(3)
print(fruit)
fruit.clear()
print(len(fruit))

# Slicing list
numbers=[0,1,2,3,4,5,6,7,8,9]
print(numbers[0:8])
print(numbers[-1:-7])
print(numbers[-1: :])
print(numbers[::2])
print(numbers[:])
print(numbers[:8])
print(len(numbers))
print(reverse=true)
print(sorted(numbers))
numbers.sort()
print(numbers)



















