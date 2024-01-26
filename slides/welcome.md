---
layout: presentation
title: Course overview
permalink: /slides/welcome/
---

class: center, middle

# Welcome

Intro to Computer Science

---

# Agenda

1. [Introductions](#introductions)
2. [What you know you knew](#know-knew)
3. [What you didn't know you knew](#didnt-know-knew)
4. [What you knew you didn't know](#knew-didnt-know)
5. [What you didn't know you didn't know](#didnt-know-didnt-know)
6. [How this course works](#how-course-works)
7. [What to do now](#do-now)
8. [Conclusions](#conclusions)

---

name: introductions

# Introductions

---

template: introductions
name: introductions-1

## This course

Introduction to Computer Science

- Syllabus: [syllabus](../../syllabus)
- Schedule: [schedule](../../)

---

template: introductions-1

Official description:

> How to design algorithms to solve problems and how to translate these algorithms into working computer programs. Experience is acquired through projects in a high-level programming language. Intended primarily for computer science majors but also suitable for students of other scientific disciplines. Programming assignments.

---

template: introductions

## Me

Daniel Zint

email: daniel.zint@nyu.edu

---

template: introductions

## You

- An aspiring programmer?
- An aspiring computer scientist?
- Interested in making things and solving problems?
- Willing to spend hours by yourself reading and **staring at code**.

---

template: introductions

## Computer science

The study of the theory and practice of computation. Very open-ended.

```python
not programming == computer_sciencing
```

```python
computer_sciencing.find(computers) == -1
```

```python
computer_sciencing not in sciences
```

---

name: know-knew

# What you know you knew

---

template: know-knew

## Data types

Programs usually think of data in terms of rigid stereotypes.

- integers
- floating point numbers
- booleans
- strings
- lists
- dictionaries/hash tables/associative arrays
- nonetypes/null/nil

Review [data types](https://nyu-python-programming.github.io/course-material/data-types).

---

template: know-knew

## Input and output

There are many ways to input and output data from / to external sources.

```python
response = input("What's brown and sticky?")
```

```python
print("'{}' is correct!".format(response.capitalize()))
```

Review [input and output](https://nyu-python-programming.github.io/course-material/input-output).

---

template: know-knew

## Boolean logic and decision-making

Programs can adapt to context.

```python
if this or that and the_other is not also_that:
    thats_wonderful()
```

Review [boolean logic](https://nyu-python-programming.github.io/course-material/boolean-logic) and [decision-making](https://nyu-python-programming.github.io/course-material/decision-making).

---

template: know-knew

## Functions

Functions are modular blocks of code usually designed to perform a single task.

```python
def thats_wonderful():
    print("That's wonderful")
```

Review [functions](https://nyu-python-programming.github.io/course-material/functions).

---

# What you know you knew

## Modules

A module is a reusable library of code.

```python
# import random module
import random

def thats_wonderful():
    # use a function from the random module
    if random.randint(1,10) > 5:
        print("That's wonderful")
    else:
        print("Okay...")
```

Review [modules](https://nyu-python-programming.github.io/course-material/modules).

---

# What you know you knew

## For loop and while loops

You have choices when repeating blocks of code.

```python
for i in range(10):
    print("Welcome!")
```

```python
i = 0
while i < 10:
    print("Welcome!")
    i = i + 1
```

Review [for loops](https://nyu-python-programming.github.io/course-material/loops-for) and [while loops](https://nyu-python-programming.github.io/course-material/loops-while).

---

# What you know you knew

## Lists

Lists are useful for storing a set of related values.

```python
favorite_foods = [
    "Pizza with glyphosate-coated bleached wheat flour and soy cheese",
    "Coffee with GMO corn syrup solids added",
    "Emulsified non-fat sugar-free ice cream with artificial sweetener"
    ]
```

Review [lists](https://nyu-python-programming.github.io/course-material/list-basics) and [more lists](https://nyu-python-programming.github.io/course-material/list-more).

---

# What you know you knew

## Dictionaries

Dictionaries contain key/value pairs.

```python
phone_numbers: {
    "Foo Barstein": "646-888-5623",
    "Baz Foo":      "212-717-3297",
    "Bar Baz":      "747-211-8451"
}
```

Review [dictionaries](https://nyu-python-programming.github.io/course-material/dictionary-basics) and [more dictionaries](https://nyu-python-programming.github.io/course-material/dictionary-more).

---

# What you know you knew

## Text files

Data can be stored and retrieved from text files.

```python
# open file in read mode
f = open('data.csv', 'r')
```

```python
# print out each line of the file
for line in f:
    data = line.split(",")
```

Review [text files](https://nyu-python-programming.github.io/course-material/text-files).

---

# What you know you knew

## Strings

Languages offer many ways to analyze and manipulate text data.

```python
text = "This,That,The other"
text = text.lower()
pos = text.find(",")
if pos > 0:
    data = text.split(",")
```

Review [strings](https://nyu-python-programming.github.io/course-material/string-basics) and [string formatting](https://nyu-python-programming.github.io/course-material/string-formatting).

---

name: didnt-know-knew

# What you didn't know you knew

---

# What you didn't know you knew

## Variables, literals, expressions, and function calls

There are many ways to express value in programs.

```python
"I am literally a literal"
```

```python
I_am_not
```

```python
math.pow(washington, 2) + park
```

Review [variables, literals, and expressions](https://nyu-python-programming.github.io/course-material/variables-literals-expressions).

---

# What you didn't know you knew

## Dot notation

Dots indicate belongingness.

```python
random.randint(5, 10)
```

```python
math.pow(2, 2)
```

```python
'help me'.islower()
```

---

# What you didn't know you knew

## Other languages

Try to convince me that you don't understand this code:

```javascript
let x = 5
let y = true
if (x < 10 || y === true) {
  console.log("Easy peasy!")
}
```

```java
int x = 5;
boolean y = true;
if (x < 10 || y == true) {
    System.out.println("Easy peasy!");
}
```

---

name: knew-didnt-know

# What you knew you didn't know

---

# What you knew you didn't know

A popular way to think about programs with interacting parts.

- Object-oriented programming

```python
you = new Student("Jane Doe")
```

```python
me = new Professor("Daniel Zint")
```

```python
me.say_hello(you)
```

Jump ahead half a semester to [object-oriented programming](../../slides/object-orientation)

---

name: didnt-know-didnt-know

# What you didn't know you didn't know

---

template: didnt-know-didnt-know
name: didnt-know-1

## Basic computer concepts and terminology

Can you answer these questions?

- What is a file? What is a folder?

--

- What are good names for files and folders?

--

- How do you use the command line?

--

- What is a compiler? What is an interpreter? An assembler?

--

- What is an operating system? What is an application?

--

- What is the Internet? What is The World Wide Web?

--

- What is The Cloud?

--

Review [basic computer concepts](https://nyu-python-programming.github.io/course-material/basic-computer-concepts).

---

# What you didn't know you didn't know

## Alias vs. copy

What is printed?

```python
x = 5
y = x
x = 10
print(y)
```

Try it out yourself.

---

# What you didn't know you didn't know

## Raw strings

How many lines are printed?

```python
x = "First line\nSecond line"
print(x)
```

```python
x = r"First line\nSecond line"
print(x)
```

Learn about [raw strings](https://nyu-python-programming.github.io/course-material/string-raw).

---

# What you didn't know you didn't know

## Multidimensional arrays

```python
row1 = [1, 2, 3]
row2 = [4, 5, 6]
row3 = [7, 8, 9]
```

```python
data = [row1, row2, row3]
```

```python
print(data[1][2])
```

Jump ahead half a semester to [multi-dimensional arrays](../../slides/arrays-multidimensional).

---

# What you didn't know you didn't know

## Recursion

How many times is the function called?

```python
def foo(x):
  if x < 3:
      foo(x+1)
      foo(x+1)

foo(1)
```

Jump ahead almost a semester to [recursion](../../slides/recursion).

---

# What you didn't know you didn't know

## You can place out of this class

If you are comfortable with

- multi-dimensional arrays,
- object-oriented programming, and
- recursion

Consider taking a placement exam to skip this course.

Learn about [placement exams](https://cs.nyu.edu/home/undergrad/placement_sample_exams.html).

---

name: how-course-works

# How this course works

---

template: how-course-works
name: how-course-works-1

## Lecture

I will speak for 75 minutes about twice each week.... that's 150 minutes of talking each week.

--

Please interrupt me and ask questions.

- Lectures are far more effective when there's two-way communication

---

template: how-course-works

## Notes

[Amos Bloomberg](https://knowledge.kitchen) provides notes for most lecture
topics. You may find them useful but incomplete.

- The notes pertinent to any lecture are found on the [schedule](./../schedule).

You find all the material to his courses on [Knowldedge Kitchen](https://knowledge.kitchen/).

---

template: how-course-works

## Reading

Reading assignments from [the textbook](../../syllabus#textbook) and elsewhere each class. The textbook is quite thorough.

---

template: how-course-works

## Assignments

You will have 8 assignments.

Assignments that are handed in late are not graded --> **0 points**!

---

template: how-course-works
name: extensions

## Extensions

There are no extensions.

---

template: how-course-works

## Quizzes

Regular simple multiple-choice online quizzes. These are meant to help you self-assess your own mastery of conceptual material.

---

template: how-course-works

## Exams

You will take 3 exams.

- Two midterms
- One final

Many find the first exam to be easy. The second and third... not so much!

Students who come to class tend to do better.

---

template: how-course-works

## Grading

- 10% quizzes
- 15% assignments
- 20% first exam
- 25% second exam
- 30% third exam

---

template: how-course-works

## Communication

We use Brightspace for all communication outside of the classroom.

---

template: how-course-works

## Tutoring

Tutors are waiting to answer your questions virtually all day every day of the week.

See them often. See them fast.

The tutor's schedule will be posted on Brightspace once available.

---

# What to do now

---

# What to do now

## Review the syllabus

The [syllabus](../../syllabus) contains basic information on how this course works.

---

# What to do now

## Bookmark the schedule

The [schedule](../../schedule) contains a day-by-day breakdown of everything you need to know and do in this course.

---

# What to do now

## Download and Install JDK

The Java Development Kit (JDK) is a necessary set of tools that help develop Java programs. Install the Standard Edition (SE).

https://www.oracle.com/java/technologies/downloads/

---

# What to do now

## Download and install Visual Studio Code

Visual Studio Code is an Integrated Development Environment (IDE) that integrates with the JDK to allow you to easily write and debug Java programs.

https://code.visualstudio.com

---

# What to do now

## Download and install the Extension Pack for Java

These extensions to Visual Studio Code make it suitable for Java programming.

https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack

---

# What to do now

## Install a Terminal

- Git for Windows additionally comes with Git Bash, which gives Windows users a UNIX-like command shell.
- WINDOWS USERS - you should use Git Bash or Windows Subsystem for Linux (WSL) rather than Windows' default Powershell or other command line shell program. To set Git Bash or WSL as the default terminal shell within Visual Studio Code, you can try to follow the instructions in [the second answer here](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal) by **Mahade Walid** and edited by **FruityOatyBar** (ignore the first answer, which is outdated).
- Mac and Linux users already have a UNIX command shell in the Terminal app.

---

name: conclusions

# Conclusions

--

- Welcome!

--

- Start to think like a compiler... or is it an interpreter... or an assembler?

--

```python
print("There's no reason to worry... {}".format("yet!"))
```
