## `const`

* Like `let`, can only be declared once per variable
* Must be assigned at the same time it is declared
* Value can not be reassigned

```
const rhyme
// => Uncaught SyntaxError: Missing initializer in const declaration

const rhyme = 1
const rhyme = 2
// => Uncaught SyntaxError: Identifier 'rhyme' has already been declared

const other_rhyme = "buckle my shoe"
other_rhyme = 3
// => Uncaught TypeError: Assignment to constant variable.
```

https://repl.it/@andyweiss1982/headsShouldersKneesToes2
