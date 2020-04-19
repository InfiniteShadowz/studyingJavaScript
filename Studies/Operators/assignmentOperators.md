# Assignment Operators

This type of operators assign values to variables or variables to variables.

## Assignment:

- **`=`** ----> assign a value to a variable or a variable to a variable.

_ex:_ 

```javascript
var x = 10;
var y;
y = "string!";
```


## Increment:

- **`++`** ----> increment by 1 and assign it to the variable refered in the same time.

_ex:_ 

```javascript
var x = 10;
var y = 5;
x ++;
//now x = 11
y ++;
//now y = 6;
```

_It is same as `x = x + 1`_
_It is same as `y = y + 1`_


## Decrement:

- **`--`** ---->  Decrease by 1 and assign it to the variable in the same time.

_ex:_ 

```javascript
var x = 10;
var y = 5;
x --;
//now x = 9
y --;
//now y = 4;
```

_It is same as `x = x - 1`_
_It is same as `y = y - 1`_


## Addition Assignment:

- **`+=`** ----> add any value or variable and assign it in the same time.

_ex:_ 

```javascript
var x = 5;
var y = 3;
//equals to y = y + 2;
y += 2;
//equals to x = x + y;
x += y;
console.log(x);

```
> CONSOLE: 10


- **`-=`** ----> subtract any value or variable and assign it in the same time.

_ex:_ 

```javascript
var x = 5;
var y = 3;
//equals to y = y - 2:
y -= 2;
//y = 1
//equals to x = x - y:
x -= y;
console.log(x);

```
> CONSOLE: 4


## Multiplication Assignment:

- **`*=`** ----> multiply a number by another and assign it in the same time.

_ex:_ 

```javascript
var x = 10;
var y = 5;
// x = x * y:
x *= y;
console.log(x)
```
> CONSOLE: 50

It is same as `x = x * y`


## Division Assignment:

- **`/=`** ----> divide a number by other and assign it in the same time.

_ex:_ 

```javascript
var x = 10;
var y = 5;
//x = x / y:
x /= y;
console.log(x);
```
> CONSOLE: 2 

## Remainder Assignment:
- **`%=`** ---> return the remainder of the divide operation between the given numbers and assign it in the same time.

_ex:_ 

```javascript
var x = 13;
var y = 5;
x %= y;
console.log(x);
```
> CONSOLE: 3


