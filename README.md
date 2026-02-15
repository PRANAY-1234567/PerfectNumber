# 📘 README — Perfect Number Checker (Python)

## 📌 Description

This Python program checks whether a given number is a **Perfect Number** or not.

A **Perfect Number** is a number that is equal to the sum of its **proper divisors** (excluding the number itself).

👉 Example:
6 → divisors are **1, 2, 3**
Sum = 1 + 2 + 3 = **6** → So it is a Perfect Number.

---

## ⚙️ Code

```python
num = 6
sum = 0

for i in range(1, num):
    if num % i == 0:
        sum += i

if sum == num:
    print("Perfect Number")
else:
    print("Not Perfect")
```

---

## 🧠 Step-by-Step Explanation (Very Simple)

### 1️⃣ Store the number

```python
num = 6
```

This is the number we want to check.

---

### 2️⃣ Create a variable to store sum

```python
sum = 0
```

This will store the total of divisors.

---

### 3️⃣ Loop from 1 to number-1

```python
for i in range(1, num):
```

We check all numbers **before 6**.

---

### 4️⃣ Check if divisor

```python
if num % i == 0:
```

If remainder = 0 → it means **i divides num**.

---

### 5️⃣ Add divisor to sum

```python
sum += i
```

For 6:

* 1 divides → add → sum = 1
* 2 divides → add → sum = 3
* 3 divides → add → sum = 6

---

### 6️⃣ Compare sum with number

```python
if sum == num:
```

If equal → Perfect Number.

---

## ▶️ Output

```
Perfect Number
```

---

## ✅ Examples of Perfect Numbers

| Number | Divisors   | Sum |
| ------ | ---------- | --- |
| 6      | 1,2,3      | 6   |
| 28     | 1,2,4,7,14 | 28  |

---

## 💡 Key Concept Learned

* Loops
* Modulus operator `%`
* Condition checking
* Number logic

---

## 🚀 Real-World Use

This type of logic is used in:

* Mathematics programs
* Coding interviews
* Logic building practice

---

