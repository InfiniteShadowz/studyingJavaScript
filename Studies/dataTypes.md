# Data Types (JS)

## How to return the type of a variable using `typeof`:

```javascript
var x = 20;
console.log(typeof x);
``` 
> CONSOLE: number


## Types:

## Number:

- JavaScript has only one type of numbers. It does not differenciate float numbers and integers (as python or java does for example)

_ex:_

```javascript
var x = 34.50;
var x1 = 34; 
``` 
- `Infinity`

- `NaN`

## String:

- ### Single and double quotes without complexity:

In JavaScript you can use single or double quotes. 

```javascript
var name = "Fernanda Shinoda";
var question = 'Who is "john"?';
``` 


- ### Single and double quotes with complexity:

Sometimes, in JS, you´ll need to use a group of single quotes or double quotes and it becomes a problem. But it is simply solved using `\` (backslash) before the same quote used to start the string.

_ex:_

```javascript
//wrong:
var shoutBad = 'Alan asks, let's go?"';
//right:
var shoutGood = 'Alan asks, "let\'s go?"';
``` 

- ### newline command `\n`:

`\n` throws string to the next line in output

_ex:_

```javascript
var fullName = "Fernanda\nShinoda"
``` 

- ### newline command `\t`:

`\t` throws string to the next indentation point in output

_ex:_

```javascript
var fullName = "Fernanda\tShinoda"
``` 


## Boolean:

basically true or false.

- `true` ---> returns a true statment 
- `false`----> returns a false statment



## undefined

## object

- `array`
- `null`

## function










