<h1 align = center > Introduction to Computer Science and Programming in Python </h1>

<p align="center">
  <img src="https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/6-0001f16.jpg">
</p>


6.0001 Introduction to Computer Science and Programming in Python is intended for students with little or no programming experience. It aims to provide students with an understanding of the role computation can play in solving problems and to help students, regardless of their major, feel justifiably confident of their ability to write small programs that allow them to accomplish useful goals. The class uses the Python 3.5 programming language.

---

<h2 align = center > Lecture 1 : What is Computation ?</h2>

&nbsp;

[Lecture Video on Youtube](https://www.youtube.com/watch?v=nykOeWgQcHM&t=537s)

&nbsp;

> Topics
- you should graduate form this course knowing how to solve problem and some programming skills and its theoritical concepts
- you will learn what is control flow, how to represent your knowledge with data structure and how to create objects
- you will learn how to organize and modularize systems using object classes and methods
- learn how to know that this program is better than the other program using algorithms

&nbsp;

> What does a computer do ?
- performs calcualtions
- high effecient memory
- computers know only what you tell them

&nbsp;

> Types of Knowledge
- **decalarative knwoledge:** statement of fact
- **imperative knowldge:** is recipe or the "how - to" (steps)

&nbsp;

> Basic Machine Architucture
- Input
- Output
- Memory: Stores data and instructions sequence
- ALU (Arithmetic logic unit): do premetive operations (addition - subtraction)
- Control Unit: Program counter to control the sequence of instructions
 

&nbsp;

> Aspects of languages
- *semanticsis* the meaning associated with a **syntactically correct** string of symbols with **no static semantic errors**

&nbsp;

> Python Objects
- everything in python is object
- objects are
  - **scalar** (cannot be subdivided)
    - *int* ; represents intergs, ex. 5
    - *float* ; represents real numbers, ex. 3.2
    - *bool* ; represetns boolean value True or False
    - *NoneType* ; special and has one value, None
    - You can type casting (convert object of one type to another)
  - **non-scalar** (have internal structure that can be accessed)

&nbsp;

> operators on ints and floats
- i+j : the **sum**
- i-j : the **difference**
- i*j : the **product**
- i/j : **division**
- i%j : the **remainder** when i is divided by j
- i\**j : i to the **power** of j

---

<h2 align = center > Lecture 2 : Branching and Iteration</h2>

&nbsp;

[Lecture Video on Youtube](https://www.youtube.com/watch?v=0jljZRnHwOI&list=PLUl4u3cNGP63WbdFxL8giv4yhgdMGaZNA&index=5)

&nbsp;


> Strings
- letters, special characters, spaces, digits
- enclose in quotation double or single
- we can concatentate strings

``` python
name = "Hana"
new_string = ( " hi " + name )*2 # hi Hana hi Hana

```
&nbsp;

> Input/Output
- for printing output use ; print()
- for inserting input from user ; input()

&nbsp;

> comparison operators
- the result of comparison operators give you boolean (True or False)
- \>, <, >=, <=, ==, !=

&nbsp;

> logic operators
- and, or, not
- you can back to the truth table

&nbsp;

> control flow - branching
- if
- if - else
- if - elif - else

&nbsp;

> control flow - iteration
- for loop
  - used when know the number of iterations
  - can end early via break
  - uses a counter
- while loop
  - unbounded number of iterations
  - can end early via break

---

<h2 align = center > Lecture 3 : String Manipulation, Guess and Check, Approximations, Bisection </h2>

&nbsp;

[Lecture Video on Youtube](https://www.youtube.com/watch?v=SE4P7IVCunE&list=PLUl4u3cNGP63WbdFxL8giv4yhgdMGaZNA&index=11)

&nbsp;

> Strings
- sequence of case sensitivea characters
- can compare strings with == , < , >
- you can retrieve the length of the string
- you can perform *indexing* on strings using square brackets
- you can retrieve sub strings from a string through *slicing*
- strings are *immutable* - cannot be changed


---

<h2 align = center > Lecture 4 : Decomposition, Abstraction, and Functions </h2>

&nbsp;

[Lecture Video on Youtube](https://www.youtube.com/watch?v=MjbuarJ7SE0&list=PLUl4u3cNGP63WbdFxL8giv4yhgdMGaZNA&index=14)

&nbsp;

> Functinos
- *abstraction idea*: do not need to know how function deeply works to use it
- *decompistion idea*: different function can work together to achieve an end goal (solve a problem with an algorithm consist of decomposed functions)
- we can achieve decompisition (code divided into modules) and abstraction (black box) with functions
- functions are useable chunks of code
- functions have a name, input, algorithm, and output
- sometimes functions have docstring (the role of the function or description); it is optional but recommmended
- python returns the value *None*, if no return given
- you can have only one return executed inside a function
- the code inside a function but after a return statement not executed
- you can enter a function as an argument for another function
- inside a function, can access a variable outside but cannot modify it

---

<h2 align = center > Lecture 5 : Tuples, Lists, Aliasing, Mutability, and Cloning </h2>

&nbsp;

[Lecture Video on Youtube](https://www.youtube.com/watch?v=RvRKT-jXvko&list=PLUl4u3cNGP63WbdFxL8giv4yhgdMGaZNA&index=18)

&nbsp;

> Headline
- 