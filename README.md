# List example
fruits = ['apple', 'banana', 'cherry']
fruits.append('orange')
fruits[1] = 'blueberry'
print(fruits)  # ['apple', 'blueberry', 'cherry', 'orange']
# Tuple example
coordinates = (10.5, 20.3)
print(coordinates[0])  # 10.5

# coordinates[0] = 12.0  # ❌ This will raise a TypeError
# Range example
for i in range(3):
    print(i)
# Output: 0, 1, 2
# Mutability example
a = [1, 2, 3]
b = a
b[0] = 100
print(a)  # [100, 2, 3] – a changed because b points to the same list

# But with immutables:
x = 5
y = x
y = 10
print(x)  # 5 – x stays the same
