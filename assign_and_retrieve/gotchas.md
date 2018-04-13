### Array / Object Gotchas ¯\\\_(ツ)\_/¯

Cannot be reassigned, but can be modified

```js
const interests = ["paddleboarding", "racquetball"]
interest.push("tennis")

interests
// => ["paddleboarding", "racquetball", "tennis"]

interests = ["baseball", "basketball"]
// => Uncaught TypeError: Assignment to constant variable.
```

---

### Array / Object Gotchas ¯\\\_(ツ)\_/¯

Cannot be reassigned, but can be modified

```js
const me = {name: "Andy", age: 35}
me.age = 36

me
// => {name: "Andy", age: 36}

me = {name: "Someone Else"}
// => Uncaught TypeError: Assignment to constant variable
```

---

### `Object.freeze`

If we want array / object constants to be truly immutable

```js
const me        = {name: "Andy", age: 35}
const interests = ["paddleboarding", "racquetball"]

Object.freeze(me)

me.interests = interests
// => ["paddleboarding", "racquetball"]

me.interests
// => undefined

Object.freeze(interests)

interests.push("tennis")
// => Uncaught TypeError: Cannot add property 2, object is not extensible
```
