## Exercise 5: Days of the Month - 30 Marks

month = {
    1:31,
    2:28,
    3:31,
    4:30,
    5:31,
    6:30,
    7:31,
    8:31,
    9:30,
    10:31,
    11:30,
    12:31}

x = int(input("Enter your month:"))

if 1 <= x <= 12:
    if x == 2:
        leap = input("Is it a leap year?:")
        if leap == "yes":
            print("February has 29 days")
        else:
            print("February has 28 days")
    else:
        print(f"Month {x} has {month[x]} days.")
else:
    print("This month  doesn't exist.")