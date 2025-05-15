# python-
Write a program to find the entered character is a vowel or a consonent,while user input could be either upper or lower case using if - elif-else
char=input("Enter an alphabet:")
char=char.lower()
if len(char)!=1 or not char.isalpha():
    print("Invalid input.please enter a single")
elif char in 'aeiou':
    print(f"'{char}' is a vowel.")
else:
    print(f"'{char}' is a consonant.")
