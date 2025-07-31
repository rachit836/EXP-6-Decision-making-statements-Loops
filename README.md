Sure! Here's the **updated and combined experiment journal** with the **hourglass pattern** using nested `for` loops instead of the 5x5 star square.

---

## **Experiment Journal: Loop-Based Programs and Nested Loops in C++**

---

### 🔹 **Aim:**

To understand and implement basic and nested looping structures (`for` and `while` loops) in C++. The experiments include:

1. Printing even numbers from 0 to 10 using a `for` loop
2. Printing a sentence multiple times using a `for` loop
3. Printing numbers from 1 to 20 using a `while` loop
4. Creating a simple system locker using a `while` loop
5. Generating an hourglass pattern using nested `for` loops

---

### 🔹 **Tools Used:**

* Programiz C++ online compiler

---

### 🔹 **Theory:**

Loops in C++ execute a block of code repeatedly based on a condition. The two primary loop structures are:

* **`for` loop**: Used when the number of iterations is known. Combines initialization, condition check, and increment/decrement in one line.
* **`while` loop**: Used when the number of iterations is unknown and continues looping while a condition remains true.

---

#### ✅ **`for` Loop Syntax:**

```cpp
for(initialization; condition; increment/decrement) {
    // statements
}
```

---

#### ✅ **`while` Loop Syntax:**

```cpp
while(condition) {
    // statements
}
```

---

### 🔹 **Programs and Descriptions:**

---

#### ✅ **Q1. Print Even Numbers from 0 to 10 Using `for` Loop**

Prints even numbers by incrementing the loop counter by 2.

```cpp
for(int i = 0; i <= 10; i += 2) {
    cout << i << " ";
}
```

---

#### ✅ **Q2. Print a Sentence Using `for` Loop**

Prints the same sentence 5 times.

```cpp
for(int i = 1; i <= 5; i++) {
    cout << "This is a repeated sentence." << endl;
}
```

---

#### ✅ **Q3. Print Numbers from 1 to 20 Using `while` Loop**

Prints numbers from 1 to 20 using a condition-checked loop.

```cpp
int i = 1;
while(i <= 20) {
    cout << i << " ";
    i++;
}
```

---

#### ✅ **Q4. System Locker Using `while` Loop**

Simulates a password system that keeps prompting until the correct password `"admin123"` is entered.

```cpp
string password;
while(password != "admin123") {
    cout << "Enter password: ";
    cin >> password;
}
cout << "Access granted!";
```

---

### 🔹 **Nested `for` Loops: Hourglass Pattern**

---

#### ✅ **Theory:**

Nested `for` loops allow iteration over multiple levels, such as rows and columns. They are particularly useful for **pattern printing** tasks like hourglasses, pyramids, and diamonds.

---

#### ✅ **Example: Hourglass Star Pattern**

This program prints an hourglass pattern of stars using nested loops.

**Code:**

```cpp
int n = 5;

// Upper half
for(int i = n; i >= 1; i--) {
    for(int space = 0; space < n - i; space++) {
        cout << " ";
    }
    for(int star = 1; star <= 2*i - 1; star++) {
        cout << "*";
    }
    cout << endl;
}

// Lower half
for(int i = 2; i <= n; i++) {
    for(int space = 0; space < n - i; space++) {
        cout << " ";
    }
    for(int star = 1; star <= 2*i - 1; star++) {
        cout << "*";
    }
    cout << endl;
}
```

**Output:**

```
*********
 *******
  *****
   ***
    *
   ***
  *****
 *******
*********
```

---

### 🔹 **Conclusion:**

Through these experiments, I have:

* Practiced using `for` and `while` loops for repeating tasks and condition-based logic
* Built a simple password verification system
* Learned how to use **nested `for` loops** to create structured patterns such as an hourglass

These programs have strengthened my understanding of loops in C++ and shown how they can be applied to solve both simple and complex problems.

---

Would you like help adding variations of the hourglass, comments to the code, or visual explanations for how the loops work?
