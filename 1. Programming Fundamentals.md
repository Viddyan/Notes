### Programming Fundamentals:

#### 1. **Introduction (What, Why, How)**

- **What**:  
  Programming fundamentals refer to the basic concepts and principles that form the foundation of computer programming. These core concepts are common across most programming languages and are crucial for writing efficient, readable, and maintainable code.

- **Why**:  
  Understanding programming fundamentals is essential for anyone looking to become proficient in any programming language. They serve as building blocks for solving complex problems, developing applications, and creating systems in various domains like web development, mobile apps, and system software.

- **How**:  
  Programming fundamentals include learning basic constructs like variables, data types, control structures (such as loops and conditionals), functions, and algorithms. Through hands-on practice and problem-solving, you develop an understanding of how these components work together to create functional programs.

#### 2. **Learning Objectives**
By the end of this topic, you should be able to:
- Understand the basic building blocks of any programming language.
- Apply control structures like loops and conditionals.
- Write modular code using functions.
- Work with basic data types and variables.
- Develop logic to solve problems using algorithms.

#### 3. **Essential Concepts (Building Blocks)**

1. **Variables and Data Types**  
   - **Variables**: Containers used to store data values. For example, in Python:  
     ```python
     age = 25
     name = "Alice"
     ```
   - **Data Types**: Define the kind of data a variable can hold. Common types include:
     - **Integers** (whole numbers): `int age = 25;`
     - **Floating-Point Numbers** (decimals): `float price = 19.99;`
     - **Characters** (single letters or symbols): `char grade = 'A';`
     - **Strings** (sequence of characters): `string name = "Alice";`
     - **Booleans** (True/False values): `bool isLoggedIn = true;`

2. **Operators**  
   Operators are symbols that tell the compiler or interpreter to perform specific mathematical, relational, or logical operations. Common operators include:
   - **Arithmetic Operators**: `+`, `-`, `*`, `/`, `%`
   - **Relational Operators**: `==`, `!=`, `<`, `>`, `<=`, `>=`
   - **Logical Operators**: `&&` (AND), `||` (OR), `!` (NOT)

3. **Control Structures**  
   These structures control the flow of execution in a program:
   - **Conditionals (if, else, switch)**: Execute code based on conditions.
     ```python
     if age > 18:
         print("Adult")
     else:
         print("Minor")
     ```
   - **Loops (for, while, do-while)**: Repeat a block of code multiple times.
     ```python
     for i in range(5):
         print(i)
     ```

4. **Functions**  
   Functions are reusable blocks of code that perform specific tasks. They help in reducing redundancy and improving code maintainability.
   - **Defining a Function**:
     ```python
     def greet(name):
         print("Hello " + name)
     ```
   - **Calling a Function**:
     ```python
     greet("Alice")
     ```

5. **Data Structures**  
   Data structures store and organize data in a specific format. Common data structures include:
   - **Arrays/Lists**: A collection of elements of the same type.
   - **Dictionaries/Hashmaps**: A collection of key-value pairs.
   - **Stacks and Queues**: Linear data structures used for managing data sequentially.
   - **Trees and Graphs**: Non-linear structures used for hierarchical and networked data.

6. **Input and Output (I/O)**  
   I/O refers to how data is input into a program and how the program outputs data to the user. Example in Python:
   ```python
   name = input("Enter your name: ")
   print("Hello " + name)
   ```

7. **Algorithms**  
   Algorithms are step-by-step procedures used to perform tasks or solve problems. They play a critical role in programming by determining how efficiently a program runs.
   - **Example**: Sorting an array of numbers using the **Bubble Sort** algorithm:
     ```python
     def bubbleSort(arr):
         n = len(arr)
         for i in range(n):
             for j in range(0, n-i-1):
                 if arr[j] > arr[j+1]:
                     arr[j], arr[j+1] = arr[j+1], arr[j]
     ```

#### 4. **Hands-On Coding (Real-World Implementations)**

1. **Basic Calculator**  
   Write a program that performs basic arithmetic operations (addition, subtraction, multiplication, and division) based on user input.
   ```python
   def calculator(a, b, operator):
       if operator == '+':
           return a + b
       elif operator == '-':
           return a - b
       elif operator == '*':
           return a * b
       elif operator == '/':
           return a / b
       else:
           return "Invalid operator"
   ```

2. **Find the Largest Number**  
   Write a function that takes a list of numbers and returns the largest number.
   ```python
   def find_largest(numbers):
       max_num = numbers[0]
       for num in numbers:
           if num > max_num:
               max_num = num
       return max_num
   ```

#### 5. **Guided Exercises (Practice Tasks)**

1. Write a program to find whether a number is even or odd.
2. Create a function that reverses a string.
3. Develop a program that accepts user input for two numbers and an operator, and then performs the operation (addition, subtraction, multiplication, division).
4. Write a loop that prints the Fibonacci sequence up to a given number of terms.

#### 6. **Interview Preparation**

- **What is the difference between a list and a dictionary?**
- **Explain the difference between `while` and `for` loops.**
- **How do you handle errors in a program?**
- **What is recursion, and when would you use it?**
- **What is an algorithm, and can you describe an example?**

#### 7. **Wrap-Up**

Programming fundamentals are the core concepts that lay the groundwork for all software development. Mastering them enables developers to approach complex problems with a structured and logical mindset. With these foundations, you can explore more advanced topics such as object-oriented programming, databases, and web development.

#### 8. **Post-Session Resources**

- **Books**:
  - "The C Programming Language" by Brian W. Kernighan and Dennis M. Ritchie
  - "Python Crash Course" by Eric Matthes
  - "Introduction to Algorithms" by Thomas H. Cormen, et al.
  
- **Online Resources**:
  - [Codecademy](https://www.codecademy.com/)
  - [freeCodeCamp](https://www.freecodecamp.org/)
  - [W3Schools](https://www.w3schools.com/)

#### 9. **Assessment (Output-Based Questions)**

1. **Consider the following code snippet:**
   ```python
   x = 5
   y = 10
   print(x + y)
   ```
   **What will be the output?**
   - a) `5`
   - b) `10`
   - c) `15`
   - d) `50`
   **Answer**: c) `15`

2. **Consider the following code snippet:**
   ```python
   for i in range(3):
       print(i)
   ```
   **What will be the output?**
   - a) `1 2 3`
   - b) `0 1 2`
   - c) `0 1 2 3`
   - d) `1 2 3 4`
   **Answer**: b) `0 1 2`
