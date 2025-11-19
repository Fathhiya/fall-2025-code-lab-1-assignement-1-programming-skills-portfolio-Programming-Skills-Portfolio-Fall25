## Exercise 4: Primitive Quiz - 30 Marks

information = {
    "France": "Paris",
    "Germany": "Berlin",
    "Italy": "Rome",
    "Spain": "Madrid",
    "Portugal": "Lisbon",
    "Netherlands": "Amsterdam",
    "Switzerland": "Bern",
    "Belgium": "Brussels",
    "Austria": "Vienna",
    "Greece": "Athens"
}

mark = 0

for country, capital in information.items():
    answer = input(f"What is the capital of {country}? ")
    if answer.strip().lower() == capital.lower():
        print("Your answer is correct!")
        mark += 1
    else:
        print(f"Wrong! The correct answer is {capital}.")
print(f"\nYou got {mark} out of {len(information)} correct!")