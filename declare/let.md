## `let`

* Just like `var`, value can change
* But can only be declared once per variable

```
let rhyme

rhyme = 1
let rhyme = 2
// => Uncaught SyntaxError: Identifier 'rhyme' has already been declared

let other_rhyme = "buckle my shoe"
otherRhyme = 3
otherRhyme = 4
let other_rhyme = "shut the door"
// => Uncaught SyntaxError: Identifier 'otherRhyme' has already been declared
```

---

## `let`

Hoisting rules similar to `var`

```js
console.log(foo)
// undefined

let foo
```


```js
console.log(foo)
// ReferenceError: foo is not defined
```
