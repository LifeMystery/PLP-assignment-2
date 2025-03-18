# PLP-assignment-2

# Python List Operations

This Python script demonstrates various list operations, including appending, inserting, extending, removing, sorting, and finding the index of an element.

## Tasks Performed

1. **Create an empty list** called `my_list`.
2. **Append elements**: 10, 20, 30, 40 to `my_list`.
3. **Insert an element** (15) at the second position in the list.
4. **Extend the list** with another list `[50, 60, 70]`.
5. **Remove the last element** from the list.
6. **Sort the list** in ascending order.
7. **Find the index** of the value `30` and print it.

## Code Explanation

```python
# Create an empty list called my_list
my_list = []

# Append the following elements to my_list: 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert the value 15 at the second position in the list
my_list.insert(1, 15)

# Extend my_list with another list: [50, 60, 70]
my_list.extend([50, 60, 70])

# Remove the last element from my_list
my_list.pop()

# Sort my_list in ascending order
my_list.sort()

# Find and print the index of the value 30 in my_list
index_of_30 = my_list.index(30)
print(f"The index of 30 in my_list is: {index_of_30}")
