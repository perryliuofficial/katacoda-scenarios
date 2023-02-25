# Week 1 Step 2 Strings & Input Answers:
* Ask the user for their favourite colour.
* Print that variable.
* Optional: Chain it by putting input() inside of a print statement so you only need 1 line of code

# Quick Exercise
## 1.
```python
colour = input("What is your favourite colour? ")
print("You answered: " + colour)
```

## 1. Optional
```python
print("You answered: " + input("What is your favourite colour? "))
```

# Test your knowledge:
## 1.
Ask the user for a name (eg Tom) and ask user for an emotion (eg happy).  Print out “<name> is feeling <emotion>.”  Eg “Tom is feeling happy.”.
```
name = input("What is your name? ")
emotion = input("How are you feeling? ")
print(name + " is feeling " + emotion + ".")
```

### 1.1 Extend your program to print out 2 lines – “Pleased to meet you Tom./n Tom is feeling happy today!”
```
name = input("What is your name? ")
emotion = input("How are you feeling? ")
print("Please meet " + name + ".\n" + name + " is feeling " + emotion + " today!")
```

## 2. Extra challenge
* Write a short story (just 1 paragraph) about a character learning how to code. Write it out on paper first.
* Write a program to ask user for a name and ask user what pronouns to use (ie he/him/she/her).  Print your story using the users names and pronouns so that it makes sense.
```
name = input("What is your character's name? ")
pronoun = input("What is your character's pronoun? e.g. he/her/she/her
print(name + " had just started to learn python, " + pronoun + " were really enjoying it and learning lots of useful information.")
```