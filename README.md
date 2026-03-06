# Assignment_5---- 
Task 1
Data Structures and Strings in Python

student_marks = {
    "Alice": 85,
    "Bob": 78,
    "Charlie": 92,
    "David": 88
}
name = input("Enter the student's name: ")

if name in student_marks:
    print(f"{name}'s marks: {student_marks[name]}")
else:
    print("Student not found.")

Task 2
numbers = list(range(1, 11))

first_five = numbers[:5]

reversed_list = first_five[::-1]

print("Original list:", numbers)
print("Extracted first five elements:", first_five)
print("Reversed extracted elements:", reversed_list)
