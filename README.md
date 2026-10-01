# ⚡ C Recursion — 50 Practical Programs

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/Programs-50-00C853?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Topic-Recursion-FF6F00?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Level-Beginner--Intermediate-7C4DFF?style=for-the-badge" />
</p>

<p align="center">
  <b>🧠 Learn Recursion • 💻 Practice C • 🎯 Prepare for Practical Exams</b>
</p>

---

## 🚀 About This Repository

Welcome to my **C Recursion Practical Programs** repository!

This collection contains **50 carefully selected recursion-based programs in C**, designed to strengthen problem-solving skills and provide practical preparation for programming laboratory examinations.

The programs start with basic recursive concepts and gradually move toward **numbers, arrays, strings, searching, patterns, and mathematical problems**.

> 💡 **One repository. 50 problems. One core concept — Recursion.**

---

## 🧩 What You'll Find

| #  | Category        | Topics                                |
| -- | --------------- | ------------------------------------- |
| 🔢 | Number Problems | Factorial, Power, Fibonacci, GCD, LCM |
| 🔁 | Basic Recursion | 1→N, N→1, sums, counting              |
| 🧮 | Digit Problems  | Sum, product, reverse, prime digits   |
| 📦 | Arrays          | Sum, min, max, search, reverse        |
| 🔤 | Strings         | Reverse, length, vowels, consonants   |
| 🔍 | Searching       | First occurrence, last occurrence     |
| ⭐  | Patterns        | Star patterns, number patterns        |
| 🧠 | Logic Building  | Palindrome, prime, binary conversion  |

---

# 📚 50 Practical Programs

### 🔹 Basic Recursion

* [01] Print 1 to N
* [02] Print N to 1
* [03] Sum of First N Natural Numbers
* [04] Factorial of a Number
* [05] Power of a Number
* [06] Count Digits
* [07] Sum of Digits
* [08] Reverse a Number
* [09] Check Palindrome Number
* [10] Fibonacci Series

### 🔹 Mathematical Recursion

* [11] Check Prime Number
* [12] GCD of Two Numbers
* [13] LCM of Two Numbers
* [14] Decimal to Binary
* [15] Product of Digits
* [16] Sum of Even Numbers
* [17] Sum of Odd Numbers
* [18] Print Even Numbers
* [19] Print Odd Numbers
* [20] Count Zero Digits

### 🔹 Array Recursion

* [21] Sum of Array Elements
* [22] Maximum Element in Array
* [23] Minimum Element in Array
* [24] Reverse an Array
* [25] Check Array Palindrome
* [26] Search an Element in Array
* [32] Sum Elements at Even Positions
* [38] Count Occurrences
* [39] First Occurrence
* [40] Last Occurrence
* [41] Print Array in Reverse
* [44] Product of Array Elements
* [45] Average of Array Elements
* [48] Minimum Element in Array

### 🔹 String Recursion

* [27] Count Digits in a String
* [28] Reverse a String
* [29] Find Length of a String
* [30] Count Vowels
* [43] Count Consonants

### 🔹 More Recursion Problems

* [31] Multiplication Table
* [33] Print Digits of a Number
* [34] Count Even Digits
* [35] Repeated Digit Sum
* [36] Count Steps to Zero
* [37] Star Pattern
* [42] Sum of Odd Digits
* [46] Binary to Decimal
* [47] Sum of Prime Digits
* [49] Number Pattern
* [50] Sum Between Two Numbers

---

# 🧠 Understanding Recursion

Recursion is a technique where a function **calls itself** to solve a smaller version of the same problem.

Every recursive solution generally contains two important parts:

```c
void function(int n)
{
    // Base Case
    if (n == 0)
        return;

    // Recursive Case
    function(n - 1);
}
```

### 🔥 The Two Essential Parts

```text
             RECURSIVE FUNCTION
                    │
          ┌─────────┴─────────┐
          ▼                   ▼
     BASE CASE          RECURSIVE CASE
          │                   │
     Stop recursion      Call itself
```

Without a proper **base case**, recursion can continue indefinitely.

---

# ⚙️ Example — Factorial

Mathematically:

```text
5! = 5 × 4 × 3 × 2 × 1
```

Recursive definition:

```text
factorial(n) = n × factorial(n - 1)
```

C implementation:

```c
int factorial(int n)
{
    if (n <= 1)
        return 1;

    return n * factorial(n - 1);
}
```

Execution:

```text
factorial(5)
     ↓
5 × factorial(4)
     ↓
5 × 4 × factorial(3)
     ↓
5 × 4 × 3 × factorial(2)
     ↓
5 × 4 × 3 × 2 × factorial(1)
     ↓
120
```

---

# 🔄 Recursion Flow

A recursive function keeps creating function calls until the **base condition** is reached.

```text
        function(n)
             │
             ▼
        n == base?
        /        \
      YES         NO
       │           │
      STOP     function(n-1)
                   │
                   ▼
              function(n-2)
                   │
                   ▼
                  ...
```

---

# 🛠️ Technologies Used

<p>
<img src="https://img.shields.io/badge/C-Programming-00599C?style=flat-square&logo=c&logoColor=white" />
<img src="https://img.shields.io/badge/GCC-Compiler-444444?style=flat-square&logo=gnu&logoColor=white" />
<img src="https://img.shields.io/badge/VS%20Code-Editor-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" />
</p>

### Language

**C**

### Concepts

* Functions
* Recursion
* Arrays
* Strings
* Loops
* Conditional Statements
* Mathematical Logic
* Searching
* Pattern Printing

---

# ▶️ How to Run

### 1️⃣ Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2️⃣ Open the Project

```bash
cd YOUR_REPOSITORY_FOLDER
```

### 3️⃣ Compile a Program

Using GCC:

```bash
gcc program.c -o program
```

### 4️⃣ Run

```bash
./program
```

### Windows

```bash
program.exe
```

---

# 💻 Example

### Input

```text
Enter number: 7
```

### Output

```text
Prime
```

---

# 🎯 Learning Objectives

By completing these programs, you can practice:

```text
                 RECURSION
                     │
        ┌────────────┼────────────┐
        ▼            ▼            ▼
      NUMBERS      ARRAYS       STRINGS
        │            │            │
        ▼            ▼            ▼
     FACTORIAL     SEARCH       REVERSE
     FIBONACCI     SUM          LENGTH
     PRIME         MAX/MIN      VOWELS
        │            │            │
        └────────────┼────────────┘
                     ▼
              PROBLEM SOLVING
```

---

# 📈 Difficulty Progression

| Level                | Focus                | Programs |
| -------------------- | -------------------- | -------- |
| 🟢 Beginner          | Basic recursion      | 1–10     |
| 🟡 Easy              | Mathematical logic   | 11–20    |
| 🟠 Intermediate      | Arrays & strings     | 21–35    |
| 🔴 Advanced Practice | Searching & patterns | 36–50    |

---

# 📝 Practical Exam Preparation

These programs are especially useful for **C programming practical examinations**.

### Before the exam, make sure you understand:

* ✅ What is recursion?
* ✅ What is a base case?
* ✅ What is a recursive case?
* ✅ How function calls are stored in the stack
* ✅ How to pass arrays to functions
* ✅ How to handle strings
* ✅ How to trace recursive calls manually

### ⭐ Quick Exam Tip

Don't just memorize the code.

Understand this pattern:

```text
1. Identify the smallest case
        ↓
2. Write the base condition
        ↓
3. Reduce the problem
        ↓
4. Call the same function
        ↓
5. Return the result
```

---

# 📂 Suggested Folder Structure

```text
C-Recursion-50-Programs/
│
├── 01_Print_1_to_N.c
├── 02_Print_N_to_1.c
├── 03_Sum_N_Natural.c
├── 04_Factorial.c
├── 05_Power.c
├── 06_Count_Digits.c
├── 07_Sum_Digits.c
├── 08_Reverse_Number.c
├── 09_Palindrome_Number.c
├── 10_Fibonacci.c
│
├── 11_Prime.c
├── 12_GCD.c
├── 13_LCM.c
├── ...
│
└── README.md
```

---

# 🌟 Repository Highlights

```text
╔══════════════════════════════════╗
║       C RECURSION PRACTICE       ║
╠══════════════════════════════════╣
║                                  ║
║   🔢 50 Practical Programs       ║
║   💻 C Programming               ║
║   🧠 Recursion                   ║
║   📦 Arrays & Strings            ║
║   🔍 Searching                   ║
║   ⭐ Pattern Problems             ║
║   🎯 Exam Preparation            ║
║                                  ║
╚══════════════════════════════════╝
```

---

# 🚀 Future Improvements

Possible additions to this repository:

* [ ] More advanced recursion problems
* [ ] Backtracking programs
* [ ] Recursive sorting algorithms
* [ ] Recursive binary search
* [ ] Tower of Hanoi
* [ ] Permutations
* [ ] Combinations
* [ ] Recursion + Dynamic Programming
* [ ] Time and Space Complexity for every program

---

# 👨‍💻 Author

### Sudipta De

<p>
<a href="https://github.com/Sudipta-De">
<img src="https://img.shields.io/badge/GitHub-Sudipta--De-181717?style=for-the-badge&logo=github" />
</a>
</p>

---

<p align="center">

### 💡 "Understand the base case. Master the recursion."


</p>
