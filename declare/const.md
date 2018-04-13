## `const`

* Like `let`, can only be declared once per variable
* But it must be assigned at the same time it is declared
* Value can not be reassigned (more on this soon)
* Best for values that will never change

```
const rhyme
// => Uncaught SyntaxError: Missing initializer in const declaration

const rhyme = 1
const rhyme = 2
// => Uncaught SyntaxError: Identifier 'rhyme' has already been declared
const other_rhyme = "buckle my shoe"
```

https://repl.it/@andyweiss1982/headsShouldersKneesToes2
