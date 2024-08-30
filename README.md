- 👋 Hi, I’m Webster@netro93
- 👀 I’m interested in creating python codes
- 🌱 I’m currently learning python
- 💞️ I’m looking to collaborate on any coding and deburging
- 📫 How to reach me: Whatsapp me or call on +27815317919, or email bhoromawebster@gmail.com
- ⚡ Fun fact: All developers start by developing bugs then debug them to create a running code with no errors. # Programming is a world of try,error and corrections.

<!---
Netro93/Netro93 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
import random

Below is the python lottery program. Now to run this program you need to have python installed on your compute
--import random

lucky_numbers = []
user_numbers = []

correct_numbers = 0

print('Welcome To Lucky Lottery Numbers')
print('Enter 5 Numbers:')

# For generating random lucky numbers
for num in range(0,5):
    random_num = random.randint(1, 100)
    lucky_numbers.append(random_num)

# For getting user numbers
for num in range(0,5):
    user_num = int(input())
    user_numbers.append(user_num)

# For checking if got any lucky numbers
for lucky_num in lucky_numbers:
    for user_num in user_numbers:
        if user_num == lucky_num:
            correct_numbers = correct_numbers + 1

print(f'You got {correct_numbers} correct numbers')

print(f'Result: {lucky_numbers}')->
