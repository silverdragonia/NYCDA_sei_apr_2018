## Variables

Create a variable using the keywords `let` or `const`.

```javascript
let myNumber = 40;
```

**anatomy** *keyword / identifier / equal sign / value / semi-colon*


## Primitive Values
* **integer** - any whole number

```javascript
10, 45, -100, 5000, 0
```

* **float** - any number with a decimal

```javascript
5.2, -100.8, 5000.0
```

* **string** - anything within single or double quotes

```javascript
"george", 'george', '5'
```

* **boolean** - true or false

```javascript
true, false
```

* **undefined** - unkown value

```javascript
undefined
```

## Non-primitive Values

### Arrays

Stores a dictionary of values.

```javascript
let myPets = ['max', 'sandy', 'harry'];
```

**anatomy** *square bracket / (value / comma / value / comma / ...()... / square brackets / semi-colon*

##### Indexes

Used to identify a specific place in an array.

```javascript
myPets[0]
```

**anatomy** *variable name / square bracket / index / square bracket / semi-colon*

* index 0 = max
* index 1 = sandy
* index 2 = harry

### Objects

A dictionary of keys and their values.

```
let myDog = {
color: 'white',
name: 'buzzie',
age: 3
};
```
**anatomy** *curly bracket / (key / colon / value) / comma / ...()... / curly bracket / semi-colon*

Calling a value of a key within an object:

```javascript
myDog.name
```

**anatomy** *variable name / period / key*

## Operators

* **`=` assigns a value to a variable**

```javascript
let c = 'value';
```

* **`+` addition and concatenation** *(be careful of types)* 

```javascript
let c = a + b;
let greeting = 'Hello';
let name = 'george';
let result = greeting + name; // 'Hello, george'
let sum = '5'+ 5; // '55'
```

* **`-` subtractions**

```javascript
let c = a - b;
```

* __`*` multiplication__

```javascript
let c = a * b;
```

* **`/` division**

```javascript
let c = a / b;
```

* **`%` modulo** *(the remainder of division)*

```javascript
let c = a % b;
```

* **`!` not**

```javascript
var c = !oldEnough;
```

* **`==` is equal to** *(results in boolean)*

```javascript
var c = a == b;
```

* **`!=` is not equal to** *(results in boolean)*

```javascript
let c = a!= b;
```

* **`===` *strict* is equal to**

* **`!==` *strict* is not equal to**

## Functions

Takes (an) input(s), performs the function's actions, outputs the result.

*Naming a function:* start with an action word, e.g. `function doSomething()`

```javascipt
function myFunction (...) {
	... ...
};
```

**anatomy** *identifier / open parenthesis / parameter(s) / close parenthesis / curly bracket / code / curly bracket/ semi-colon*

Calling a function:

```javascript
let dog1 = myFunction();
console.log(dog1.name);
```

## If Statements
Checks conditions to determine what code to run next.
`if` `else if` `else`

```javascript
if ( ... ) {
	console.log('Do this');
}
```
**anatomy** *keyword / `{` / conditional / close patenthesis / curly bracket / code / curly bracket*




