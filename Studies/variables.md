# Variables

## Declaring a Variable in JS:

to declare a variable in JavaScript, its necessary to use `var`:

```javascript
var name;
var a;
var b;
```

_PS: variables in JS may not contain spaces or start with a number._


## Variable Assigning in JS:

to assign a value to a variable or a variable to a variable, it is used the assignment operator `=`:

```javascript
//Declaration:
var a;
// you can declare a variable and assign it at the same time too:
var b = 5;
var c;

//Assignment:
c = b;
b = a;
```


## Uninitialized variable in JS:

when variables are only declared, they have an initial value of `undefined`. If its tried to do math operations in `undefined` it returns `NaN` (Not a Number).

_ex0:_
```javascript
//Those are uninitialized variables:
var name;
var a;
var b;
```

_ex0:_

```javascript
//Those are initialized variables:
var name = "FShinoda;
var a = 5;
var b = 0;
//They will not return undefined.
```


