# JS Data Structures presentation


## Primitives


## Object

### Map

```js
const map = new Map();

map.set("😂", "Cray things");
map.set("🧠", "Please use it, it's free");

map.get("🧠"); // Please use it, it's free
map.size; // 2
```

- Iterable
- Ordered keys
- Cool methods: get, set, has, size, delete, clear ...

### WeakMap

```js
const weak_map = new WeakMap();

const a = {
id: 1,
emotion: "😆",
};

const b = {
id: 1,
emotion: "😇",
};

weak_map.set(a, "I'm glad");
weak_map.set(b, "I'm zen. Don't worry");

weak_map.get(a); // I'm glad
```

- ..map
- Keys are only objects
- Keys are not enumerable, cannot use __.size__


### Set

```js
const set = new Set();

set.add(1);
set.add(1);
set.add(1);

set; // 0 => 1
```

- Unique value, all types
- Iterable
- Cool methods like map: add, has, delete, size


### WeakSet

- Weak reference: not yet understand
- Set of only objects
- Not enumerable

### Object
