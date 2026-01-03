name = input("Enter your name: ")
age_input = input("Enter your age: ")
food = input("Enter your favorite food: ")

if not name:
    print("You didn't enter a name.")
elif not age_input:
    print("You didn't enter an age.")
elif not food:
    print("You didn't enter your favorite food.")
else:
    age = int(age_input)
    print(f"Yo! My name is {name}, I'm {age} years old and my favorite food is {food}.")
