Coding Cheat Sheet 
===============

## Variables and Constants 
### Variable:
A variable is a container used to store a value.

- A declared (a declaration is a piece of code that creates something new in your application, such as a function, variable, or custom type) variable with no value (uninitialized):
```javascript 
var myName; 
```

- Various javascript examples:
```javascript
var myAge = 50;
var firstName = 'Bob';
var lastName = 'Barker';
var fullName = firstName + lastName;
```

### Constant:
A constant is declared with the word `let` and you use it when you know that a blue won't change.
```swift
let numberOfTries = 3
``` 

## Functions
A function allows you to name a set of commands, which can then run any thime you want. Basically it is a block of code that can be used over and over again when called by name.

Swift:
```swift
func tieMyShoe() {
  loop
  swoop
  pull
}
```

## Conditional Code
Conditional code uses `if` statements to determine what code will run when the condition set is true. If the condition is false, you can use `else` or `else if`s to specify other code to run.

### Logical Operators
Logical operators AND `$$` OR `||`  NOT `!`
-  `!` (NOT)
    -Condition must be NOT true.
```javascript
if ! {
  blah blah blah;
} else {
  blah;
}
```

-  `&&` (AND)
   - Both conditions must be true.
```javascript
if something && somethingElse {
  blah blah;
} else {
  blah;
}
```

-   `||` (OR)
   - Either condition must be true.
```javascript
if something || somethingElse {
  blah blah;
} else {
  blah;
}
```

```javascript
var x = 0;
function addOne() {
  alert('Current number is ' + x);
  x += 1;
}
```

### Comparison Operators
A symbol, such as ==, !=, <, >, <=, or =>, used to compare two values. A comparison operator can be used in a condition of an `if` statement or `while` loop to return a Boolean value indicating whether a comparison is `true`. For example, `6 > 8` compares `6` with `8` and returns `false`.  
  
    
       
## Loops
Repeat code over and over again in a loop.
### For Loops
- Repeats a block of code for as many times as you specify.

```swift
for i in 1 ... 24 {
  if isOnClosedSwitch {
    toggleSwitch()
  } else if inOnGem {
    collectGem() 
    } else {
      moveForward()
    }
  }
```

### While Loops
- Repeats a block of code as long as the condition is true.

```swift
while !isBlocked {
  while !isOnGem {
    moveForward()
  }
  turnLeft()
  collectGem()
}
```

## Algorithms
An algorithm is a set of rules and instructions you use to solve a problem. For example, a nav app uses an algorithm to figure out the fastest path to where you want to go.

## Type
A named grouping of properties (the features) and methods (the behaviors) of a kind of data.

### initialization
The act of creating a new instance of a type, which includes setting initial values for any properties of the type.

### instance
A value of a particular type. Example: in `let greenPortal = Portal(),`  `greenPortal` is an instance of type  `Portal `.

### property
A variable (a nambed container that stores a value) defined inside a type.

### parameter
The name of an input vaue to a function, used in the definition of the function. For example, in `move(distance: Int)`, `distance` is a parameter that takes a value of type `Int`.

## Arrays
An **array** is a collection that stores an ordered list of items of the same type. The same item can appear multiple times in different positions. For example, `highScores = [37, 34, 29, 29, 26]` is an array of integers.

### Index.
The **index** is a number that represents the position of an item in an array. They start at 0 because computers start counting at zero. 

If you try to access an index that's outside an array's boundaries, you'll get an ''array out of bounds" error. You can prevent this by making sure your `index` value is never greater than your array's highest index number. 
Example:
```swift
//swift
if index == arrayName.count {
	index = 0 
	}
```
```javascript
//javascript
if index == arrayName.length {
	index = 0
	}
```

### methods
```swift
ingredients.remove(at: 2)
ingredients.insert('newItem', at: 2)
ingredients.append('newItem')
ingredients.removeFirst()
ingredients.removeLast()
ingredients.removeAll()
//Remove a coordinate from rightColumn and append to newArray:
var rightColumn = world.column(7)
newArray.append(rightColumn.remove(at: 1))

for item in ingredients {
  place(item, in: bowl)
}
```


### Iteration
**Iteration** is the act of repeating a process, such as performing the same action on each item in an array.

## Comments
A **code comment** gives information about the code, but the app/computer ignores it and does not run it.
 `//Swift code comment`
```swift 
/*Swift multi-
line code comment */
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTkyMzE3MzY0MSwxNjQ0MzcyODczXX0=
-->
