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
5. Generating a pattern using nested `for` loops

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

#### ✅ **Q5. Hourglass Star Pattern**

---

### 🔹 **Algorithm to Print Hourglass Star Pattern**

1. **Start**

2. Initialize `n = 5` (number of rows in half of the hourglass).

3. **Upper Half (Inverted Pyramid)**

   * Loop `i` from 0 to `n - 1`:

     1. Loop `j` from 0 to `i`:

        * Print a space `" "`.
     2. Loop `k` from `i` to `n - 1`:

        * Print `"* "` (star followed by space).
     3. Move to the next line.

4. **Lower Half (Regular Pyramid)**

   * Loop `i` from `n - 2` down to 0:

     1. Loop `j` from 0 to `i`:

        * Print a space `" "`.
     2. Loop `k` from `i` to `n - 1`:

        * Print `"* "` (star followed by space).
     3. Move to the next line.

5. **End**


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

#### ✅ **Q6. pattern no.2**

#### 🔹 **Algorithm:**

1. **Start**
2. Initialize `n = 5` (number of rows).
3. Use a loop (`i`) from 1 to `n`:

   * For each row `i`:
     4\. Use an inner loop (`j`) from 1 to `i`:

     * Print `" * "` (with space for formatting).

     5. Move to the next line (`cout << endl;`).
4. **End**

#### 🔹 **Output:**

```
 * 
 *  * 
 *  *  * 
 *  *  *  * 
 *  *  *  *  * 
```

---
#### ✅ **Q7.pattern no.3

#### 🔹 **Algorithm:**

1. **Start**
2. Initialize `n = 5` (number of rows).
3. Use a loop (`i`) from 1 to `n`:

   * For each row `i`:
     4\. Use a loop (`j`) from 1 to `(n - i)`:

     * Print a single space `" "` to shift stars right.

     5. Use another loop (`k`) from 1 to `i`:

        * Print `"*"` (no extra space between stars).
     6. Move to the next line (`cout << endl;`).
4. **End**

#### 🔹 **Output:**

```
    *
   **
  ***
 ****
*****
```

---



### 🔹 **Conclusion:**

Through these experiments, I have:

* Practiced using `for` and `while` loops for repeating tasks and condition-based logic
* Built a simple password verification system
* Learned how to use **nested `for` loops** to create structured patterns such as an hourglass

These programs have strengthened my understanding of loops in C++ and shown how they can be applied to solve both simple and complex problems.

---

