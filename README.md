# Assignment_5
Data Structures and Strings in Python


# Step 1: Create dictionary
student_marks = {
    "Alice": 85,
    "Bob": 78,
    "Charlie": 92,
    "David": 88
}

# Step 2: Ask user for student name
name = input("Enter the student's name: ")

# Step 3 & 4: Check if student exists
if name in student_marks:
    print(f"{name}'s marks: {student_marks[name]}")
else:
    print("Student not found.")
