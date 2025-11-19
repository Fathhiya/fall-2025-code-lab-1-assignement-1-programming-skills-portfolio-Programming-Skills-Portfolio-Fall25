## Exercise 8: Simple Search - 30 Marks

names = ["Jake","Zac", "Ian", "Ron", "Sam", "Dave"]
name_search = input("Enter your name:")
if name_search in names:
    print(f"{name_search} is there on the list")
else:
    print(f"{name_search} is not there in the world")
