## NOTE: We will be running our code in [Python Playground](https://www.online-python.com/KXmLvup8J6#google_vignette)


# Lesson 1: Variables and Constants

- variables store information (like a name or age).

- Constants are unchangeable values (like ```PI = 3.14```.

- Show examples in Python:
```python
name = "John"
age = 25
print(name)
print(age)
```
[Python Playground](https://www.online-python.com/RJV5Z1i4DU)


## 🧪 Activity: Variable Mad Libs Game
**Step-by-Step**:

1. Open Python Playfround.
2. Erase existing code.
3. Add the following starter code:

```
 
# Step 1: Declare variables

name = "Alex"
animal = "dragon"
place = "castle"
verb = "danced"

# Step 2: Use the variables in a story

print("Once upon a time, " + name + " saw a " + animal + " at the " + place + ".")
print("They " + verb + " together until sunset.")

```

3. Run your program to see the output.

[Python Playground](https://www.online-python.com/Q6pTX7u5fH)

4. Change the variable values to create different stories.
5. Optional: Add one constant (e.g., ```MAGIC_WORD = "Abracadabra")```


# Lesson 2 Conditionals

1. Open a new Python Playground.
2. Erase existing code.
3. Add this starter code.

```

# Step 1: Get user input

color = input("Pick a color (red, blue, green): ")


# Step 2: Use conditionals

if color == "red":

         print("You will find a surprise today!")

elif color == "blue":

         print("A new opportunity is coming your way.")

elif color == "green":

         print("You will learn something exciting.")

else:
    print("Hmm… the future is unclear.")

```

[Python Playground](https://www.online-python.com/S36DhaRjgx)

3. Run the program and test with different inputs.
4. Customize it: Add your own questions and responses.


# 🔹 Lesson 3 Loops (30 min)


📖 Mini-Lesson:
- Loops repeat code.

- Use ```for``` for a set number of times, ```while``` for repeating until a condition is met.


## 🧪 Activity A: Triangle of Stars
***Step-by-Step***:

1. Start a new file in Python Playground.

2. Paste this code:

```

# Step 1: Use a for loop to print a triangle

for i in range(1, 6):

        print("*" * i)

```

[Python Playground](https://www.online-python.com/rgHS3tqFc6)

3. Modify the range to make a bigger or smaller triangle.

4. Optional Challenge: Use ```input``` to let the user choose the height.

## 🧪 Activity B: Number Guesser
**Step-by-Step**:

1. Open new file in Python Playground.

2. Add this code:

```

# Step 1: Set secret number
secret = 7
attempts = 0

# Step 2: While loop for 3 tries
while attempts < 3:
    guess = int(input("Guess the number (1-10): "))
    if guess == secret:
        print("🎉 You got it!")
        break
    else:
        print("Try again!")
    attempts += 1

if guess != secret:
    print("Out of tries! The number was", secret)

```
[Python Playground](https://www.online-python.com/PSBUGt3VMg)

3. Run the code and test guessing.

4. Challenge: Let the user choose how many tries they get!

# 🔹 4. Mini Projects (25 min)


## 🧪 Project: Simple Quiz App
**Step-by-Step**:

1. Ask 5 questions using ```input()```.

2. Use conditionals to check if answers are correct.

3. Use a variable to count the score.


```

score = 0

q1 = input("What is 2 + 2? ")
if q1 == "4":
    print("Correct!")
    score += 1
else:
    print("Oops!")

q2 = input("What is the capital of France? ")
if q2.lower() == "paris":
    print("Correct!")
    score += 1
else:
    print("Nope!")

print("Your score is", score, "/ 2")

```

[Python Playground](https://www.online-python.com/DcMTped805)

## 🧪 Project: Virtual Pet
**Step-by-Step**:

1. Ask user to name their pet. Ask user for their name.

2. Use 4 variables to track pet happiness.

3. Use a loop and conditionals to simulate taking care of the pet.

```

name = input("Name your pet: ")
happiness = 5

for i in range(3):
    action = input("Feed or Play? ").lower()
    if action == "feed":
        happiness += 2
    elif action == "play":
        happiness += 3
    else:
        happiness -= 1

print(name + "'s happiness level is:", happiness)

```
[Python Playground](https://www.online-python.com/eYfS4CabqD)


# 🔚 Wrap-Up (5 min)
1. Ask students to share what they built

2. Encourage them to customize projects at home

# SUBMISSION

1. Submit the URL to your code for the 2 Projects from the Python Playground.
2. Submit the URL to your code for the 2 Activities from the Python Playground.
3. Submit the URL to your code for the Mini-Lessons from the Python Playground.
- Add the 2 URLs to the Assignment where indicated in Canvas for credit and a Certificate.

# SURVEY

Please complete the short 5 question survey in Canvas.

**Thanks a bunch**,
Dr. Vicki



