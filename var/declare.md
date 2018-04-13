## `var`

* Kind of old school, but not dead yet
* Doesn't care how often you declare it

```
var rhyme = 1
var rhyme = 2
var rhyme = "buckle my shoe"
var rhyme = 3
var rhyme = 4
var rhyme = "shut the door"
```

---
## `var`

Best practice to declare once at top of scope

```js
var rhyme

rhyme = 1
rhyme = 2
rhyme = "buckle my shoe"
rhyme = 3
rhyme = 4
rhyme = "shut the door"

```

---
## `var`

Things will be OK as long as you call it somewhere

```js
console.log(foo)
// undefined

var foo
```
