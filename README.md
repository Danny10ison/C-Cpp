# Notes from tutorials

[Date => 14/08/2021  => D1](#)

it is bad practice to be using 
```c++
using namespace std;
```
instead use
```c++
using std::cout;
cout << "Hello\n";
```
or
```c++
std::cout << "Hello\n";
```
[Date => 16/08/2021 => D2](#)

### Before 

complete exercises on W3Schools for tutorial level reached.

#### Basic C++ syntax
- basic display with cout
- newline with \n special character
- single line and multiline comments

#### C++ Variables
- Creating variable
- basic addition operation
- variable assignment
- multiple variable declaration

#### C++ User Input
- using cin
- taking 2 input

#### C++ Data Types
- creating variables with inbuilt data types. int, double, char, bool, string.
- boolean vars yay, nay.
- string variable.

#### C++ Operators
- basic operators +, *, /, -, %
- increament ++x, x++
- operator assignment. +=

#### C++ Strings
- creating string var
- string concatenation  with +
- string methods .length
- accessing string elements, array form. var[i]
- changing string elements. var[i] = 'newElement'
- get a string from user using getline(cin, varname).

#### C++ Math, cmath hearder
- max(x,y)
- importing the math header < cmath >, sqrt, round, log

#### C++ Boolean
- create boolean variables.
- boolean expressions

#### C++ Conditional- If..Else,
- simple if...else
-  comparison
- if...else
- if...else if...else
- ternary operator  - (condition) ? true_statement:false_statement
- switch statement

#### C++ Loops
- while loop
- do...while
-  for
- break
- continue

#### C++ Arrays
- creating arrays
- accessing array elements
- changing array element
- looping through array elements

#### C++ References
- create reference
```c++
string food = "Pissa";
string &meal = food;
```
- get the memory of variable
```c++
string food = "Pissa";
cout << &food;
```
- intro pointers
```c++
string food = "Pissa";
string* ptr = &food;
```
[Date => 25/08/2021 => D3](#)

Complete with a freshed knowledge in C++ functions

+ function definition
+ function call
+ function declaration

```cpp
data_type function_name(param1, param2, ...);

int main(){

  function_name(param1, param2, ...);
}

function_name(param1, param2, ...){
  // some code 
}

```

*function parameter refers to the variables of the function*

*when a parameter is passed to a function, its known as __arguement__*

### function overloading
```cpp
data_type1 function_name1(param1, param2, ...){
  // some code 
}

data_type2 function_name1(param3, param4, ...){
  // some code 
}

```