import random

letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
symbols = ['!', '#', '$', '%', '&', '(', ')', '*', '+']

user_letters = int(input("How many letters would you like in your password? \n"))
user_numbers = int(input("How many numbers would you like in your password? \n"))
user_symbols = int(input("How many symbols would you like in your password? \n"))

# password = ''

# for i in range(1, user_letters + 1):
    # password += (random.choice(letters))
# for i in range(1, user_numbers + 1):
    # password += (random.choice(numbers))
# for i in range(1, user_symbols + 1):
    # password += (random.choice(symbols))
# print(password)

# MORE EFFICICENT !
password = []
random_letters = random.choices(letters, k=user_letters)
random_numbers = random.choices(numbers, k=user_numbers)
random_symbols = random.choices(symbols, k=user_symbols)
password.extend(random_numbers + random_symbols + random_letters)
random.shuffle(password)
final_password = ''
for i in password:
    final_password += i
print(f"This is your password: {final_password}")
