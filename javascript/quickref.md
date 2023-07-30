# Quick Reference Javascript

## 1 Lexical Structure

### 1.1 Comments

```javascript
// single line comment

/*
  Multi-line comment
 */
```

### 1.2 Literals

```javascript
1         // Number one
1.5       // Number one point five
'Hello'   // String
true      // Boolean
false     // Boolean
null      // Null object
```

### 1.3 Declarations

|       |                                                                                 |
|-------|---------------------------------------------------------------------------------|
| var   | Declares a variable, optionally initializing it to a value                      |
| let   | Declares a block-scoped, local variable, optionally initializing it to a value. |
| const | Declares a block-scoped, read-only named constant.                              |

## 2 Numbers
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Numbers_and_dates

### 2.1 Integer

base-10 integer
```javascript
1
10
123
1000
```

hexadecimal literal begins with `0x` or `0X`
```javascript
0xff      // 255
0XABCD    // 43981
```

In ES6, binary (base 2) or octal (base 8) using prefixes 0b/0B and 0o/0O

### 2.2 Floating-point


## Quick Notes

**Property Access** 

```javascript
expression . identifier
expression [ expression ]
```

Examples

```javascript
let team = {size:5}
team.size
team["size"]

```

**Conditional Property Access**

```javascript
expression ?. identifier
expression ?.[ expression ]
```

Examples

```javascript
let a = {}
a?.b        // undefined
```


## References

https://developer.mozilla.org/en-US/docs/Web/JavaScript

