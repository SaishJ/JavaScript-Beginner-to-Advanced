# Logic and Control Flow

## Conditional Statements

### If-Else statement
```javascript
if (condition) {
  // code to be executed if the condition is true
} else {
  // code to be executed if the condiyion is false
}
```

### If- Else If -Else statement
```javascript
if (condition1) {
  // code to be executed if the condition is true
} else if (condition2) {
  /* code to be executed if the
     condition1 is false and
     condition2 is true */
} else {
  /* code to be executed if
     condition1 is false and
     condition2 is false */
}
```

### Switch statement
```javascript
switch (expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
```

### Ternary Operator
```javascript
condition ? exprIFTrue : exprIfFalse
```
> condition: An expression whose value is used as a condition.

> exprIfTrue: An expression which is executed if the condition is truthy.

> exprIfFalse: An expression which is executed if the condition is falsy.

### Truthy / Falsy Values
#### FALSY Values
* false
* 0 (zero)
* "", '', `` (empty strings)
* null
* undefined
* NaN (not a number)

#### TRUTHY Values
* Everything that is not FALSY
