# 100 Days Of Code - Log
------
## Day 1: November 9, 2022
### Working with Strings - 01

**Today's Progress**: Creating a Program that read a name or a text and transform every first word to upper case

**Thoughts:** It was very useful because i was able to work with some different methods even in a simple example.

*Methods that were used and others:*
1. `split()`
2. `replace()`
3. `toUpperCase()`
4. `join()`
5. `for of loop`

**Link to work:** [Capitalize First Letter Program](https://github.com/Holiv/capitalize-first-letter)

### Working with Strings - 02

**Today's Progress**: Program that read a credit card number and hide all the numbers but the last four

**Thoughts:** Simple example but with a real case working with very interesting methods;

*Methods that were used and others:*
1. `slice()`
2. `padStart()`
3. `type coersion`

**Link to work:** [Credit Card Number Hider](https://github.com/Holiv/credit-card-number-hider)

## Day 2: November 10, 2022
### Using Default Parameters

**Today's Progress**: Program that simulate booking a flight.

**Thoughts:** 
1. `Sometimes is useful to have functions where some parameters have default values.`
2. `Default parameters accepts any expressions`
3. `Accepts other parameter that were set before it`
4. `Use undefined as argument to skip a parameter and leave it with the default value`

**Link to work:** [Booking a Flight](https://github.com/Holiv/default-parameters)

## Day 3: November 11, 2022
### Map - JavaScript Data Structure

**Today's Progress**: Simulating a quiz using Map as a Data Structure

**Thoughts:** 
Maps are a new data structure in JavaScript that allows us to store data with key value pairs, similar to Objects. But the biggest difference is that in Objects, the type of the keys are always strings, however ***in Maps the keys can have any type*** and it can gave to us a lot of possibilities.

Maps has also moderns methods that brings efficiency to it and as Sets, Maps can't also have duplicated values.

Used in the program:

1. `.get()`
2. `Destruct`
3. `Map Iteration using for of loop`

**Link to work:** [Quiz using Map](https://github.com/Holiv/javascript-map_quizz)

## Day 4: November 12, 2022
### How Passing Arguments Works: Value vs. Reference

**Today's Progress**: Creating a function to test the difference between values and objects used as arguments

**Thoughts:** 
When passing a primitive value as an argument to a function a new variable will be created. Its create a whole new variable with the same value of the original one. It means that any change in the variable inside the function will never affect the original variable outside the function.

Things work a little bit different when talking about Objects as we see before in previous sections. Objects are store in the Heap memory, so the variable that store these objects store its address in fact as a value and not the object itself. So when we pass a object as an argument to a function, it is the object reference that are being passed (as a value), then when something is modified in the object inside the function it will affect the whole object everywhere in the code, because we are not creating a copy of the object but passing its address, then the JavaScript goes to the address and change it affecting the Object entirely.

To finish is important to know that in JavaScript there is no **passing by reference** as other programming languages. Even though we are passing the reference as an argument to the function it goes as a **value** (value that is equal to the object reference in memory) and not by **reference.**

**Link to work:** [Value vs Refference](https://github.com/Holiv/js_value_vs_refference)

## Day 5: November 13, 2022
### The .call() method

**Today's Progress**: Using the .call() method to borrow a method from another Object

**Thoughts:** 
The ***.call() method*** is a function method that allows us to borrow objects methods from a certain object to another object. It excludes the need to repeat the code when creating similar objects that has similar methods.

The number of arguments that the ***.call()*** method will receive will depend on the original method that we are borrowing, but the important point here is that ***the first argument will always be the name of the object that we are borrowing the method. It means that the .call() method will always have at least one argument. The others arguments will be the arguments to attend the parameters of the original method if it is necessary.***

**The following sequence of what happened in the code above:**

- We called the ***book method*** using `qatarAirlines.book`
- As ***book*** is also a function so we were able to use the ***.call()*** method - Here we are saying: <ins>"Hey, qatarAirlines, can you borrow your ***book*** method so that i can use it in my new Airline?”</ins>
- The we pass as the first argument the ***emiratesAirline***, it says to the code that we are borrowing the ***book*** method from the ***qatarAirlines*** to use in the ***emiratesAirline.***

**Link to work:** [The .call() method](https://github.com/Holiv/javascript_call_method)

## Day 6: November 14, 2022
### Creating a Poll using some advanced topics

**Today's Progress**: Creating a poll that prompts the user for his favorite programming language.

**Thoughts:** 

Covered topics in the program:

1. `String manipulation`
2. `Array manipulation`
3. `.fill() method`
4. `.joins() method`
5. `this. keyword`
6. `.bind() method`
7. `short circuiting`
8. `DOM manipulation`

**Link to work:** [The poll](https://github.com/Holiv/favourite_programming_lenguage_poll)

## Day 7: November 15, 2022
### Closures - Understanding how closures works

**Today's Progress**: Creating an example to understand how closure works

**Thoughts:** 

- we dont create closures, it simply happens automatically in some situations and our work is to recognize it.
- closure makes a function remember all the variables that existed at the function's birthplace
- Whenever you create a function within another function, you have created a closure. The inner function is the closure. This closure is usually returned so you can use the outer function’s variables at a later time.

**Link to work:** [Closures](https://github.com/Holiv/understanding-closures)