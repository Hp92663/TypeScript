
# TypeScript Tutorial


### Introduction
- TypeScript is enhance version of JavaScript

- TypeScript is a syntactic superset of JavaScript which adds static typing.

- This basically means that TypeScript adds syntax on top of JavaScript, allowing developers to add types.

- TypeScript is not new language, this is just add new feature in JavaScript.

- TypeScript add types like string, number, bool etc.

- We can add Object - Oriented way with TypeScript for code is well managed.

* TypeScript can't run in browser directly. It can TypeScript compiler convert the code for TypeScript to JavaScript.

### Version & History

- TypeScript created by Microsoft.
 
- Current Version is 5.2.2

- First released on 1 Oct 2012





## Installation

### TypeScript in Your Project

- Install TypeScript with npm
```bash
  npm install typescript --save-dev
```



### Globally Installing TypeScript

You can use npm to install TypeScript globally, this means that you can use the tsc command anywhere in your terminal.

Install TypeScript with npm

```bash
  npm install -g typescript

```
    
## Usage/Examples

For example

```javascript

function add (x, y) {
  return x+y;
}

console.log(add('2', '3'))

# output - 23
 
```


* Here add value but it van concat the value of number
because given value is in a string format

* JavaScript can't throw error so that use a TypeScipt


For example

```javascript

function add (x:number, y:number) {
  return x+y;
}

// throw error type is mismatched 
// Argument of type 'string' is not assignable to parameter of type 'number'.

console.log(add('2', '3'))


console.log(add(2, 3))

# output - 5

```
