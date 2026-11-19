#OFFICE EMPLOYEE SYSTEM
print("EMPLOYEE ATTENDANCE SYSTEM")

name = input("Enter Employee Name: ")

attendance = input("Enter Attendance (P/A): ")

if attendance == "P":
    print(name, "is Present")

elif attendance == "A":
    print(name, "is Absent")

else:
    print("Invalid Attendance")

print("Thank You!")
