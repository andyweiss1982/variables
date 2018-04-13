### Assignment

* `const`: set it and forget it

```js
const name              = "Andy"
const birthplace        = "New Jersey"
const age               = 31
const job               = "teacher"
const careerAspiration  = "developer"
```

---

### Retrieval

* `console.log`
* String interpolation

https://repl.it/@andyweiss1982/goals

---

### Advanced Retrieval
#### (Working with Variables)

* Math
* Reassignment
* (Use `const` unless you know value will change)

https://repl.it/@andyweiss1982/goals2

---

### Arrays

Arrays are zero-indexed

```js
let cities = ["Miami", "New York", "Los Angeles"]

cities[0]
// => "Miami"

cities[1]
// => "New York"

cities[2] = "Chicago"

cities
// => ["Miami", "New York", "Chicago"]
```

---

### Objects

Objects can be retrieved by key

```js
let teams = { miami: 'heat', new_york: 'knicks' }

teams.miami
// => 'heat'

teams.new_jersey = "nets"

delete teams.new_jersey

teams['brooklyn'] = "nets"
```
