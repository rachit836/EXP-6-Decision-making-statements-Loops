

##  **Experiment Journal: Loop-Based Programs in C++**

---

### 🔹 **Aim:**

To understand and implement basic programs using looping structures (`for` and `while` loops) in C/C++. The programs covered:

1. Printing even numbers from 0 to 10 using `for` loop
2. Printing a sentence using `for` loop
3. Printing numbers from 1 to 20 using `while` loop
4. System locker using `while` loop

---

### 🔹 **Tools Used:**

* Programiz c++ compiler

---

### 🔹 **Theory:**

In C++, **loops** are used to execute a block of code repeatedly under a certain condition. There are mainly three types of loops:

* `for` loop
* `while` loop


#### ✅ **Definition of `for` loop:**

A `for` loop is used when the number of iterations is known. It combines initialization, condition checking, and increment/decrement in one line.

**Syntax:**

```cpp
for(initialization; condition; increment/decrement) {
    // statements
}
```

#### ✅ **Definition of `while` loop:**

A `while` loop is used when the number of iterations is not known in advance. It checks the condition before executing the loop body.

**Syntax:**

```cpp
while(condition) {
    // statements
}
```

---

### 🔹 **Program Descriptions, Syntax, and Definitions:**

---

### ✅ **Q1. Printing Even Numbers from 0 to 10 using `for` loop**

**Definition:**
Even numbers are divisible by 2. A `for` loop can be used to iterate through numbers and print even ones.

**Syntax:**

```cpp
for(int i = 0; i <= 10; i += 2) {
    cout << i << " ";
}
```

---

### ✅ **Q2. Printing a Sentence using `for` loop**

**Definition:**
You can use a `for` loop to repeat a sentence multiple times, such as for display or repetition-based tasks.

**Syntax:**

```cpp
for(int i = 1; i <= 5; i++) {
    cout << "This is a repeated sentence." << endl;
}
```

---

### ✅ **Q3. Printing Numbers from 1 to 20 using `while` loop**

**Definition:**
A `while` loop executes as long as the given condition is true. It is ideal for printing a range when the upper bound is clear.

**Syntax:**

```cpp
int i = 1;
while(i <= 20) {
    cout << i << " ";
    i++;
}
```

---

### ✅ **Q4. System Locker using `while` loop**

**Definition:**
This simulates a password-locked system where access is granted only when the correct password is entered. A `while` loop helps repeat the login prompt until successful.

**Syntax:**

```cpp
string password;
while(password != "admin123") {
    cout << "Enter password: ";
    cin >> password;
}
cout << "Access granted!";
```

---

### 🔹 **Conclusion:**

In this set of experiments, we practiced the use of `for` and `while` loops in C++. We successfully:

* Printed number sequences
* Repeated messages
* Simulated a basic password-protected system

This helped reinforce our understanding of looping mechanisms and how to apply them in real-world logic.

---


