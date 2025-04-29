# JavaScript Intro

## Instructions

1. Each person in the group should clone this repository down to their local machine. This will not be submitted.
2. Open the cloned folder with VS Code.
3. Live serve `index.html` in your browser, then open the browser console.
4. Choose one person in the group to share their screen.
5. Everyone else in the group should follow along and type the answers on their own computers.
6. As a team, read each question out loud and reach a consensus on the answer before moving to the next question.

## Evaluate expressions with browser console

1. Identify the **operator** and **operands** in this **expression**: `2 + 3`
=> operator: + (addition)
   operands: 2 and 3

2. Use the browser console to **evaluate** the following expressions.
   1. `2 + 2` => 4
   2. `1.01 * 5` => 5.05
   3. `18 / 3 - 2` => 4
   4. `-5 - 20 * 3` => -65
3. Which of the following is _not_ an operator? => 3.
   1. `*` => multiplication
   2. `-` => subtraction
   3. `9` => not an operator
   4. `/` => division
4. What does `2 ** 3` evaluate to? => 8 (** is exponentiation operator)
5. What does the `**` operator do? => exponentiation, raise to the power of 
6. Which of the following expressions does not evaluate to the same **value**?
   1. `16`
   2. `4 ** 2`
   3. `-8 * -2`
   4. `4 + 1 * 4` => 8, which is different from the rest
7. Write three different expressions that evaluate to 64. 
=> 8**2 , 2*30+4 , 7*10-4 , 8*8 

## Use the modulo operator

8. Use the browser console to **evaluate** the following expressions.
   1. `13 % 3` => 1
   2. `14 % 3` => 2
   3. `15 % 3` => 0
   4. `15 % 4` => 3
   5. `15 % 5` => 0
9. List two numbers `% 5` that would evaluate to `0`. => 5, 10
10. How can **modulo** (`%`) be used to check if a number is even? => If the number is tested by %2 and the result is 0 -> it's an even number; if the number %2 and the result is NOT 0 -> it's an odd number
11. What does the modulo operator do? => find the remainder in division

## Store information as variables

Computers store information in **memory**, which you can imagine as a long sequence of data. A **memory address** is the location of a specific piece of information in memory.

| Variable      | Memory Address | Value     |
| ------------- | -------------- | --------- |
|               | 243            |           |
| numJellybeans | 244            | 102       |
|  cat          | 245            |  🐈‍⬛       |
|               | ...            |           |
| color         | 306            | 🟩        |
|               | 307            |           |
| temperature   | 308            | 72.5      |
|               | ...            |           |
| hobby         | 419            | "crochet" |

12. The **variable** `numJellybeans` **points to** which memory address? => 244
13. What value is stored at that address? => 102
14. Which variable points to memory address 308? => temperature
15. What value is stored at that address? => 72.5
16. Which variable points to the **string** `"crochet"`? => hobby
17. Explain how the table should be modified to indicate that a variable named `pet` points to a cat (🐈‍⬛) which is stored at address 245. => see updated table above
18. In your own words, define **variable** in relation to **memory** and **memory addresses**. => memory address is the unique location where the variable's value is stored. Variable (file name) - value (file content) - memory address (where the file/file content is stored).

## Let JavaScript handle addresses

Here is the same table again, but this time, the memory addresses have been obscured. Different programming languages have different philosophies for exposing memory addresses to developers. JavaScript prefers to handle the memory addresses for you, so you don't need to worry about them!

| Variable      | Memory Address | Value     |
| ------------- | -------------- | --------- |
|               | ???            |           |
| numJellybeans | ???            | 102       |
|               | ???            |           |
|               | ...            |           |
| color         | ???            | 🟩        |
|               | ???            |           |
| temperature   | ???            | 72.5      |
|               | ...            |           |
| hobby         | ???            | "crochet" |

19. What is the value of the variable named `temperature`? => 72.5
20. The green square is stored in which variable? => color
21. Why might a programmer _want_ to care about memory addresses? => memory addresses are unique, and allows programmer to manipulate data more directly. -> important for low-level programming and performance optimization (?) optimize memory usage 
22. Why might a programmer _not_ want to care about memory addresses? => higher-level languages often handle memory managament (such as allocation and dellocation) automatically. 