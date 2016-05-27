# FizzBuzz

FizzBuzz is probably the all-time most famous programming challenge. It is given to many junior developers during the interview process.

## The rules:

Write a program such that:

For the numbers 1 to 100, print "Fizz" if the number is divisible by 3, print "Buzz" if it's divisible by 5, print "FizzBuzz" if it's divisible by both, and otherwise just print the number.

## Part 1: Pseudocode

The lines below each represent a line of code necessary to create this program. However, they are all out of order. Put them in the correct order.

- While my number is less than or equal to 100
- My number is 1
- My number increases by 1
- If the remainder of my number divided by 3 is 0
- If the remainder of my number divided by 5 is 0
- If the remainder of my number divided by 3 is 0, and the remainder of my number divided by 5 is 0
- Write "Fizz"
- Write "Buzz"
- Write "FizzBuzz"
- Write my number
- Otherwise
- Otherwise
- Otherwise

## Part 2: Real code

- `while(number <= 100){`
- `var number = 1;`
- `number += 1;`
- `if(number % 3 === 0)`
- `if(number % 5 === 0)`
- `if(number % 3 === 0 && number % 5 === 0)`
- `{document.write("Fizz")}`
- `{document.write("Buzz")}`
- `{document.write("FizzBuzz")}`
- `{document.write(number)}`
- `else`
- `else`
- `else`
- `}`
