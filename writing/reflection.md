# CS101 Spring 2026 — Practice Midterm Reflection

Name: Austin Aspenwall  
Date: 03/20/2025

After completing the practice test, please reflect on your experience by
answering the questions below. Replace each `` with a thoughtful response
(a few sentences each). Your responses help you consolidate what you learned
and identify areas to review before the real midterm.

---

## 1. Self-Assessment

**Question:** How did you feel about your performance on the practice test?
Which topics felt most comfortable, and which ones felt most difficult?

**Your Answer:**

I felt pretty confident on my answers, but I did want to check that I got them correct, since I only have about a over 1 1/2 semester of programming with python but still learning and understanding what everything does in a flow. The most difficult one was probably knowing how lambda worked in a program mathematically and what sends out the key-value or the true value for a dictionary.

---

## 2. Tricky Questions

**Question:** Identify one question you got wrong (or were unsure about).
Explain the concept being tested and describe why the correct answer is right.

**Your Answer:**
The 2 questions that I was stuck/unsure on were,
values = (3, 5, 2, 8, 4)
total = 0
for v in values:
    total += v
print(total)
-- And
d = {"p": 3, "q": 4}
d["r"] = d["p"] * d["q"]
print(d)

The concept of the first question is a variable set to a tuple, where it goes into a for loop for every position in the tuple in added onto the value until there are no more value lefts to loop through that tuple and print the totaled value of all integers in the tuple. So that total = 3, + 5 = 8, + 2 = 10, + 8 = 18, + 4 = 22 so the finql outcome/answer would be 22.

The second concept is a dictionary set to where we have key-value:value of d = {p: 3 and p: 4}, and so when we do       d["r"]= d["p"] * d["q"], we are essentialy adding a new key-value "r" into the dictionary where the value of that key-value is the the value of "p" time the value of "q" and when we do print(d) we are printing out the updated dictionary so it will print out, {"p": 3, "q": 4, "r": 12} which would be the final answer.

---

## 3. Loops and Iteration

**Question:** In your own words, explain the difference between `range(a, b, step)`
with a positive step versus a negative step. Give one original example of each.

**Your Answer:**

range(a,b,steps | steps > 0) basically makes it so you count up from the first postion to the postion after the the last number you want to end and the positive number counts upwards, but you need a < b to count up and then to count backwards its the same style but you need a > b and the step to be negative. Example: 

Upwards: for i in range(4, 9, 1):
    print(i)
Backwards: for i in range(8, 3, -1):
    print(i)


---

## 4. Data Structures

**Question:** Python has lists, tuples, dictionaries, and sets. Describe one key
difference between a list and a tuple, and one key difference between a
dictionary and a set. When would you choose each?

**Your Answer:**

list and tuples the key difference is that lists can be mutable/changing and unordered, while tuples are immutable/unable to change and are ordered. A key difference between a set and a dictionary and set set is also that dictionaries are mutable and sets are immutable.

---

## 5. Functions

**Question:** What is a default parameter in a Python function? Write a short
example function that uses a default parameter, and explain what happens when
the caller omits that argument.

**Your Answer:**
the default parameter is whater is set in a function.

---

## 6. List Comprehensions

**Question:** List comprehensions can include an optional filter condition.
Rewrite the following traditional loop as a list comprehension:

```python
result = []
for n in range(1, 11):
    if n % 3 == 0:
        result.append(n * 2)
```

**Your Answer:**

results = [n * 2 for n in range (1,11) if n % 3 == 0]

---

## 7. Operator Precedence

**Question:** Python evaluates `**` (exponentiation) right-to-left.
What is the value of `2 ** 2 ** 3`? Show your step-by-step reasoning.

**Your Answer:**

The value of 2 ** 2 ** 3 is 2 with the exponent of 2 with the exponent of 3 so first thing you do is do the 2 exponent of 3 which is 2 ^ 3 = 8 which will cause 2 *8 2 ** 3 to become 2 ** 8 which is 2 to the exponent of 8 which =  256.

---

## 8. Classes 

**Question:** What are classes in Python programming? Explain why they are necessary in programming.

**Your Answer:**

Classes are like blueprints to use when given an instance of a name or given piece of data that you flow through to build off of. THey are necessary if you have multiple different sets of data used for different unique programs in your code and allows them to run through it more efficiently and organized.

---

(Did you remember to add your name and date at the top of this document?)
