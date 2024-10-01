### Looping:

#### 1. **Introduction (What, Why, How)**

- **What**:  
  Looping is a control flow mechanism that repeatedly executes a set of instructions until a condition becomes false.

- **Why**:  
  It simplifies repetitive tasks and allows programs to handle large sets of data efficiently.

- **How**:  
  Loops evaluate a condition and repeat the code block until the condition no longer holds true.

#### 2. **Learning Objectives**
By the end of this topic, you should be able to:
- Understand and use different types of loops.
- Implement loops to handle data efficiently.
- Use control statements (`break`, `continue`) within loops.

#### 3. **Essential Concepts (Building Blocks)**

1. **Types of Loops**

   - **For Loop**:  
     Repeats a block of code a specified number of times.

     **Pseudocode**:
     ```
     For i from 0 to N-1:
         Execute code block
     EndFor
     ```

   - **While Loop**:  
     Repeats the code block as long as the condition is true.

     **Pseudocode**:
     ```
     While condition is true:
         Execute code block
     EndWhile
     ```

   - **Do-While Loop** (Executes the code block at least once):
     ```
     Do:
         Execute code block
     While condition is true
     ```

2. **Infinite Loops**
   ```
   While True:
       Execute code block
   EndWhile
   ```

3. **Breaking and Continuing Loops**

   - **Break**:
     ```
     For each element in collection:
         If condition is true:
             Break
         EndIf
         Execute code block
     EndFor
     ```

   - **Continue**:
     ```
     For each element in collection:
         If condition is true:
             Continue
         EndIf
         Execute code block
     EndFor
     ```

4. **Nested Loops**  
   ```
   For i from 0 to N-1:
       For j from 0 to M-1:
           Execute code block
       EndFor
   EndFor
   ```

#### 4. **Hands-On Coding (Real-World Implementations)**

1. **Sum of Natural Numbers**  
   ```
   Initialize total = 0
   For i from 1 to 100:
       Add i to total
   EndFor
   Print total
   ```

2. **Factorial of a Number**  
   ```
   Function Factorial(n):
       Initialize result = 1
       While n > 1:
           Multiply result by n
           Decrement n
       EndWhile
       Return result
   EndFunction
   ```

3. **Multiplication Table**  
   ```
   Initialize number = 7
   For i from 1 to 10:
       Print number * i
   EndFor
   ```

4. **Find Prime Numbers**  
   ```
   For num from 2 to 100:
       Set is_prime to True
       For i from 2 to num-1:
           If num is divisible by i:
               Set is_prime to False
               Break
           EndIf
       EndFor
       If is_prime is True:
           Print num
       EndIf
   EndFor
   ```

#### 5. **Guided Exercises (Practice Tasks)**

1. Print all even numbers between 1 and 50:
   ```
   For i from 1 to 50:
       If i is even:
           Print i
       EndIf
   EndFor
   ```

2. Sum of list of numbers:
   ```
   Initialize total = 0
   For each number in list:
       Add number to total
   EndFor
   Return total
   ```

3. User input until sum > 100:
   ```
   Initialize sum = 0
   While sum <= 100:
       Input number
       Add number to sum
   EndWhile
   ```

4. Reverse a string:
   ```
   Initialize reversed_string = ""
   For i from length of string - 1 to 0:
       Append string[i] to reversed_string
   EndFor
   Return reversed_string
   ```

#### 6. **Interview Preparation**

- **What is the difference between a `for` loop and a `while` loop?**
- **When would you use a `break` statement in a loop?**
- **How can you avoid infinite loops?**
- **What are nested loops, and how are they used?**

#### 7. **Wrap-Up**

Loops provide a powerful way to handle repetitive tasks. By using the correct loop type and control statements like `break` and `continue`, you can streamline complex processes in programming.

#### 8. **Post-Session Resources**

- Refer to online tutorials, books, and coding challenges to practice loops.

#### 9. **Assessment (Output-Based Questions)**

1. **Consider the following pseudocode:**
   ```
   For i from 0 to 2:
       For j from 0 to 1:
           Print i, j
   EndFor
   ```

   **What will be the output?**
   - a) `0 0, 1 1, 2 2`
   - b) `0 1, 1 0, 2 1`
   - c) `0 0, 0 1, 1 0, 1 1, 2 0, 2 1`
   - d) `None of the above`

   **Answer**: c) `0 0, 0 1, 1 0, 1 1, 2 0, 2 1`

2. **What will be the output of this pseudocode?**
   ```
   Initialize i = 0
   While i < 3:
       Print i
       Increment i
   EndWhile
   ```

   - a) `0, 1`
   - b) `0, 1, 2`
   - c) `0, 1, 2, 3`
   - d) `None of the above`

   **Answer**: b) `0, 1, 2`
