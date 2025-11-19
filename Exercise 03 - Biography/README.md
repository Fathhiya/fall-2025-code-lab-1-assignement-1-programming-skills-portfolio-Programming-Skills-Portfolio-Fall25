## Exercise 3: Biography - 25 Marks

name = str(input("Enter your name:"))
hometown = str(input("Enter your hometown:"))
age = int(input("Enter your age:"))
information={
    "Name":name,
    "Hometown":hometown,
    "Age":age}
print(f"Name: {information['Name']} \nHometown: {information['Hometown']} \nAge: {information['Age']}")