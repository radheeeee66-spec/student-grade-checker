name = input("Enter your name")
marks = int(input("Enter your marks"))

if marks >= 90:
    result = "Excellent"
elif marks >= 75:
    result = "Very Good"
elif marks >= 50:
    result = "Pass"
else:
    result = "Fail"

print(name)
print(marks)
print(result)