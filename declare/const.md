## `const`

* Like `let`, can only be declared once per variable
* But its value can not be reassigned (more on this soon)
* Best for values that will never change

```
const rhyme = 1
const rhyme = 2
// => Uncaught SyntaxError: Identifier 'rhyme' has already been declared
const other_rhyme = "buckle my shoe"
```
