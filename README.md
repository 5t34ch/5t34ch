- 👋 Hi, I am @5t34ch
- 👀 I am interested in the specific areas of focus that Python and C++ influence and crossover in regards to LLMs and the way they talk to machines.
- 🌱 I am currently learning Python 3 and C++. I am barely starting out and am looking for any resources or direction that would point me towards what would make the most sense to learn next. I am using an LLM to write different learning plans and work through introductions to concepts of both Python and C++
- 💞️ I am looking to collaborate. 
- 📫 How to reach me - u/eldaveed6fiddy on reddit.

import random

# step 1: create a list
number_10 = [random.randint(1, 297) for _ in range(10)]
print("random #'s list: ", "\n", number_10)


# step 2: define is_even
def is_even(number):
    return number % 2 == 0


# step 3: use filter
even_numbers = list(filter(is_even, number_10))
print("even #'s list: ", "\n", even_numbers)

# step 4: use list comp
squares = [pow(i, 2) for i in even_numbers]
print("list of squares of even #'s: ", "\n", squares)


# step 5: define is_odd
def is_odd(number):
    return number % 2 != 0


# step 6: use filter and is_odd
odd_numbers = list(filter(is_odd, number_10))
print("odd #'s list: ", "\n", odd_numbers)

# step 7: use list comp again
cubes = [pow(i, 3) for i in odd_numbers]
print("list of cubes of odd #'s: ", "\n", cubes)


<!---
5t34ch/5t34ch is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
