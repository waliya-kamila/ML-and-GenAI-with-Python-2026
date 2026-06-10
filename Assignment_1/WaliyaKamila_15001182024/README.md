# 1. Find area of rectangle
length = float(input("Enter length: "))
width = float(input("Enter width: "))
area = length * width
print("Area of rectangle:", area)

# 2. Find simple interest
principal = float(input("Enter principal: "))
rate = float(input("Enter rate (%): "))
time = float(input("Enter time (years): "))
si = (principal * rate * time) / 100
print("Simple Interest:", si)

# 3. Convert Celsius to Fahrenheit
celsius = float(input("Enter temperature in Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print("Temperature in Fahrenheit:", fahrenheit)

# 4. Calculate average of 3 numbers
a = float(input("Enter number 1: "))
b = float(input("Enter number 2: "))
c = float(input("Enter number 3: "))
average = (a + b + c) / 3
print("Average:", average)

# 5. Find square and cube of a number
num = float(input("Enter a number: "))
print("Square:", num ** 2)
print("Cube:", num ** 3)

# 6. Swap two numbers WITHOUT third variable
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
print("Before swap: a =", a, ", b =", b)
a, b = b, a
print("After swap: a =", a, ", b =", b)

# 7. Student Report Program
# Taking student details using input()
name = input("Enter student name: ")
roll = input("Enter roll number: ")

# Store marks in variables
marks1 = float(input("Enter marks in Subject 1: "))
marks2 = float(input("Enter marks in Subject 2: "))
marks3 = float(input("Enter marks in Subject 3: "))

# Calculate total and percentage
total = marks1 + marks2 + marks3
percentage = (total / 300) * 100

# Display report with proper indentation and comments
print("\n--- Student Report ---")
print("Name:", name)
print("Roll Number:", roll)
print("Marks - Sub1:", marks1, "| Sub2:", marks2, "| Sub3:", marks3)
print("Total Marks:", total)
print("Percentage:", percentage, "%")
