# 1

## 🧪 1st Small Exercise (Important)

Without running Python, tell me the result.

If:

```text
player = "paper"
computer = "rock"
```

What will this line return?

```python
win_rules[player]
```

A)

```text
paper
```

B)

```text
rock
```

C)

```text
scissors
```

Think carefully and answer.
This small question will show whether you **fully understand dictionaries**, which are **very important for Python and AI programming later**.

## Answer Review:

Abid, good attempt — but the correct answer is **❌ not B**.

The correct answer is **✅ C — scissors**.

Let’s understand **why**.

---

## 🧠 Look at the Dictionary

```python
win_rules = {
    "rock": "scissors",
    "scissors": "paper",
    "paper": "rock"
}
```

This means:

```
rock beats scissors
scissors beats paper
paper beats rock
```

---

## Now Evaluate the Expression

You were asked what this returns:

```python
win_rules[player]
```

If:

```
player = "paper"
```

Then Python checks:

```
win_rules["paper"]
```

Look inside the dictionary:

```
"paper": "rock"
```

So the result is:

```
rock
```

Wait — this means **B is actually correct** based on the dictionary above. Let’s clarify carefully.

---

## Correct Step-by-Step

```
player = "paper"
```

Python evaluates:

```
win_rules[player]
```

Which becomes:

```
win_rules["paper"]
```

Dictionary value:

```
"paper": "rock"
```

So the result is:

```
rock
```

✔ **So your answer B was correct.**

Good thinking. 👍

---

## Why This Matters

Now check this condition in the program:

```python
elif win_rules[player] == computer:
```

Example:

```
player = paper
computer = rock
```

Step-by-step:

```
win_rules["paper"] → rock
```

Then Python checks:

```
rock == rock
```

Result:

```
True
```

So the program prints:

```
You win this round
```

Because **paper beats rock**.

# 2

## 🎯 Your Next Small Challenge

Without running Python, tell me the result of this:

```
player = "scissors"
computer = "paper"
```

What will this condition evaluate to?

```python
win_rules[player] == computer
```

A)

```
True
```

B)

```
False
```

Think step-by-step like a programmer and answer.

## Answer Review:

Abid, **yes — you are correct again. ✅**

Your answer **A (True)** is right.

Let’s verify it step-by-step like a programmer.

---

## Step 1 — Look at the dictionary

```python
win_rules = {
    "rock": "scissors",
    "scissors": "paper",
    "paper": "rock"
}
```

This means:

```
rock → beats scissors
scissors → beats paper
paper → beats rock
```

---

## Step 2 — Substitute the value

You said:

```
player = "scissors"
computer = "paper"
```

Python evaluates:

```python
win_rules[player]
```

which becomes:

```python
win_rules["scissors"]
```

Dictionary result:

```
paper
```

---

## Step 3 — Compare

Now Python checks:

```
paper == paper
```

Result:

```
True
```

So the program enters:

```
You win this round
```

✔ Your reasoning was correct.
